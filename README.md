# hkcs-java-assignment
Spring Boot CRUD API with MongoDB for HKCS Internship Assignment
# HKCS Java Developer Internship Assignment

### Project Overview
This project is a RESTful API built using Spring Boot and MongoDB to perform CRUD (Create, Read, Update, Delete) operations.

### Technologies Used
- Spring Boot
- Spring Data MongoDB
- Maven
- Java 17/21

### Setup Instructions
1. Clone this repository to your local machine.
2. Ensure MongoDB is running locally on port 27017.
3. Configure your database settings in `src/main/resources/application.properties`.
4. Run the application using: `mvn spring-boot:run`

### API Endpoints
- **GET** `/api/items` - Fetch all items
- **POST** `/api/items` - Create a new item
- **PUT** `/api/items/{id}` - Update an existing item
- **DELETE** `/api/items/{id}` - Delete an item

### Testing
- Use Postman to test the API endpoints by sending JSON payloads.
