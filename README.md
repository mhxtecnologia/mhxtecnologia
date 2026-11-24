# Hi, I'm Matheus Takeuchi 👋

**Senior Full Stack Developer** with 11+ years building web, backend and mobile products —
from the database schema to the pixel on the screen.

I work mostly with **TypeScript** (React, Next.js, Node.js, NestJS) and **Rust**, and I care about
clean architecture, automated tests, security by default and software that is easy to run.

🌐 Résumé: [mhxtecnologia.github.io](https://mhxtecnologia.github.io)

## Tech stack

| Area | Tools |
|---|---|
| **Frontend** | React · Next.js · Redux · Tailwind CSS · Vitest · Testing Library |
| **Backend** | Node.js · NestJS · Rust (Axum, Tokio) · REST · WebSocket · OpenAPI |
| **Data** | PostgreSQL · Prisma · sqlx · Redis · BullMQ |
| **Mobile** | Android · Kotlin · Jetpack Compose · Room |
| **DevOps** | Docker · GitHub Actions · Linux · Caddy · Nginx |
| **Practices** | Clean Architecture · SOLID · DDD · TDD · CI/CD |

## Portfolio

Every project below was written from scratch as a showcase: one-command setup,
real tests and a green CI pipeline.

| Project | What it shows | Stack | CI |
|---|---|---|---|
| [**recurring-billing-api**](https://github.com/mhxtecnologia/recurring-billing-api) | Subscription billing with Pix charges, background jobs and idempotent HMAC-signed webhooks | NestJS · PostgreSQL · Prisma · BullMQ | [![CI](https://github.com/mhxtecnologia/recurring-billing-api/actions/workflows/ci.yml/badge.svg)](https://github.com/mhxtecnologia/recurring-billing-api/actions/workflows/ci.yml) |
| [**solid-shop-api**](https://github.com/mhxtecnologia/solid-shop-api) | E-commerce backend in Clean Architecture: catalog, JWT auth and a cart with money in cents | NestJS · TypeScript · PostgreSQL · Docker | [![CI](https://github.com/mhxtecnologia/solid-shop-api/actions/workflows/ci.yml/badge.svg)](https://github.com/mhxtecnologia/solid-shop-api/actions/workflows/ci.yml) |
| [**solid-shop-web**](https://github.com/mhxtecnologia/solid-shop-web) | Storefront for Solid Shop with a BFF that keeps the token in an HttpOnly cookie | Next.js 15 · React · Redux · Vitest | [![CI](https://github.com/mhxtecnologia/solid-shop-web/actions/workflows/ci.yml/badge.svg)](https://github.com/mhxtecnologia/solid-shop-web/actions/workflows/ci.yml) |
| [**dupfind**](https://github.com/mhxtecnologia/dupfind) | Cross-platform CLI that finds duplicate files: size pre-filter, partial hash, then parallel BLAKE3; release binaries for Linux, Windows and macOS | Rust · rayon · BLAKE3 · clap | [![CI](https://github.com/mhxtecnologia/dupfind/actions/workflows/ci.yml/badge.svg)](https://github.com/mhxtecnologia/dupfind/actions/workflows/ci.yml) |
| [**axum-auth-service**](https://github.com/mhxtecnologia/axum-auth-service) | Authentication service: Argon2id passwords, Ed25519-signed JWTs published as JWKS, rotating refresh tokens with reuse detection and a Redis login rate limit | Rust · Axum · sqlx · PostgreSQL · Redis · OpenAPI | [![CI](https://github.com/mhxtecnologia/axum-auth-service/actions/workflows/ci.yml/badge.svg)](https://github.com/mhxtecnologia/axum-auth-service/actions/workflows/ci.yml) |
