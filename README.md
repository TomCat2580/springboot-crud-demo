# Spring Boot CRUD Demo

This project is a simple backend application built with Spring Boot.
It was created as a learning and demonstration project for my application
for an apprenticeship as a Software Developer (Fachinformatiker für Anwendungsentwicklung).

## Technologies
- Java
- Spring Boot
- Spring Web (REST API)
- Spring Data JPA
- H2 Database
- Maven

## Features
- Create, read, update and delete data (CRUD)
- RESTful API with JSON
- Clear project structure (Controller, Service, Repository)
- Database access using Spring Data JPA

## Project Structure
- Controller: handles HTTP requests
- Service: contains business logic
- Repository: database access layer
- Entity: data models

## Example Endpoints
- GET /api/users
- POST /api/users
- PUT /api/users/{id}
- DELETE /api/users/{id}

## How to Run
1. Clone the repository
2. Start the application:
`mvn spring-boot:run`
3. Test the API using a browser or Postman

## Learning Goal
The goal of this project is to practice basic backend development concepts
such as REST APIs, CRUD operations and layered application architecture.

