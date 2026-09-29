# Kapsa

Kapsa is a Personal Knowledge Management (PKM) system designed to organize notes, files, and personal knowledge through isolated vaults.

The project is being built from scratch as a production-oriented backend engineering project, applying modern software development practices including clean architecture, automated testing, security, containerization, and Linux deployment.

## Goals

Kapsa aims to provide a secure and extensible platform for:

- Managing personal knowledge through vaults.
- Creating and organizing hierarchical notes.
- Tagging and categorizing information.
- Managing images, PDFs, and other files.
- Providing secure authentication and authorization.
- Supporting multi-factor authentication.
- Exposing a documented REST API.

## Tech Stack

### Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA

### Data

- PostgreSQL
- Redis

### Object Storage

- MinIO
- AWS S3

### Infrastructure

- Docker
- Docker Compose
- Linux
- Nginx

### Testing & Documentation

- JUnit 5
- Mockito
- Testcontainers
- OpenAPI / Swagger UI

## Architecture

Kapsa will initially be implemented as a **modular monolith**.

The initial modules are expected to include:

- Identity & Access
- Knowledge Management
- File Storage
- Shared Infrastructure

Module boundaries will be kept explicit so that the system can evolve without introducing unnecessary distributed-system complexity.

## Project Status

**Under active development.**

The project is currently in its initial bootstrap and architecture phase.