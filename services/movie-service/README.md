# Movie Service

The Movie Service is a backend service that provides information and functionality related to movies. It allows users to retrieve movie details, search for movies, and manage movies.

## Features

- Retrieve movie details: Users can get detailed information about a specific movie by providing its ID.
- Retrieve movies list and you can use paging
- Movies management (create, update, delete)

## Installation

To install and run the Movie Service, follow these steps:

1. Navigate to the project directory: `cd movie-service`
2. Install dependencies: `yarn install`
3. Configure environment variables: Create a `.env` file and set the required variables.
4. Start the server: `yarn start`

## Usage

1. Start the movie service: `yarn start`
2. Access the movie service API at `http://localhost:3000`
3. Access the movie service API documentation at `http://localhost:3000/api`

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Redis
- Jest

## API Documentation

The Movie Service provides a RESTful API with the following endpoints:

- `POST /movies`: creates a movies in movies database.
- `GET /movies/:id`: Retrieves detailed information about a specific movie.
- `GET /movies`: returns movies list with the use of pagination.
- `DELETE /movies/:id`: Removes a movie our movies database.
- `GET /movies/:id/exist`: checks if the movie exists in our database.
- `PUT /movies/:id` : update the information about the movie.

For detailed documentation and examples, please refer to the [API Documentation](http://localhost:3000/api).

## Contributing

Contributions to the Movie Service are welcome! If you would like to contribute, please follow the guidelines outlined in [CONTRIBUTING.md].

## License

The Movie Service is open source and released under the [MIT License].
