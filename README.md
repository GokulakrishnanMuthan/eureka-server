# Eureka Server

Eureka Server is the **Service Registry** for the microservices architecture.  
It allows services like **Order Service**, **Product Service**, and **API Gateway** to register themselves and discover each other dynamically.

---

## 🚀 Features
- Centralized service registry using Netflix Eureka
- Enables service discovery for microservices
- Provides a dashboard to monitor registered services
- Works seamlessly with Spring Cloud Gateway

---

## 🛠️ Tech Stack
- **Java 17**
- **Spring Boot 3.x**
- **Spring Cloud Netflix Eureka Server**

---

## ⚙️ Configuration

### `application.properties`
```properties
spring.application.name=eureka-server
server.port=8761

# Eureka server configuration
eureka.client.register-with-eureka=false
eureka.client.fetch-registry=false
