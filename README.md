# Elker Bonandi

**Full Stack Software Engineer — .NET · Angular** · Lisbon, Portugal

[![LinkedIn](https://img.shields.io/badge/LinkedIn-elker--bonandi-0A66C2?logo=linkedin)](https://www.linkedin.com/in/elker-bonandi/)
[![Email](https://img.shields.io/badge/Email-elkerbonandi%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:elkerbonandi@gmail.com)

I build and maintain software with C#, ASP.NET Core and Angular, with a focus on
security, clean architecture and automated quality gates. Since 2023 I have been developing a
multi-tenant treasury system for a real non-profit with multiple churches in Portugal.
Before software, I spent 10+ years in operations, HR and commercial management — which is why I
care about software that real people depend on.

---

## Featured work

### [ICM Solution](https://github.com/Bonandi22/icm-solution-showcase) — multi-tenant treasury & membership platform
`.NET 10` `ASP.NET Core` `Angular 22` `YARP` `RabbitMQ` `SQL Server` `Docker` `GitHub Actions`

Treasury and membership management for Igreja Cristã Maranata (Portugal), designed for real member and
financial data across multiple churches.

- **5 microservices** (Clean Architecture) behind a **YARP API Gateway** with rate limiting
- **Security**: JWT in HttpOnly cookies, Argon2id password hashing, hashed refresh tokens,
  per-church data isolation enforced server-side, protection against mass assignment
- **RBAC** with 7 organisational roles mapped to granular endpoint permissions
- **CI/CD**: every merge builds, tests and publishes 7 Docker images to GHCR, with a fail-closed
  dependency audit gate
- Recent work: Angular upgrade to v22, dependency vulnerabilities reduced from 20 to 0,
  WCAG 2.2 accessibility fixes

> The source repository is private because the system is designed for real member and financial data.
> Architecture, security design and code excerpts: **[icm-solution-showcase](https://github.com/Bonandi22/icm-solution-showcase)**.
> I am happy to walk through the full codebase in an interview.

### [Academia .NET](https://github.com/Bonandi22/academia-dotnet-app) — interview-prep learning platform
`ASP.NET Core 8` `Angular` `SQL Server` `JWT` `Modular monolith`

Study modules, quizzes and flashcards for Full Stack/.NET interviews, with user accounts and
progress synced to the API.

### [Bíblia Teológica](https://github.com/Bonandi22/biblia-teologica) — Bible study portal
`.NET 8` `Clean Architecture` `Angular 22` `SQLite` `Docker Compose` `CI/CD`

Each of the 66 books in context: author, audience, history, prophecies — editorial content served
by an ASP.NET Core API, with authentication and an admin area.

### [Fishing Legends](https://github.com/Bonandi22/fishing-legends) — full-stack 3D game
`React` `Three.js` `TypeScript` `Fastify` `PostgreSQL`

3D fishing game where the backend is the authority over identity, progress and economy:
versioned, transactional and idempotent API. Built to explore a stack beyond .NET.

---

## How I work

I follow an engineering standard I wrote for my own projects: architecture decisions recorded as
ADRs, nullable reference types with no new warnings, a failing test before every bug fix, dependency and vulnerability audits in
CI, and nothing merged without green builds.

## Tech

**Backend:** C#, ASP.NET Core, EF Core, REST, RabbitMQ, YARP · **Frontend:** Angular, TypeScript,
RxJS · **Data:** SQL Server, PostgreSQL, MySQL, SQLite · **Testing:** xUnit, Moq,
FluentAssertions · **DevOps:** Docker, GitHub Actions, Azure DevOps · **Architecture:** Clean
Architecture, DDD, modular monolith, microservices

## Background

Full Stack Development (C# & ASP.NET Core) — Assembly School, Lisbon · Bachelor's in Business
Administration — São Camilo, Brazil · Portuguese (native), English (B2)
