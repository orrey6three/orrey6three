<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║   const dev = new Fullstack({ city: "Tyumen" });         ║
║   dev.build("ideas").ship("production");                 ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

</div>

---

## 👤 Who am I

Fullstack developer who thinks in systems and ships in features. I care about **clean architecture**, **developer experience** and **code that doesn't make future-me cry**.

- 🧠 I split responsibility between layers, not just files
- ⚙️ I write backends that scale and frontends that feel instant
- 🔬 Strong opinions on folder structure, weakly held

---

## 🚀 Stack

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=for-the-badge&logo=react&logoColor=white)

### Backend
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-0377CC?style=for-the-badge&logo=elasticsearch&logoColor=white)

### Infra & Tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

---

## 🏗️ Architecture I actually use

```
apps/
├── web/          ← Next.js App Router, RSC, streaming
├── api/          ← NestJS, CQRS, domain modules
└── shared/       ← types, contracts, zod schemas

Domain layer      → pure business logic, zero framework deps
Application layer → use cases, commands, queries (CQRS)
Infrastructure    → DB, cache, queue adapters
Presentation      → controllers, resolvers, route handlers
```

**Patterns I reach for:**

- `Feature-Sliced Design` on the frontend — no more spaghetti imports
- `CQRS + Repository` on the backend — read and write models live separately
- `Zod` as the single source of truth for types across the entire stack
- `Optimistic updates` + `React Query` for UX that feels native
- `BullMQ` for async work that shouldn't block the response

---

## 📊 Stats

<div align="center">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=orrey6three&theme=dark&hide_border=true&include_all_commits=true&layout=compact&langs_count=6)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=orrey6three&theme=dark&hide_border=true&include_all_commits=true&count_private=false&show_icons=true)

</div>

---

<div align="center">

[![Profile views](https://visitcount.itsvg.in/api?id=orrey6three&icon=5&color=6)](https://visitcount.itsvg.in)

</div>
