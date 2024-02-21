# Project Name: EduPulse: Capturing the Beat of Student Opinions

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)

## Overview
The Student Survey Application is a microservices-based web application designed for managing student survey data. It features CRUD operations, containerization using Docker, and deployment on Kubernetes. The application is built using Spring Boot, RESTful Web Services, and JPA/Hibernate, with data stored in Amazon RDS for MySQL.

## Features
- CRUD Operations: Create, Read, Update, and Delete survey data.
- Database Management: Utilizes Amazon RDS for MySQL.
- Containerization: Docker support for consistent deployment.
- Deployment: Automated deployment on Kubernetes through a CI/CD pipeline.

## Technologies Used
- Spring Boot
- RESTful Web Services
- JPA/Hibernate
- Docker
- Kubernetes
- Amazon RDS for MySQL
- Postman (for testing)

## Getting Started

### Prerequisites
- Docker
- Kubernetes
- Java 11
- Maven

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-survey-application.git
2. Navigate to the project directory:
   ```bash
   cd student-survey-application
3. Build the project:
   ```bash
   mvn clean install
   
## Usage
1. Run the application using Docker Compose:
   ```bash
   docker-compose up

Access the application at http://localhost:8080.

## Testing
Use Postman to test the RESTful services. Import the provided Postman collection and execute various requests to validate CRUD operations.

## Deployment
The application is deployed on Kubernetes using a CI/CD pipeline. Ensure that your Kubernetes cluster is set up and configure the pipeline to automate the deployment process.

## Contributing
Contributions are welcome! Please read the CONTRIBUTING.md for guidelines on how to contribute to this project.
