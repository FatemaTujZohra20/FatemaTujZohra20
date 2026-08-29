<h1 align="center">Hi, I'm Most. Fatema Tuj Zohra</h1>
 
<p align="center">
  <strong>Java Backend Developer — Spring Boot · REST APIs · Microservices</strong><br>
  API Design · JPA/Hibernate Modeling · Test-Driven Development<br>
  📍 Rajshahi, Bangladesh · Open to Backend Java roles (BD / EU / remote)
</p>
<p align="center">
  I design and build production-grade REST APIs with Spring Boot.<br>
  Comfortable across the full backend lifecycle — JPA/Hibernate modeling, Spring Security,<br>
  validation, exception handling, structured logging, and Docker.<br>
  Currently building toward a Backend Java Developer role on a strong engineering team.
</p>

---

## Featured Projects

### [E-Commerce Backend Platform](https://github.com/FatemaTujZohra20/E-Commerce-Backend-Platform-Java_SpringBoot_Ostad_Batch03_Module22_Assignment)

Full commerce backend with filtered search via JPA Specifications and pagination across products and categories. Built a Levenshtein-distance cart suggestion engine and a coupon system with per-code percentage caps, plus an end-to-end Stripe payment flow with SMTP order confirmations on successful payment. Migrated destructive `DELETE` endpoints to a **soft-delete pattern preserving full auditability.**
`Spring Boot` `Spring Data JPA` `PostgreSQL` `Stripe` `SMTP` `Docker`

### [AI CV Evaluator](https://github.com/FatemaTujZohra20/AI-CV-Evaluator-Java_SpringBoot_Ostad_Batch03_Module24_Assignment)

Spring Boot REST API that scores CV image uploads across five hiring dimensions using Spring AI's multimodal `ChatClient` (Google Gemini), returning structured 0–100 JSON. Architected the prompt pipeline against `spring-ai-client-chat` so the provider is **swappable to OpenAI or Anthropic by changing a single starter dependency** — vendor flexibility that matters under corporate AI procurement and compliance review.
`Spring Boot` `Spring AI` `Multimodal ChatClient` `Google Gemini` `REST`

### [Weather Information Service](https://github.com/FatemaTujZohra20/Weather_Information_Service_Java_SpringBoot_Ostad_Batch03_Module28_Assignment)

Single `GET /api/weather?city={city}` endpoint returning latitude, longitude, temperature, wind speed and humidity as structured JSON from WeatherAPI. A **1-minute PostgreSQL freshness cache serves repeat requests from storage instead of re-calling the upstream API**, cutting third-party call volume. API keys loaded through environment-based configuration — never hard-coded, never committed.
`Spring Boot` `PostgreSQL` `Caching` `WeatherAPI` `Externalized Config`

### [Inventory Management API](https://github.com/FatemaTujZohra20/Inventory_Management_API_Java_SpringBoot_Ostad_Batch03_Module27_Assignment)

CRUD endpoints for product creation and retrieval with bean-validated inputs on every request. Stock in/out operations write a **persisted stock-change history**, with a zero-floor quantity constraint enforced at the service layer rather than the database — the stock-consistency and audit-trail discipline required in inventory, billing and financial-ledger systems.
`Spring Boot` `Spring Data JPA` `PostgreSQL` `Bean Validation`

### [Product Inventory API — Error Contract Discipline](https://github.com/FatemaTujZohra20/Product-Inventory-API-Java_SpringBoot_Ostad_Batch03_Module14_Assignment)

Production-style REST service built around a clean error contract: bean validation, custom domain exceptions, and a `@RestControllerAdvice` global handler returning correct **400 / 404 / 409** semantics. Disciplined `DEBUG / INFO / WARN / ERROR` logging via SLF4J throughout — the kind of stable contract that keeps downstream consumers' integrations from breaking.
`Spring Boot` `@RestControllerAdvice` `Bean Validation` `SLF4J`

### [Secure Note-Taking API](https://github.com/FatemaTujZohra20/Secure-Note-Taking-Application-Java_SpringBoot_Ostad_Batch03_Module15_Assignment)

Spring Security HTTP Basic authentication backed by a database user store, with **role-based access control (`USER`, `ADMIN`) enforced at the endpoint level** — the access-control foundation behind every multi-tenant SaaS and internal tool.
`Spring Boot` `Spring Security` `RBAC` `PostgreSQL`

### [Warehouse Management — Test Coverage](https://github.com/FatemaTujZohra20/Warehouse-Management--Java_SpringBoot_Ostad_Batch03_Module16_Assignment)

Service-layer unit tests with Mockito and controller integration tests with `@WebMvcTest`, **covering both happy-path and error scenarios** rather than only the paths that pass. Written to catch regressions before they reach production.
`JUnit 5` `Mockito` `MockMvc` `@WebMvcTest` `Spring Boot Test`

---

## 🧠 Skills & Expertise

| Domain | Technologies |
| --- | --- |
| **Languages** | Java, SQL, Python |
| **Backend Frameworks** | Spring Boot, Spring Data JPA (Hibernate), Spring Security, Spring AI |
| **API Design** | REST, Swagger / OpenAPI, bean validation, `@RestControllerAdvice` error contracts, pagination & filtering (JPA Specifications) |
| **Databases** | PostgreSQL, H2, JPA/Hibernate entity modeling, soft-delete & audit patterns |
| **Testing** | JUnit 5, Mockito, MockMvc, `@WebMvcTest`, service-layer unit testing, controller integration testing |
| **Containers & Build** | Docker, Docker Compose, Maven, Gradle |
| **Security** | Spring Security (HTTP Basic), role-based access control, environment-based secrets management |
| **Integrations** | Stripe (payments, webhooks), SMTP / JavaMail, Google Gemini via Spring AI, third-party REST APIs with caching |
| **Practices** | Structured logging (SLF4J), exception handling strategy, Git version control |
| **Spoken Languages** | Bengali (native), English (fluent) |

---

## 🛠 Tech Stack

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-%236DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-%2359666C.svg?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit5-%2325A162.svg?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-%2378A641.svg?style=for-the-badge&logo=&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-%23C71A36.svg?style=for-the-badge&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-%2302303A.svg?style=for-the-badge&logo=gradle&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-%23635BFF.svg?style=for-the-badge&logo=stripe&logoColor=white)
![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)

---

## 📊 What I'm Currently Working On

- Building production-grade **Spring Boot REST APIs** with clean error contracts and full validation coverage
- Deepening **JPA / Hibernate** modeling — Specifications, projections, and query performance
- Extending **test coverage** with JUnit 5, Mockito and `@WebMvcTest` across service and controller layers
- Containerizing services with **Docker Compose** for reproducible local and deployment environments

---

## 🌱 Learning & Improving

- **Microservices patterns** — service decomposition, inter-service communication, resilience with Resilience4j
- **Spring Cloud** — config server, service discovery, API gateway
- **Caching & performance** — Redis, query optimization, and connection-pool tuning
- **CI/CD** — GitHub Actions pipelines for automated build, test and image publishing

---

## 🎓 Certifications

- **[Backend Web Development with Java & Spring Boot](https://ostad.app/share/certificate/c45999-most.-fatema-tuj-zohra)** — Ostad · Nov 2025 – Jul 2026 · [Final Score **97.3%**](https://ostad.app/share/certificate/c46000-most.-fatema-tuj-zohra)
- **[Introduction to Software Engineering](https://www.coursera.org/account/accomplishments/verify/BINSM21OJTX6)** — IBM (Coursera) · Final Score **100%** · May 2026
- **[Java Programming for Beginners](https://www.coursera.org/account/accomplishments/verify/W4I1LETN2HM8)** — IBM (Coursera) · Final Score **100%** · Jul 2026
- **[Object-Oriented Programming in Java](https://www.coursera.org/account/accomplishments/verify/UCOFCS1C46YL)** — IBM (Coursera) · Final Score **100%** · Aug 2026

---

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ftzohra0x1)
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/FatemaTujZohra20)
[![Email](https://img.shields.io/badge/Email-fatematujzohra20%40gmail.com-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fatematujzohra20@gmail.com)

---

*"Validate the input. Handle the exception. Test the failure path."*
