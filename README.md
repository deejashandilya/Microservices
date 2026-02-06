* * * * *

Microservices-Based Task Management System
==========================================

A robust, scalable distributed system built using the **Spring Cloud** ecosystem. This project demonstrates the implementation of a microservices architecture to handle user management and task orchestration with high availability and centralized configuration.

🏗️ Architecture Overview
-------------------------

The project is divided into several specialized services:

-   **Discovery Server (Eureka):** Acts as a service registry for dynamic service discovery.

-   **API Gateway:** The single entry point for all clients, handling request routing and security.

-   **User Service:** Manages user profiles, authentication, and authorization.

-   **Task Service:** Handles the core business logic for task creation, tracking, and status management.

🚀 Tech Stack
-------------

-   **Backend:** Java 17+, Spring Boot 3.x

-   **Microservices:** Spring Cloud Netflix Eureka, Spring Cloud Gateway

-   **Security:** Spring Security, JWT (JSON Web Tokens)

-   **Database:** Spring Data JPA (PostgreSQL/MySQL/H2)

-   **Communication:** Feign Clients (Synchronous) / RestTemplate

-   **Build Tool:** Maven

📋 Key Features
---------------

-   **Service Registration & Discovery:** Automatic registration of microservices with Eureka.

-   **Centralized Routing:** Unified API management via Spring Cloud Gateway.

-   **Inter-Service Communication:** Seamless data exchange between `TaskService` and `UserService` using OpenFeign.

-   **Distributed Logging:** Track requests across multiple service boundaries.

🛠️ Getting Started
-------------------

### Prerequisites

-   JDK 17 or higher

-   Maven 3.6+

-   Your preferred IDE (IntelliJ IDEA, Eclipse, or VS Code)
