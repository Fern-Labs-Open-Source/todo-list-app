# API Version 1

This directory contains the first version of the Todo List API.

## Available Endpoints

### Authentication
- POST /api/v1/auth/register - Register a new user
- POST /api/v1/auth/login - Authenticate a user
- POST /api/v1/auth/logout - Log out a user

### Tasks
- GET /api/v1/tasks - List all tasks
- POST /api/v1/tasks - Create a new task
- GET /api/v1/tasks/:id - Get a specific task
- PUT /api/v1/tasks/:id - Update a task
- DELETE /api/v1/tasks/:id - Delete a task

### Categories
- GET /api/v1/categories - List all categories
- POST /api/v1/categories - Create a new category
- GET /api/v1/categories/:id - Get a specific category
- PUT /api/v1/categories/:id - Update a category
- DELETE /api/v1/categories/:id - Delete a category