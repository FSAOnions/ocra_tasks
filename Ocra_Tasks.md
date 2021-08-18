# Ocra \* Tiers

## Proof of Concept

- be able to select a 3D item and place it on a surface

## Tier 1: MVP Dining Experience

### As a customer, I want to be able to:

- access a deployed version of the website so I can browse and order food items through their camera.
- view all available products in VR so I can pick from a variety.
- view a single product so I can see more details.
- add a product to my VR cart so I can collect my desired products in one place.
- edit my cart if I change my mind:
  - remove a product in my cart.
- pay for the bill (or fake checkout).

### As an engineer, I want to:

- have a well-seeded database so that I am able to simulate a number of different scenarios for the user stories below.
  - we are able to test multiple 3D food items on a surface.

## TIER 2: E-Commerce Essentials

<details><summary>Click Here To Open</summary>

### As a logged-in customer, I want to be able to:

- pay for the items in my cart if I leave 5 meters away from the restaurant and it will automatically include 30% tip.
- see all products that belong to a certain category.
- view and edit my user profile so I can update my information when necessary.
- have a persistent cart so I can revisit and pick up where I left off.
- see my order history so I can remember my previously purchased items and their prices at the time of purchase.

</details>

## TIER 3: Extra Features & Flair

<details><summary>Click Here To Open</summary>

### As an administrator, I want to be able to:

- allow customers to have a variety of payment method options in order to increase checkout conversion.
  - _Begin by integrating Stripe, and, if interested, dive into integrating PayPal, Venmo, Braintree, or Bitcoin._
- edit products and manage users through a dashboard so I can easily make changes and assessments as necessary.
- add new items to the menu.
- change item details.
- verify 21 and older.
- manually check people out (paying cash).

### As a customer, I want to be able to:

#### Receive Notifications

- receive an email confirmation when placing an order so that I can easily reference it when needed without visiting my account.
- be notified when certain events occur so that I am informed of my actions.
  - _For example, when I add a product to my cart, there is a toast notification that pops up in the corner of the page with an appropriate message for that action._

</details>
