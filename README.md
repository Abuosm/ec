# Spring Boot React E-Commerce Application

## Overview

A full-stack e-commerce application built using **Spring Boot Microservices**, **React.js**, **MySQL**, **Redis**, and **Docker**. The project follows a microservices architecture where each service is containerized using Docker, making development and deployment easier and more scalable.

---

## Tech Stack

### Backend

* Java 11
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL 8
* Redis
* Maven

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Bootstrap

### DevOps

* Docker
* Docker Compose

---

## Microservices

* Authentication Service
* Common Data Service
* Payment Service
* Search Suggestion Service
* React UI

---

## Features

* User Authentication
* Product Management
* Brand & Category Management
* Search Suggestions
* Payment Service Integration
* Redis Caching
* REST APIs
* Dockerized Microservices Architecture

---

## Docker Containers

| Service                   | Port  |
| ------------------------- | ----- |
| React UI                  | 3000  |
| Authentication Service    | 7000  |
| Common Data Service       | 9000  |
| Payment Service           | 9050  |
| Search Suggestion Service | 10000 |
| MySQL                     | 3306  |
| Redis                     | 6379  |

---

## Project Structure

```
spring-boot-react-ecommerce-app/
│
├── client/
├── server/
│   ├── authentication-service/
│   ├── common-data-service/
│   ├── payment-service/
│   └── search-suggestion-service/
│
├── docker-compose.yml
└── README.md
```

---

## Running the Project

### Clone the Repository

```bash
git clone https://github.com/Abuosm/ec.git
cd ec
```

### Start with Docker

```bash
docker compose up --build
```

After the containers start:

* React UI: http://localhost:3000
* Authentication Service: http://localhost:7000
* Common Data Service: http://localhost:9000
* Payment Service: http://localhost:9050
* Search Suggestion Service: http://localhost:10000

---

## Current Project Status

🚧 **Work in Progress**

The core application is successfully running using Docker.

### Completed

* Dockerized Spring Boot Microservices
* React Frontend
* MySQL Integration
* Redis Integration
* REST APIs
* Docker Compose Configuration
* Service Communication

### Currently Working On

* Migrating product image assets from the original project.
* Replacing broken external image URLs.
* Improving deployment workflow.
* Preparing the application for production deployment.

> **Note:** Some product and carousel images may not load because the original project depends on external image URLs that are no longer available. These assets are currently being migrated.

---

## Learning Outcomes

This project helped me gain practical experience with:

* Spring Boot Microservices
* REST API Development
* React Frontend Integration
* Docker & Docker Compose
* MySQL Database Management
* Redis Caching
* Maven Build Process
* Containerized Application Deployment

---

## Future Improvements

* Host images using a personal Cloudinary account or another image hosting service.
* Deploy backend microservices to the cloud.
* Deploy React frontend.
* Add CI/CD pipeline.
* Improve UI/UX.
* Add API documentation.

---

## Author

**Abubaker Osman**

GitHub: https://github.com/Abuosm
