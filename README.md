Spring Boot E-Commerce Backend
Overview
This project is a backend REST API built using Spring Boot for an e-commerce system.
Currently, it implements Category management using a clean layered architecture.
The project focuses on backend fundamentals such as REST APIs, service-based design, and database interaction using JPA.

Tech Stack
Java
Spring Boot
Spring Data JPA
Hibernate
MySQL
Maven



Project Structure
The application follows a layered architecture:
controller  → handles HTTP requests
service     → contains business logic
repository  → handles database operations
model       → entity classes

This separation makes the code maintainable and scalable.

Features Implemented
Category CRUD APIs
RESTful API design
Controller–Service–Repository pattern
Database integration using JPA



API Endpoints
Category APIs
MethodEndpointDescriptionGET/api/categoriesFetch all categoriesPOST/api/categoriesCreate a new categoryPUT/api/categories/{id}Update categoryDELETE/api/categories/{id}Delete category


How to Run the Project
Clone the repository
git clone https://github.com/harshagupta2005/sb-ecom.git
Open the project in IntelliJ / Eclipse
Configure database in application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=your_username
spring.datasource.password=your_password



Run the main Spring Boot application
SbEcomApplication.java
Test APIs using Postman



What This Project Demonstrates:-

Understanding of Spring Boot backend development
Proper REST API design
Clean code structure
Database interaction using JPA






