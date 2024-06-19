# Project Name: Thermondo Backend Coding Challenge - User Service

## Description

This project is part of the Thermondo Backend Coding Challenge and focuses on the User Service. The User Service is responsible for managing user-related operations such as user registration, credentials validation and user existence

## Features

- Register new user in our database.
- Validate user existence and credentials.
- Retrieve user Profile with the related ratings.

## Installation

To install and run the user Service, follow these steps:

1. Navigate to the project directory: `cd auth-service`
2. Install dependencies: `yarn install`
3. Configure environment variables: Create a `.env` file and set the required variables.
4. Start the server: `yarn start`

## Usage

1. Start the user service: `yarn start`
2. Access the user service API at `http://localhost:3000`
3. Access the user service API documentation at `http://localhost:3000/api`

## API Endpoints

- `POST /users` - Register a new user
- `/users/:id/exist` - check user existence
- `/users/:id/profile` - Get user profile information
- `/users/validate-credentials` - validate the given credentials for a user.

For detailed information about the Auth Service API endpoints, refer to the [API documentation](http://localhost:3000/api).

## Technologies Used

- Node.js
- Express.js
- MongoDB

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
