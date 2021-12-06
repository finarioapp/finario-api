# Finario API Documentation

Provides documentation and OpenAPI 3.0.1 spec for the Finario API versions >= 1.1.0. For previous API versions, see [here](https://github.com/finarioapp/api).

Download the latest spec [here](./api-1.1.0.yaml).

To gain access to the Developer Portal, where you can generate authentication tokens, please contact your Finario account manager.

# Test Cycle

Navigate to the root of the repo. To install npm dependencies:

`npm install`

To validate the specification:

`npm run lint`

To test the generation of the documentation:

`npm run serve`

To generate a no-dependency HTML file:

`npm run gen`
