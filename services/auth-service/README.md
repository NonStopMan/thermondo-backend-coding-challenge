# Auth Service

The Auth Service is responsible for handling user authentication and authorization in the Thermondo backend system.

## Features

- Token generation: Allows users to generate tokens so they can use it across our system
- Token validation: Allow backend service to verify the user token passed.

## Installation

To install and run the Auth Service, follow these steps:

1. Navigate to the project directory: `cd auth-service`
2. Install dependencies: `yarn install`
3. Configure environment variables: Create a `.env` file and set the required variables.
4. Start the service: `yarn start`

## API Documentation

The Auth Service provides a RESTful API with the following endpoints:

- `POST /auth/generate-token`: creates a new token for the user using username and password.
- `POST /auth/validation-token`: validates the given token passed to the endpoint.

For detailed information about the Auth Service API endpoints, refer to the [API documentation](http://localhost:3000/api).

## Contributing

We welcome contributions from the community. To contribute to the Auth Service, please follow our [contribution guidelines].

## License

The Auth Service is open source and released under the [MIT License].
