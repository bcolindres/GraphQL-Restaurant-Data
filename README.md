# GraphQL Restaurant Data Project

This project implements a GraphQL API for managing restaurant data including CRUD operations for restaurants and dishes.

## Overview

The project uses Node.js along with Express.js for creating a GraphQL server. It defines a schema with queries and mutations to interact with restaurant data. The data is stored in memory as a simple array of objects for demonstration purposes.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/graphql-restaurant-data-project.git

2. Navigate to the project directory:
   cd graphql-restaurant-data-project

3. Install dependencies:
   npm install

# Usage

1. Start the GraphQL server:
   npm start

2. Open your browser and navigate to http://localhost:5500/graphql to access the GraphiQL interface.

3. Use the provided queries and mutations to interact with the restaurant data.

# Queries and Mutations
Queries
restaurant(id: Int): Restaurant: Get a single restaurant by ID.
restaurants: [Restaurant]: Get a list of all restaurants.
Mutations
setRestaurant(input: RestaurantInput): Restaurant: Create a new restaurant.
deleteRestaurant(id: Int!): DeleteResponse: Delete a restaurant by ID.
editRestaurant(id: Int!, input: RestaurantInput): Restaurant: Update a restaurant by ID.

# License
This project is licensed under the MIT License.

