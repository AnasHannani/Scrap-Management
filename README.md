# Scrap-Management

## Scrap Management - Frontend

## Scrap Management API - Backend

![Java](https://img.shields.io/badge/Java-17-blue.svg)![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3.1-brightgreen.svg)![Maven](https://img.shields.io/badge/Build-Maven-C71A36?logo=apache-maven&logoColor=white)![Security](https://img.shields.io/badge/Security-Spring%20Security%20%26%20JWT-red.svg)![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

This is the backend REST API for the Scrap Management application. It is a robust, secure, and well-structured application built with Java and the Spring Boot framework. It provides a complete set of endpoints for managing the entire scrap lifecycle, from user authentication to scrap list creation, validation workflows, and reporting.

## ✨ Features

-   **Authentication:** Secure, token-based authentication using JWT (JSON Web Tokens). Supports both username/password and worker barcode login.
-   **Role-Based Access Control (RBAC):** Endpoints are protected based on user roles (e.g., ADMIN, WORKER, TEAM_LEADER) using Spring Security.
-   **Scrap List Management:** Full CRUD operations for scrap lists with a multi-step validation workflow (Draft -> Submitted -> Validated/Rejected).
-   **Core Data Management:** APIs for managing essential entities like Components, Work Zones, and Scrap Motifs.
-   **Report Generation:** Dynamically generates PDF reports auditing purposes.
-   **Email Notifications:** Integrated email service with Thymeleaf templating to notify users of important events.
-   **API Documentation:** Self-generating, interactive API documentation via Swagger/OpenAPI.

## 🛠️ Technology Stack

-   **Framework:** [Spring Boot 3.3.1](https://spring.io/projects/spring-boot)
-   **Language:** [Java 17](https://www.oracle.com/java/technologies/javase/17-archive-downloads.html)
-   **Persistence:** [Spring Data JPA / Hibernate](https://spring.io/projects/spring-data-jpa)
-   **Database Support:** [PostgreSQL](https://www.postgresql.org/) / [H2](https://www.h2database.com/html/main.html)
-   **Security:** [Spring Security 6](https://spring.io/projects/spring-security)
-   **Authentication:** [JJWT 0.11.5](https://github.com/jwtk/jjwt)
-   **API Documentation:** [Springdoc OpenAPI 2.5.0](https://springdoc.org/)
-   **Email Templating:** [Thymeleaf](https://www.thymeleaf.org/)
-   **Reporting & Charting:**
    -   PDF: [iText 9.2.0](https://itextpdf.com/)
-   **Utilities:**
    -   [Lombok](https://projectlombok.org/): Reduces boilerplate code.
-   **Build Tool:** [Apache Maven](https://maven.apache.org/)

## 🚀 Getting Started

Follow these instructions to get the backend server up and running on your local machine.

### Prerequisites

-   **Java Development Kit (JDK) 17 or higher**
-   **Apache Maven**
-   A running **database instance** (e.g., PostgreSQL).
-   An **email server** (e.g., a local MailHog instance).
