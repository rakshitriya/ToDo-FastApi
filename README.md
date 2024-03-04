# To-Do App API using FastAPI

This repository contains a simple To-Do App API implemented using FastAPI, a modern, fast (high-performance) web framework for building APIs with Python. This API provides endpoints to manage To-Do items including creating, updating, deleting, and retrieving them.

## Setup

1. **Installation:**

   Make sure you have Python installed. Then, install the required dependencies using pip:

   ```bash
   pip install fastapi
   pip install uvicorn[standard]
   ```
2. **Running the Application**

    Run the following command to start the FastAPI application:
    ```bash
    uvicorn main:app --reload
    ```
    This command will start the server locally, and you can access the API through http://127.0.0.1:8000.

## API Endpoints

    GET /todos: Retrieve all To-Do items.
    GET /todos/{todo_id}: Retrieve a single To-Do item by its ID.
    POST /todos: Create a new To-Do item.
    PUT /todos/{todo_id}: Update an existing To-Do item.
    DELETE /todos/{todo_id}: Delete a To-Do item.

## API Documentation

The API documentation is automatically generated using Swagger UI. You can access it by visiting http://127.0.0.1:8000/docs after starting the server.

