# Recipe Keeper API 🍲📚
Welcome to the Recipe Keeper Application API! This module provides endpoints for performing CRUD operations on recipes. It utilizes a JSON file for storage and FastAPI for the web server.

### Project Overview
The Recipe Keeper API enables users to manage recipes, offering endpoints to create, read, update, and delete recipes. It serves as the backend for the Recipe Keeper Application, facilitating seamless interaction with recipe data.

### API Endpoints
GET /recipes: Retrieve all recipes.
POST /recipes: Create a new recipe.
GET /recipes/{recipe_id}: Retrieve a specific recipe by ID.
PUT /recipes/{recipe_id}: Update a recipe by ID.
DELETE /recipes/{recipe_id}: Delete a recipe by ID.

### CORS Settings
The API is configured to allow requests from http://127.0.0.1:8000 to facilitate local development.

### Data Storage
Recipe data is stored in a JSON file (recipes.json). Ensure this file exists before running the API.

Happy cooking and recipe keeping! 🍳📖
