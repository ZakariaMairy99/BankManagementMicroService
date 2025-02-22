# Bank Management Full-Stack MicroService Application 
# Project Overview
This project is a microservices-based application using Spring Boot for the backend and Angular for the frontend. It efficiently manages accounts and customers, focusing on modularity, scalability, and maintainability. Each service is containerized with Docker, and Eureka Server is used for service discovery. The application also leverages Swagger for API documentation and Bootstrap for enhancing the user interface.

## Technologies Used
### Backend
- **Spring Boot 3**: Framework for building RESTful APIs.
- **Spring Cloud Eureka**: Service discovery for communication between microservices.
- **Spring Cloud Gateway**: API gateway service for routing requests.
- **Spring Cloud Config Server**: Centralized configuration management for microservices.
- **Swagger**: Automatic API documentation tool.
- **Spring Data JPA (Hibernate)**: Framework for data persistence.

### Frontend
- **Angular 14+**: Frontend framework for creating reactive and dynamic user interfaces.
- **Bootstrap CSS**: Framework for responsive design.
- **TypeScript**: Language used for frontend logic.

### DevOps and Containerization
- **Docker**: Containerization of services for simplified deployment.
- **Nginx**: Web server for serving the Angular application.

### Development Tools
- **IntelliJ IDEA**: IDE for backend development.
- **Postman**: API testing tool.
- **npm**: Package manager for JavaScript dependencies.
- **Docker Compose**: Tool for orchestrating Docker containers.

## Project Architecture
1. **Frontend**: Angular serves as the dynamic and responsive user interface.
2. **Backend**: Spring Boot microservices handle accounts and customer management.
3. **Service Discovery**: Eureka Server registers and discovers services dynamically.
4. **Gateway**: Spring Cloud Gateway manages API routing.
5. **Config Server**: Centralized configuration management for all microservices.

## Features
- **Account and Customer Management**: CRUD operations for accounts and customers.
- **Service Discovery**: Eureka enables dynamic registration and discovery of services.
- **API Documentation**: Swagger generates interactive API documentation.
- **Responsive UI**: Angular and Bootstrap provide a smooth user experience.
- **Containerization**: Docker ensures seamless service deployment.

## Screenshots
### Docker Images
![Docker Interface](images/docker.png)
### Eureka Services
![Eureka Server Interface](images/eureka.png)
### Swagger Documentation
![Swagger Interface](images/swagger.png)
### Accounts Interface
![Accounts Interface](images/accounts.png)
### Customers Interface
![Customers Interface](images/customers.png)

## License
This project is licensed under ZMairy License - see the LICENSE file for details.
Let me know if you need any adjustments!

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/ZakariaMairy99/BankManagementMicroService/tree/main
