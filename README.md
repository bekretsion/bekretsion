<!-- HEADER -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1200&color=00F7FF&center=true&vCenter=true&width=750&lines=Bekretsion+Seyoum;Senior+Backend+Engineer;Node.js+%7C+TypeScript+%7C+PostgreSQL+%7C+Redis;Building+real-time+distributed+systems;Open+to+remote+roles" alt="Typing SVG" />
</p>

<h3 align="center">Backend Engineer — Node.js · TypeScript · PostgreSQL · Redis · WebSockets</h3>

<p align="center">
  <a href="https://github.com/bekretsion"><img src="https://img.shields.io/badge/GitHub-bekretsion-black?style=flat-square&logo=github" /></a>
  <a href="https://www.linkedin.com/in/bekretsion-seyoum/"><img src="https://img.shields.io/badge/LinkedIn-Bekretsion_Seyoum-blue?style=flat-square&logo=linkedin" /></a>
  <a href="mailto:bekretsionseyoum4@gmail.com"><img src="https://img.shields.io/badge/Email-bekretsionseyoum4@gmail.com-red?style=flat-square&logo=gmail" /></a>
  <img src="https://img.shields.io/badge/Open_to-Remote_Roles-brightgreen?style=flat-square" />
</p>

---

## About

Backend engineer focused on Node.js, TypeScript, and real-time distributed systems. I build APIs and WebSocket backends that handle concurrent users, complex auth flows, and multi-tenant data isolation.

Currently building a **multi-tenant collaborative notes API** using Hocuspocus, Yjs, Redis, and PostgreSQL — the core challenge is real-time document sync at scale with strict tenant isolation across WebSocket connections.

Async-first communicator. Self-managed. Comfortable across time zones.

---

## Current Build — Multi-Tenant Collaborative API

> A production-grade WebSocket backend built on [Hocuspocus](https://github.com/ueberdosis/hocuspocus) with full multi-tenancy, JWT auth, and horizontal scaling via Redis.

**What makes it senior-level:**
- `onAuthenticate` hook returns `{ userId, tenantId }` context — enforces tenant isolation at every layer
- Schema-per-tenant in PostgreSQL with row-level security policies
- Redis pub/sub adapter for horizontal scaling across multiple Node.js instances
- JWT access tokens (RS256) with refresh token rotation on every use
- Structured logging with Pino and correlation IDs on every connection
- Deployed with Docker + Railway + Upstash Redis + Neon PostgreSQL

`Node.js` `TypeScript` `Hocuspocus` `Yjs` `WebSockets` `Redis` `PostgreSQL` `Prisma` `JWT` `Docker`

🔗 *Live URL and source — coming soon*

---

## Other Projects

### Itutu — E-Commerce Platform
A full-stack e-commerce app built with Next.js 15, Prisma, Neon PostgreSQL, and TailwindCSS.

🔗 [Live Demo](https://itutu.vercel.app/) · [Source](https://github.com/bekretsion/itutu)

`Next.js 15` `Prisma` `PostgreSQL` `TailwindCSS` `TypeScript`

---

## Stack

**Core:** Node.js · TypeScript · PostgreSQL · Redis · WebSockets  
**Frameworks:** Express · Prisma · Hocuspocus  
**Auth:** JWT (RS256) · Refresh token rotation · RBAC  
**Infra:** Docker · GitHub Actions · Railway · Neon · Upstash  
**Observability:** Pino · OpenTelemetry · Correlation IDs  
**Frontend (supporting):** React · Next.js · TailwindCSS

---

## GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=bekretsion&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=bekretsion&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center">
  <i>Currently open to senior backend and Node.js remote roles.<br>
  Reach me at bekretsionseyoum4@gmail.com</i>
</p>
