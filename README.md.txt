# Assignment 5 – API Testing with JMeter

## Project Overview
CRUD API testing using JMeter with CSV data-driven POST requests.

## Endpoints Tested
- POST /users (Manual)
- GET /users/1
- PATCH /users/1
- GET After PATCH /users/1
- DELETE /users/1
- GET After Delete /users/1
- POST /users (CSV Data)

## CSV Usage
- CSV file `users.csv` used for multiple POST requests
- Variable names: firstName,lastName,age

## Steps to Run Test Plan
1. Open `CRUD API Test.jmx` in JMeter
2. Ensure `users.csv` is in same folder
3. Run Thread Group
4. Check results in View Results Tree

## Note
GET After Delete returns 200 OK due to dummy API behavior.
