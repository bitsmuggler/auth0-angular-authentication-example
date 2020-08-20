# Auth0 Angular Example (Authorization Code Flow)

[![Netlify Status](https://api.netlify.com/api/v1/badges/e54bab85-555a-44b3-aecb-7f75a8559878/deploy-status)](https://app.netlify.com/sites/auth0-angular-authentication-example/deploys)

This example shows Auth0 client authentication with Angular. It's the Authorization Code Flow

👉 [Demo](https://auth0-angular-authentication-example.netlify.app/) 

👉 Under the hood [Authorization Code Grant](https://tools.ietf.org/html/rfc6749#section-4.1)

## Configuration Auth0

* Register and setup your tenant
* Create an application ``Applications > Create Application > Type "Single Page Web Applications"``
* Set the following attributes
    * Allowed Callback URLs: ``http://localhost:4200``
    * Allowed Logout URLs: ``http://localhost:4200``
    * Allowed Web Origins: ``http://localhost:4200``

## Configuration Angular App

* Edit ``environment.ts``
    * ``auth0ClientDomain``to app domain (``Application Settings > Basic Information > Domain``)
    * ``auth0ClientId`` to app client id (``Application Settings > Basic Information > Client Id``)

## Run it

* Install dependencies ``npm install`` (+ probably the ng cli ``npm install -g @angular/cli`` or run the ``serve command``via ``npx``)
* Run ``ng serve``


## Resources

* 
* [Authorization Code Flow](https://auth0.com/docs/flows/authorization-code-flow)

