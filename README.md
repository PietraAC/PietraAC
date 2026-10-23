# Heeeey, nice to meet you 👋

## About me

I'm a **Junior Software Developer** and Systems Analysis and Development student. I previously studied Computer Engineering at UTFPR. I like taking real-world problems, understanding what is actually getting in the way, and translating them into code, especially when an automated solution can save time and make someone's day a little easier.

When I'm away from the keyboard, I'm probably playing video games or solving a Rubik's Cube. Both scratch the same itch as programming: spotting patterns, trying new strategies, and enjoying that satisfying moment when everything clicks into place.

## Tech stack

<p align="left">
  <img alt="Java 21" src="https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="Spring Boot 3.5" src="https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img alt="Angular 22" src="https://img.shields.io/badge/Angular-22-DD0031?style=for-the-badge&logo=angular&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="Keycloak" src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white">
  <img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>

## What I'm working on

### [GymFlow](https://github.com/PietraAC/GymFlow) [![CI](https://github.com/PietraAC/GymFlow/actions/workflows/ci.yml/badge.svg)](https://github.com/PietraAC/GymFlow/actions/workflows/ci.yml)

A microservices portfolio project where gyms manage branches and equipment inventory, while students create workout plans restricted to exercises available at their selected branch.

The current version uses Java 21, Spring Boot, Angular, PostgreSQL, Flyway, Docker, Keycloak, and RabbitMQ. It also includes structured AI-assisted workout suggestions with human review, backend validation, and an event-driven inventory flow built with the transactional outbox pattern.

[![GymFlow dark-blue workout interface](https://raw.githubusercontent.com/PietraAC/GymFlow/main/docs/assets/gymflow-home-stage6.png)](https://github.com/PietraAC/GymFlow)

**Engineering highlights**

- Service-owned PostgreSQL databases and versioned Flyway migrations
- OAuth 2.0/OIDC with PKCE, audience validation, role isolation, and token-derived ownership
- Reviewable AI proposals with schema validation, expiration, idempotency, and authoritative eligibility checks
- RabbitMQ inventory events with a transactional outbox and idempotent consumer
- GitHub Actions covering backend integration tests, Angular tests/build, and an authenticated Playwright journey

[Explore the repository](https://github.com/PietraAC/GymFlow) · [Read the architecture](https://github.com/PietraAC/GymFlow/blob/main/docs/architecture.md) · [View CI](https://github.com/PietraAC/GymFlow/actions)

## What I care about

- Building software that is genuinely useful to someone
- Turning complicated problems into solutions people can understand
- Sharing what I learn and making tech knowledge easier to access
- Writing clear code and documentation that help others contribute
- Growing with the community through feedback, collaboration, and open projects

## Currently learning

- Event-driven architecture and transactional outbox patterns
- Resilient service-to-service communication
- Safe AI integrations with deterministic tests and human review
- Continuous integration and production-oriented observability

I'm always happy to exchange ideas, learn with other developers, and contribute to projects that can help the community. I'm also open to junior software development opportunities and collaborations.
