# RESTful_Restaurants
Build an API to store and retrieve information about your favourite restaurants!

# Restaurant Review Site API

This is an API for a restaurant review site that allows users to view a list of saved restaurants, add to that list, star their favorite restaurants, and leave comments about these places.

## Getting Started

### Prerequisites

To run this API, you will need to have the following installed on your system:
* Node.js (version 14 or later)
* NPM (version 6 or later)

### Installing

To install the necessary packages, run the following command in your terminal:

npm install


### Running the API

To start the API, run the following command in your terminal:

npm start


This will start the API on port 3000 by default.

## Endpoints

This API has the following endpoints:

### GET /restaurants

Returns a list of all the saved restaurants.

### POST /restaurants

Adds a new restaurant to the list.

Request Body:
```json
{
  "name": "string",
  "cuisine": "string",
  "address": "string"
}

GET /restaurants/:id
Returns details of a specific restaurant with the given ID.

PUT /restaurants/:id/star
Stars a specific restaurant with the given ID.

DELETE /restaurants/:id/star
Removes the star from a specific restaurant with the given ID.

POST /restaurants/:id/comments
Adds a comment to a specific restaurant with the given ID.

Request Body:
{
  "text": "string"
}

GET /restaurants/:id/comments
Returns all the comments for a specific restaurant with the given ID.

Conclusion
This API allows users to store and retrieve information about their favorite restaurants, including the ability to star and comment on specific restaurants. If you have any questions or issues, please feel free to contact me.


