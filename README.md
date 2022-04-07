# Northcoders Final Project API

## Part-Time Pet API :dog: :rabbit: :cat:

## Description

Part-Time Pet API is the middleware created to handle all queries to the database. This seperated the responsibilities held by the front-end and the back-end whilst also allowing for throrough testing.

## The avaialable end-points are as follows:

- GET /api/users
- GET /api/users/:userid
- GET /api/pets/:petId
- GET /api/users/:userId/pets
- GET /api/users/:userId/reviews
- POST /api/users
- POST /api/users/:userId/pets
- POST /api/users/:userId/reviews
- PATCH /api/users/:userid
- PATCH /api/pets
- PATCH /api/pets/:petId
- DELETE /api/users/:userid
- DELETE /api/users/:userId/reviews
- DELETE /api/pets/:petId

## Testing

This API was built using Test Driven Development (TDD) Methodology. Extensive testing was used in it's creation and is included in the repo. Mocha and Chai were the technologies used for testing.
