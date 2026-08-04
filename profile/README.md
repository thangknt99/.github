# Open Enterprise Architecture Core

> A modern, production-grade modular architecture & microservices foundation designed to accelerate .NET 8, Node.js, and multi-tenant cloud application development.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![.NET 8](https://img.shields.io/badge/.NET-8.0-purple.svg)](https://dotnet.microsoft.com/)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green.svg)](https://nodejs.org/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)

---

## 📌 Ecosystem Purpose & Impact

Modern enterprise developers spend hundreds of hours re-implementing core infrastructure logic: multi-tenant security contexts, authentication pipelines, dynamic database query optimization, and architectural decoupling.

**Open Enterprise Architecture Core** serves as a lightweight, open-source boilerplate and reference framework. It bridges the gap between complex enterprise standards (DDD, CQRS) and real-world microservices integration across **.NET Core**, **Node.js**, and **PHP** ecosystems.

### Core Architecture Highlights
* **Clean Architecture & CQRS:** Built using MediatR command/query handlers for strict boundary enforcement and clean maintainability.
* **Multi-Tenant Isolation:** Dynamic resolution of client identity, localized data contexts, and fine-grained claim-based authorization.
* **Identity & Security Integration:** Centralized OIDC/OAuth2 protocols, secure token workflows, and cross-platform cryptography utilities.
* **High-Performance Persistence:** Optimized data pipelines balancing Entity Framework Core for rich domains and Dapper for high-concurrency read scenarios.
* **Modular Integration Patterns:** Ready-to-use API gateway setups for connecting front-end interfaces, mobile applications, and background consumers.

---

## 🛠 Tech Stack & Tools

| Component | Technology |
| :--- | :--- |
| **Backend Core** | .NET 8 / C#, ASP.NET Core Web API |
| **Microservices & Web** | Node.js (Express), PHP utilities |
| **Authentication** | OpenID Connect, OAuth 2.0, JWT, AES/Bcrypt |
| **Database & ORM** | PostgreSQL, SQL Server, Entity Framework Core, Dapper |
| **Patterns** | CQRS (MediatR), Domain-Driven Design (DDD), Repository Pattern |
| **Testing** | xUnit, Moq, EF Core In-Memory Provider |
| **DevOps & Security** | Docker, GitHub Actions, Dependabot |

---

## 🚀 Quick Start Guide

### Prerequisites
* [.NET 8.0 SDK](https://dotnet.microsoft.com/download)
* [Node.js 18+](https://nodejs.org/)
* [Docker Desktop](https://www.docker.com/products/docker-desktop/) *(Optional for local database containers)*

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
   cd your-repo-name
