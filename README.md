# QuizVerse – Microservices Architecture

QuizVerse is a Spring Boot based Quiz Application built using Microservices Architecture.

## 🏗 Architecture

This project is split into the following services:

- 🔹 Question Service  
  [QuizVerse/quiz-question-service](https://github.com/NiranjanS8/quiz-question-service)

- 🔹 Quiz Service  
  [QuizVerse/quiz-quiz-service](https://github.com/NiranjanS8/quiz-quiz-service)

- 🔹 API Gateway  
  QuizVerse/quiz-api-gateway

- 🔹 Service Registry (Eureka)  
  [QuizVerse/quiz-service-registry](https://github.com/NiranjanS8/quiz-service-registry)

- 🔹 Config Server  
  QuizVerse/quiz-config-server

---
## 🔄 System Architecture

![Architecture](./architecture.png)

---

## 🔧 Tech Stack

- Spring Boot
- Spring Cloud
- Eureka
- OpenFeign
- API Gateway
- MySQL

---

## 🚀 Features

- Quiz creation
- Question management
- Service-to-service communication
- Centralized configuration
- Service discovery
