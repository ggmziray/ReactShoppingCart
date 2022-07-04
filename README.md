# ReactShoppingCart

<h3>Description</h3>
MIT exercise to create a shopping cart application with React, built a restocking feature and integrated backend set up database with Strapi and Postman.

## How it Works

In the shopping cart, you can add and remove products from your shopping cart. Aanother feature is resetting the stock. which makes a call to a Strapi API and get a fresh list of available products.

- There’s an input field on the page that contains the URL to the Strapi back end
- When a user clicks the “ReStock Products” button, a call is made to the Strapi back end specified in the input field
- The result of this call is an updated list of products
