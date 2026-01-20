# Financial Tracker API

 **Work in Progress** - This project is actively being developed.

## Overview
The Financial Tracker API is a backend REST API built with Spring Boot that allows users to track personal financial transactions, manage budgets, and analyze spending patterns. 
The goal of this project is to practice building a real-world, enterprise-style backend application using clean architecture and best practices.

This project is being developed incrementally and will continue to evolve.

---

## Tech Stack
- Java
- Spring Boot
- Spring Web
- SQL (relational database)
- Maven
- JUnit 5

---

## Planned Features
- Create, read, update, and delete financial transactions
- Track income vs expenses
- Monthly spending summaries
- Budget limits per category
- Global error handling using exceptions
- Unit tests for service-layer business logic

---

## Architecture
The application follows a layered architecture:

controller → service → repository → database

- **Controller layer** handles HTTP requests and responses.
- **Service layer** contains business logic and application rules.
- **Repository layer** manages data access and database interactions.

This structure promotes separation of concerns, testability, and maintainability.

