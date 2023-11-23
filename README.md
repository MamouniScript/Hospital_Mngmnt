# Spring Boot Patient Management

This project serves as an introduction to Java Enterprise Edition (JEE), Object-Relational Mapping (ORM), JDBC, JPA, Hibernate, and Spring Data. It provides hands-on experience with these technologies through a Spring Boot application designed for managing patient records.

## Project Overview

1. Creation of a new Spring Initializer project with dependencies:
   - JPA
   - H2
   - Spring Web
   - Lombok

2. Defining the JPA entity `Patient` with attributes:
   - id: Long
   - nom: String
   - dateNaissance: Date
   - malade: boolean
   - score: int

3. Configures the persistence unit in the application.properties file.

4. Creates a JPA repository interface for patient data management.

## Test Patient Management Operations

Explores and tests various patient management operations, including:

- Add patients
- View all patients
- View a specific patient
- Search for patients
- Update patient information
- Delete a patient

## Technologies Used

- Java Enterprise Edition (JEE)
- Object-Relational Mapping (ORM)
- JDBC
- Java Persistence API (JPA)
- Hibernate
- Spring Data
- Spring Boot
- H2 Database
- Spring Web
- Lombok

This app is console output based to view data.
