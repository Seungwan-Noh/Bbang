# Miruku E-commerce store including shopping cart.

* Deployed on Heroku.
* Backend API = **GraphQL**.
* Database utilizes a **MongoDB with mlab** .
* Client-side API requests are generated from **Apollo Client** wrapped components.
* The rest of the app sits on **React.js** & **React Router\*(V4)** (with Code splitting).

## Site Address

* https://mirukufresh.herokuapp.com/

## Splash Preview

<img src="https://www.dropbox.com/s/mmkqzwxpu1tamgr/miruku-homepage.png?dl=0" />

## SETUP:

* `npm i` to install dependencies
* `npm start` for production server
* `cd client && npm start` for react server

## TECHNOLOGIES:

### Libraries & Packages

    * Uses _react-router-dom_ for dispatching route changes & tracking nav history.
    * Uses _react-apollo_ for requiring data from server, or CRUD with mongoDB.
    * Uses _apollo-grpahql_ for providing API calls directly to componenents.
    * Uses _react-toastify_ for toasting messages to customers.
    * Uses _mailgun-js_ for sending an confirm email to customer for success of order.
    * Uses _bootstrap_ for responsive layout.
