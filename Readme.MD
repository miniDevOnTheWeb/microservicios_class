📚 TEMARIO COMPLETO DE MICROservicios (JAVA – NIVEL PROFESIONAL)

Este temario no deja huecos. Si completas TODO, sabes microservicios.

🔹 MÓDULO 1 – Fundamentos REALES de Microservicios

(arquitectura, no código aún)

¿Por qué NO usar microservicios?

Cuándo SÍ usar microservicios

Diferencias reales:

Monolito vs Monolito modular vs Microservicios

Principios clave:

Single Responsibility Service

Independencia de despliegue

Aislamiento de fallos

Domain-Driven Design (DDD) aplicado a microservicios

Bounded Context

Aggregate

Context Mapping

Anti-patrones comunes

Shared Database

Chatty Services

God Service

🔹 MÓDULO 2 – Diseño de Microservicios

(antes de escribir código)

Cómo dividir un sistema en microservicios

Definir contratos (API First)

Versionado de APIs

Estrategias de comunicación

Sincronía vs Asincronía

Consistencia eventual

Estrategias de resiliencia

Idempotencia

🔹 MÓDULO 3 – Comunicación entre Microservicios

(núcleo del sistema)

Comunicación REST vs Eventos

REST entre microservicios

OpenFeign

Service Discovery (Eureka / Consul)

Load Balancing

Circuit Breaker (Resilience4j)

Retries y Timeouts

Fallbacks

Event-Driven Architecture

Kafka / RabbitMQ

Pub/Sub

Sagas (coreografía vs orquestación)

🔹 MÓDULO 4 – Configuración Centralizada

(clave para producción)

Spring Cloud Config Server

Configuración por entorno

Secrets management

Refresh dinámico de configuración

Profiles en microservicios

🔹 MÓDULO 5 – API Gateway

(puerta de entrada real)

¿Por qué NO exponer microservicios directamente?

API Gateway Pattern

Spring Cloud Gateway

Routing dinámico

Filtros (pre/post)

Rate Limiting

CORS

Autenticación centralizada

🔹 MÓDULO 6 – Seguridad en Microservicios

(nivel empresa)

Autenticación vs Autorización

JWT en arquitectura distribuida

OAuth2 / OpenID Connect

Auth Server (Keycloak / Spring Authorization Server)

Seguridad entre microservicios (service-to-service)

Cookies httpOnly vs Authorization header

Propagación de identidad

Zero Trust Architecture

🔹 MÓDULO 7 – Persistencia y Bases de Datos

(uno de los errores más comunes)

Database per Service

Anti-patrón: Shared DB

Transacciones distribuidas

Eventual Consistency

CQRS

Read Models

Cache distribuido (Redis)

Migraciones de base de datos

🔹 MÓDULO 8 – Observabilidad

(imprescindible)

Logging distribuido

Correlation ID

Distributed Tracing

OpenTelemetry

Zipkin / Jaeger

Metrics (Micrometer)

Prometheus + Grafana

Health Checks

🔹 MÓDULO 9 – Contenedores

(donde todo se vuelve real)

Docker para microservicios

Dockerfile por servicio

Docker Compose

Networking entre contenedores

Variables de entorno

Build optimizado de imágenes

🔹 MÓDULO 10 – Orquestación

(nivel producción real)

¿Por qué Kubernetes?

Pods

Services

ConfigMaps

Secrets

Deployments

Ingress

Escalado horizontal

Rolling Updates

Auto-healing

🔹 MÓDULO 11 – Despliegue

(CI/CD)

Entornos (dev, staging, prod)

Pipelines CI/CD

GitHub Actions

Build + Test + Deploy

Versionado de microservicios

Blue-Green / Canary Deployment

🔹 MÓDULO 12 – Integración con Frontend

(lo que pediste explícitamente)

Arquitectura Frontend + Microservicios

Frontend → API Gateway → Microservicios

Manejo de CORS

Autenticación desde frontend

Refresh Token Flow

Errores distribuidos

Performance en frontend

BFF (Backend for Frontend)

🔹 MÓDULO 13 – Proyecto Final REAL

(todo conectado)

Arquitectura completa

Microservicio de Auth

Microservicio de Usuarios

Microservicio de Productos

Microservicio de Órdenes

API Gateway

Config Server

Service Discovery

Frontend consumiendo microservicios