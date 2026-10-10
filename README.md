# Lucas Paiva

**Senior software engineer in São Paulo. .NET and SQL at work, four products of my own after hours.**

I'm the tech lead at Plenaver (Grupo Évora), a platform in a regulated market where I work directly with banks and insurers. Outside of that I run a one-person studio, IDS, where I design, build and operate my own apps with a team of AI coding agents that I coordinate.

I've been programming for almost ten years, and I care most about the unglamorous parts: data models, query plans, offline sync, and evidence that the thing works.

## What I'm building

Four products, all unreleased, so the details stay private until launch.

| Area | Shape | Built with | Status |
|---|---|---|---|
| Language learning | Mobile app with an offline-first sync layer and a generated audio pipeline | Expo, React Native, Supabase, PostgreSQL, Cloudflare R2 | Internal testing |
| Health and family | Multi-app platform: API, background workers, web portal and two mobile apps | ASP.NET Core, PostgreSQL, React, Expo, OpenTelemetry, Docker | In development |
| Education | Mobile app with an AI feature behind a server-side proxy | Expo, React Native, Supabase | In development |
| Study and reference | Offline-first mobile reader with its own API | Expo, React Native, .NET 10, PostgreSQL 17, EF Core | In development |

Happy to walk through any of them in a conversation.

## How I work

- **Several agents, one conductor.** Claude Code, Codex and Gemini work in parallel, each in its own git worktree. One model coordinates, and a different model reviews before anything is merged.
- **Project memory lives in the repo.** Numbered decisions, current state and a glossary are versioned next to the code, so any agent or person can pick the work up.
- **The server is the authority.** Row-level security, secrets kept out of the client, paid access enforced on the backend, account export and deletion built in.
- **Nothing ships on trust.** Tests, type checks, database tests and immutable content releases that are read back after publishing. One of the four apps alone has close to 500 automated tests.

## At work

- **Plenaver (Grupo Évora), 2024 to now.** Senior engineer and tech lead. Made critical database workloads up to 99% faster through indexing, refactoring and materialization, automated report delivery end to end, and introduced structured logging and telemetry on Azure and AWS.
- **Before that.** A high-traffic authentication portal on microservices for São Paulo's Military Police, where server-side pagination and query tuning cut load time by 40%; a web app that replaced a Windows Forms system at a law firm; and an e-commerce backend.

## Stack

**Backend:** C#, ASP.NET Core, .NET 10, EF Core, SQL Server, PostgreSQL, Supabase  
**Front end and mobile:** TypeScript, React, Expo / React Native, Astro, Tailwind  
**Infrastructure:** Azure, AWS S3, Cloudflare, Docker, NGINX, GitHub Actions  
**Observability:** OpenTelemetry, Prometheus, Grafana, Jaeger  
**Payments:** Stripe, RevenueCat

## Contact

I take on a few outside projects: products with AI built in, mobile apps with a backend, and database performance work.

[lucasp4iva@gmail.com](mailto:lucasp4iva@gmail.com) · [LinkedIn](https://www.linkedin.com/in/lucasp4iva/)
