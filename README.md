# VetClinic Pro – Backend API

Backend RESTful para el sistema integral de gestión de clínicas veterinarias.
Desarrollado con **Java 17 y Spring Boot 3**, siguiendo buenas prácticas de arquitectura y seguridad.

---

## Stack Tecnológico

* **Java 17**
* **Spring Boot 3**
* **Spring Security + JWT**
* **Spring Data JPA (Hibernate)**
* **PostgreSQL**
* **Maven**
* **Docker (opcional)**

---

## Arquitectura

El sistema está diseñado bajo los siguientes enfoques arquitectónicos:

1. **Arquitectura Cliente-Servidor**
   Comunicación mediante API REST entre cliente (frontend) y servidor backend.

2. **Arquitectura Multicapa (Layered Architecture)**
   Separación clara de responsabilidades:

   * Controller
   * Service
   * Repository
   * Entity

3. **Arquitectura Orientada a Objetos (OOP)**
   Aplicación de principios SOLID, encapsulamiento, herencia y polimorfismo.

4. **Arquitectura Orientada a Datos**
   Persistencia estructurada mediante JPA/Hibernate y PostgreSQL.

---

## Seguridad

* Autenticación basada en **JWT**
* Control de acceso por roles (RBAC)
* Encriptación de contraseñas con **BCrypt**
* Protección de endpoints con Spring Security

---

## Requisitos

* JDK 17+
* Maven 3.8+
* PostgreSQL 14+
* Docker (opcional)

---

## Ejecución

### Desarrollo

```bash
mvn spring-boot:run
```

### Producción

```bash
mvn clean package
java -jar target/vetclinic-backend.jar
```

---

## Documentación API

Swagger disponible en:

```
http://localhost:8080/swagger-ui.html
```

---

## Estrategia de Ramas

* `main` → Producción estable
* `develop` → Integración de desarrollo
* `feature/*` → Nuevas funcionalidades

---

**Versión:** 1.0.0
**Tecnología Principal:** Spring Boot 3
**Tipo de Proyecto:** API REST Empresarial

---
