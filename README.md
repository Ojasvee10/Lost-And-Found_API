# Lost and Found API

This project is a RESTful API developed with Spring Boot that helps manage lost and found items within a college campus.

## Features
- Report a lost item
- View all reported lost items
- RESTful API built with Spring Boot
- Data management using Spring Data JPA
- Uses an H2 in-memory database for storage

## Technologies
- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Postman (API Testing)

## API Endpoints

POST /items  - Add a new lost item
GET /items   - Retrieve the list of all lost items

## Example Request

POST /items

{
  "itemName": "Wallet",
  "description": "Blue leather wallet",
  "color": "Blue",
  "locationFound": "Library",
  "reportedBy": "Ojasvee Gupta",
  "contactNumber": "1234567890"
}
