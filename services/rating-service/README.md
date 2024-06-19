# Rating Service

The Rating Service is a backend service that provides information and functionality related to rating. It allows users to retrieve user ratings, create and update user ratings

## Features

- Create Movie Rating: User able to add or update his own rating for specific movie.
- Retrieve ratings list for specific user

## Installation

To install and run the Movie Service, follow these steps:

1. Navigate to the project directory: `cd rating-service`
2. Install dependencies: `yarn install`
3. Configure environment variables: Create a `.env` file and set the required variables.
4. Start the server: `yarn start`

## Usage

1. Start the rating service: `yarn start`
2. Access the rating service API at `http://localhost:3000`
3. Access the rating service API documentation at `http://localhost:3000/api`

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Jest

## API Documentation

The Movie Service provides a RESTful API with the following endpoints:

- `POST /ratings`: creates a user rating about movie.
- `GET /ratings/user/:id`: Retrieves all user rating information.

For detailed documentation and examples, please refer to the [API Documentation](http://localhost:3000/api).

## Contributing

Contributions to the Movie Service are welcome! If you would like to contribute, please follow the guidelines outlined in [CONTRIBUTING.md].

## License

The Rating Service is open source and released under the [MIT License].
