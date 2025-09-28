# Ticket Booking Systmem

# API Gateway Application

## Overview
This is a Spring Boot-based API Gateway application designed for a microservices architecture. It serves as a secure, resilient, and well-documented entry point, leveraging Spring Cloud Gateway for routing, Springdoc OpenAPI for API documentation, Resilience4j for circuit breaking, OAuth2 for secure resource access, and Spring Kafka for messaging. The application includes health monitoring via Spring Boot Actuator and comprehensive testing support. This project is part of a Spring Boot microservices course.

## Features
- **API Gateway**: Routes incoming requests to downstream microservices using Spring Cloud Gateway.
- **API Documentation**: Generates interactive API documentation with Swagger UI via Springdoc OpenAPI.
- **Circuit Breaker**: Implements fault tolerance using Resilience4j to handle service failures gracefully.
- **Security**: Secures endpoints with OAuth2 resource server support for authentication and authorization.
- **Messaging**: Integrates with Kafka for asynchronous messaging using Spring Kafka.
- **Monitoring**: Provides health and metrics endpoints via Spring Boot Actuator.
- **Testing**: Includes Spring Boot Starter Test for unit and integration testing.

## Prerequisites
- **Java**: 21 (as specified in `pom.xml`)
- **Maven**: 3.8.x or later
- **Kafka**: A running Kafka broker (e.g., version 3.x) and Zookeeper for messaging
- **IDE**: IntelliJ IDEA, Eclipse, or any IDE with Spring Boot support
- **Dependencies**: Managed via Maven (see `pom.xml` below)

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/apigateway.git
   cd apigateway
2. Build the project:
   ```bash
   mvn clean install
3. Run the application:
   ```bash
   mvn spring-boot:run
