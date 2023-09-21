# Reactjs Nodejs PostgreSQL Example

## Nodejs PostgreSQL CRUD Design Application


We have 4 main blocks for the application:

- For building RestAPIs in Nodejs application, we use Express framework.
- For interacting with database PostgreSQL, we use Sequelize ORM.
- We define APIs URL in router.js file
- We implement how to process each API URL in controller.js file
- We use Bootstrap and JQuery Ajax to implement frontend client.

## Reactjs CRUD Application Design


– Reactjs CRUD Application is designed with 2 main layers:

React.js components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
Ajax is used by Reactjs component to fetch (post/put/get/delete) data from remote restapi by http request

Reactjs CRUD Application defines 5 components:

- Home.js is used serve as the landing page for your app.
- AppNavbar.js is used to establish a common UI feature between components.
- CustomerList.js is used to show all customers in the web-page
- CustomerEdit.js is used to modify the existed customer
- App.js uses React Router to navigate between components.
