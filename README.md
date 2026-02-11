# VetClinic Pro – Backend API

RESTful backend for the integrated veterinary clinic management system.
Developed with **Java 17 and Spring Boot 3**, following software architecture best practices and security standards.

---

## Technology Stack

* **Java 17**
* **Spring Boot 3**
* **Spring Security + JWT**
* **Spring Data JPA (Hibernate)**
* **PostgreSQL**
* **Maven**
* **Docker (optional)**

---

## Architecture

The system is designed following these architectural approaches:

1. **Client–Server Architecture**
   Communication through a REST API between the client (frontend) and the backend server.

2. **Layered Architecture (Multitier)**
   Clear separation of responsibilities:

   * Controller Layer
   * Service Layer
   * Repository Layer
   * Entity Layer

3. **Object-Oriented Architecture (OOP)**
   Implementation based on SOLID principles, encapsulation, inheritance, and polymorphism.

4. **Data-Oriented Architecture**
   Structured data persistence using JPA/Hibernate and PostgreSQL.

---

## Security

* JWT-based authentication
* Role-Based Access Control (RBAC)
* Password encryption using **BCrypt**
* Secured endpoints with Spring Security

---

## Requirements

* JDK 17+
* Maven 3.8+
* PostgreSQL 14+
* Docker (optional)

---

## Running the Application

### Development

```bash
mvn spring-boot:run
```

### Production

```bash
mvn clean package
java -jar target/vetclinic-backend.jar
```

---

## API Documentation

Swagger UI available at:

```
http://localhost:8080/swagger-ui.html
```

---

## Branching Strategy

* `main` → Stable production branch
* `develop` → Development integration branch
* `feature/*` → Feature implementation branches

---

**Version:** 1.0.0

**Main Technology:** Spring Boot 3

**Project Type:** Enterprise REST API

---
