# Restful Booker API Testing

## Project Overview

This project demonstrates API testing using Postman against the Restful Booker API. It covers CRUD operations, authentication, dynamic variable chaining, and automated response validation.

## Target API

https://restful-booker.herokuapp.com/apidoc/index.html

## Tools Used
- Postman
- REST API
- JSON
- GitHub

## Test Coverage

| HTTP Method | Endpoint | Test Scenario |
|---|---|---|
| POST | /auth | Generate authentication token |
| GET | /booking | Retrieve booking IDs |
| GET | /booking/{id} | Retrieve booking details |
| POST | /booking | Create a new booking |
| PUT | /booking/{id} | Update an existing booking |
| DELETE | /booking/{id} | Delete a booking |

## Testing Features

- Status code validation
- JSON response validation
- Dynamic environment variables
- Authentication token handling
- Request chaining
- Positive and negative test scenarios
- Response data verification

## How to Run

1. Download the Postman collection JSON file and the Postman environment.
2. Open Postman.
3. Click Import and select the downloaded collection.
4. Configure the `baseUrl` environment variable.
5. Run the authentication request first.
6. Execute the collection using Collection Runner.


Reyneil Rodelas

Entry-Level IT Professional | QA Testing | API Testing
