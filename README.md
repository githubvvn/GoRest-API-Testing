# GoRest API Testing

## Project Overview
API testing project for the GoRest REST API using Postman. Covers complete CRUD operations and data-driven testing with assertions for status codes, response validation, and error handling.

## Tools Used
- Postman
- GoRest API (https://gorest.co.in)

## Structure
- **CRUD Operations** — GET, POST, PUT, DELETE requests with chained test cases
- **Data Driven** — Multiple users created/verified/deleted using a JSON data file via Collection Runner

## Test Coverage
- 17+ test cases across all requests
- Status code validation (200, 201, 204, 404, 422)
- Response body validation (id, name, email, gender, status)
- Dynamic data handling using collection variables (UID, userName)
- Pre-request script to validate UID existence before update/delete
- Data driven testing using a JSON file

## How to Run
1. Import the collection JSON from `Collections/` into Postman
2. Import the environment JSON from `Environments/` into Postman
3. Add your own GoRest API bearer token in the environment
4. Run individual requests, or use Collection Runner for data-driven tests
