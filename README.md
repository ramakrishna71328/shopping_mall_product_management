# Shopping Mall Product Management Module

## Project Overview

The Shopping Mall Product Management Module is a backend application developed using Java and Spring Boot.

The application provides REST APIs to perform CRUD operations on products. It uses Spring Data JPA and Hibernate for database interaction and PostgreSQL for data storage. Postman is used to test the REST APIs.

## Technologies Used

- Java 21
- Spring Boot 4.1.1
- Spring Data JPA
- Hibernate
- PostgreSQL 18.6
- Maven
- Eclipse
- Postman
- Git & GitHub

## Project Architecture

```text
Client / Postman
       |
       v
ProductController
       |
       v
ProductService
       |
       v
ProductRepository
       |
       v
Product Entity
       |
       v
PostgreSQL Database



Project Struture:

demo
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.tns.demo
│   │   │       ├── controller
│   │   │       │   └── ProductController.java
│   │   │       │
│   │   │       ├── entity
│   │   │       │   ├── Product.java
│   │   │       │   ├── MallAdmin.java
│   │   │       │   └── Mall.java
│   │   │       │
│   │   │       ├── repository
│   │   │       │   └── ProductRepository.java
│   │   │       │
│   │   │       ├── service
│   │   │       │   └── ProductService.java
│   │   │       │
│   │   │       └── DemoApplication.java
│   │   │
│   │   └── resources
│   │       └── application.properties
│   │
│   └── test
│
├── pom.xml
└── README.md
