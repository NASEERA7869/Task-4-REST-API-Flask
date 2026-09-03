# Task 4 - REST API with Flask

## Objective

Create a REST API that manages user data using Flask.

## Tools Used

- Python
- Flask
- Postman

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/users` | Get all users |
| GET | `/users/<id>` | Get a specific user |
| POST | `/users` | Create a new user |
| PUT | `/users/<id>` | Update a user |
| DELETE | `/users/<id>` | Delete a user |

## Features

- Retrieve all users
- Retrieve a specific user
- Create a new user
- Update an existing user
- Delete a user
- Handle user-not-found errors with 404 status

## Data Storage

User data is stored in an in-memory list.

## How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
```

2. Run the Flask application:

```bash
python app.py
```

3. Open the API:

http://127.0.0.1:5000/users

## API Testing

The API was tested using Postman with GET, POST, PUT, and DELETE requests.

## Status Codes Tested

- 200 OK - Successful request
- 201 Created - User successfully created
- 404 Not Found - User does not exist

