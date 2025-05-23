# Quiz App

A scalable Quiz Application built with **Java**, **Spring Boot**, and **Microservices** architecture.

---

## Features

- Designed and implemented RESTful APIs for core quiz functionalities using Microservices.
- Utilized **Feign Client** to enable seamless communication between the Question Service and Quiz Service.
- Integrated **Eureka Server** for dynamic service discovery and registration, improving fault tolerance and scalability.

---

## Architecture

The app follows a microservices architecture comprising:

- **Quiz Service**: Manages quizzes, quiz creation, and quiz-related operations.
- **Question Service**: Handles question management for quizzes.
- **Eureka Server**: Acts as a service registry to allow services to discover and communicate with each other dynamically.

---

## Technologies Used

- Java 
- Spring Boot
- Spring Cloud Netflix Eureka
- Spring Cloud OpenFeign
- Maven/Gradle (build tool)
- REST APIs

---

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven or Gradle
- Docker (optional, for containerization)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/quiz-app.git
   cd quiz-app
