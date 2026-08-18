# API Gateway

## Overview
Spring Cloud Gateway for microservices routing.

## Endpoints
- **Gateway Routes**: `http://localhost:8080/actuator/gateway/routes`
- **Health Check**: `http://localhost:8080/actuator/health`

## Configuration
- Port: 8080
- Service Discovery: Eureka Client
- Student Service Route: `/api/student/**` -> `lb://student-service`