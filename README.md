<h1 align="center">Bekretsion Seyoum</h1>

<p align="center"><b>Backend Engineer</b> · Node.js · TypeScript · PostgreSQL · Redis · WebSockets</p>

<h2 align="center">🌐 <a href="https://bekretsion.com">bekretsion.com</a></h2>

<p align="center">
  <a href="https://bekretsion.com"><img src="https://img.shields.io/badge/Website-bekretsion.com-00B4D8?style=for-the-badge" alt="bekretsion.com" /></a>
  <a href="https://www.linkedin.com/in/bekretsion-seyoum/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:bekretsionseyoum4@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build backends for real-time, multi-tenant products: WebSocket servers, auth, and data isolation that hold up with many users connected at once. I work remotely and async-first across time zones.

More about me and my work: **[bekretsion.com](https://bekretsion.com)**

## Now building: Collab API

A multi-tenant backend for real-time collaborative editing. It uses Yjs CRDTs for sync, PostgreSQL for storage and Redis to scale across instances.

[Live API](https://collab-api-jayn.onrender.com) · [Playground](https://collab-api-frontend.vercel.app) · [Source](https://github.com/bekretsion/collab_api)

- **Tenant isolation:** every connection resolves to `{ userId, tenantId }`, backed by a separate PostgreSQL schema per tenant and row-level security
- **Horizontal scaling:** Redis pub/sub sends updates to every Node.js instance
- **Auth:** RS256 JWTs, with the refresh token rotated on every use
- **Consistency:** CRDT merges, so edits made at the same time never overwrite each other
- **Observability:** structured Pino logs with a correlation ID per connection

## Hello: AI receptionist

A voice agent for hotels that answers calls in 95+ languages, books appointments and makes outbound sales calls. National finalist at [Hospitality Hackathon 2026](https://www.hospitalityhackathon.et/) (ALX Ethiopia × Kuriftu Resorts).

[Demo](https://hello-frontend-three.vercel.app) · [Backend](https://github.com/bekretsion/hello_backend) · [Frontend](https://github.com/bekretsion/hello_frontend) · [Press](https://thevoiceofafrica.com/2026/05/04/hospitality-hackathon-2026-demo-day-at-kuriftu-resorts-african-village-sets-global-innovation-record/)

## Stack

- **Backend:** Node.js, TypeScript, Express, Prisma
- **Data:** PostgreSQL, Redis
- **Auth:** JWT (RS256), refresh token rotation, RBAC
- **Infra:** Docker, GitHub Actions, Render, Neon, Upstash
- **Observability:** Pino, OpenTelemetry
- **Frontend:** React, Next.js, Tailwind

---

<p align="center">
  Open to remote backend roles<br>
  <a href="https://bekretsion.com"><b>bekretsion.com</b></a> · <a href="mailto:bekretsionseyoum4@gmail.com">bekretsionseyoum4@gmail.com</a>
</p>
