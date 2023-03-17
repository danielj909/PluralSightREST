# PluralSightREST

This repository demonstrates a simple and quick REST API which implements CRUD operations for the entities of `Speakers` and `Sessions` from a Postgre Database in a Docker container. This is a simple conference demo for which sample mock data was provided by Pluralsight as part of their Spring Boot Course. Technologies used are Spring Boot, Spring Data JPA, Hibernate, Docker, REST API, Postgre Database, and Postman tool for testing the API.

## Technologies Used
- Spring Boot
- Spring Data JPA
- Hibernate
- Docker
- REST API
- Postgre Database
- Postman tool for testing the API

## API Endpoints
### Speakers
- GET /api/speakers - get all speakers
- GET /api/speakers/{id} - get speaker by id
- POST /api/speakers - create new speaker
- PUT /api/speakers/{id} - update speaker by id
- DELETE /api/speakers/{id} - delete speaker by id

### Sessions
- GET /api/sessions - get all sessions
- GET /api/sessions/{id} - get session by id
- POST /api/sessions - create new session
- PUT /api/sessions/{id} - update session by id
- DELETE /api/sessions/{id} - delete session by id

![Postman Screenshot](https://i.imgur.com/ROkkYL4.png)
