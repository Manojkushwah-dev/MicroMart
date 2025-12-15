
# MicroMart - Complete Industry-Grade Microservices Project

## Services Included
- Eureka Server
- API Gateway
- Auth Service (JWT ready)
- Product Service (Redis caching ready)
- Order Service (Kafka producer ready)
- Inventory Service (Kafka consumer ready)
- Payment Service (Kafka consumer ready, Resilience4j hooks)
- Notification Service (Kafka consumer ready)
- Docker Compose for full stack
- Swagger ready
- ELK stack for logging and monitoring

## How to Run
1. Install Docker & Docker Compose
2. Build & Run:
```
docker-compose up --build
```
3. Access Services:
- Eureka Dashboard: http://localhost:8761
- API Gateway: http://localhost:8080
- Swagger UI: http://localhost:8080/swagger-ui.html

## Notes
- JWT security implemented in Auth and Gateway
- Kafka topics: order-topic, payment-topic
- Redis caching ready in Product Service
- Resilience4j circuit breaker hooks ready
- ELK stack logs all services

## GitHub Ready
- Include this README
- Include .gitignore
- Each service is modular for CI/CD pipelines
