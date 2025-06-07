# 🧠 MealMind

**MealMind** is a fullstack TypeScript app for meal planning, recipe inspiration, and automatic grocery list generation. Built to showcase modern web architecture, DX, and performance.

---

## ✨ Features

- 🍽️ **Smart Meal Planning** – Drag & drop weekly planner
- 📦 **Auto Grocery Lists** – Based on chosen recipes
- 🔎 **Recipe Search** – Filter by ingredients, tags, macros
- 📋 **Shopping Modes** – Tick off items on mobile
- 💬 **GraphQL API** – Typed from Hasura schema
- ✅ **E2E & Unit Testing** – Cypress + Vitest

---

## 🧱 Tech Stack

| Layer        | Technology                                   |
| ------------ | -------------------------------------------- |
| **Frontend** | [Next.js](https://nextjs.org/), TailwindCSS  |
| **Backend**  | [Hono](https://hono.dev/) (Fast Edge API)    |
| **GraphQL**  | [Hasura](https://hasura.io/)                 |
| **Database** | PostgreSQL                                   |
| **Testing**  | Cypress (E2E), Vitest (Unit)                 |
| **Tooling**  | Turborepo, pnpm, TypeScript, GraphQL Codegen |

---

## 📂 Monorepo Structure

```bash
meal-mind/
├── apps/
│   ├── web/        # Next.js frontend
│   ├── api/        # Hono backend API
│   └── hasura/     # Hasura GraphQL Engine (Docker)
├── packages/
│   ├── ui/         # Shared UI components
│   ├── graphql/    # GraphQL codegen & fragments
│   ├── utils/      # Shared logic/utilities
│   └── config/     # Shared tsconfig/lint/etc.
└── turbo.json      # Task pipeline
```

---

## 🚀 Getting Started

```bash
pnpm install
pnpm dev

> localhost:3000          → Frontend
> localhost:3001/hello    → Hono API
> localhost:8080          → Hasura Console
```

## 🛠️ Skills Highlighted

- Fullstack type-safety /w GraphQL and Typescript
- Modern monorepo architecture (Turborepo + pnpm)
- Modular structure using turborepo with pnpm workspaces
- Edge-ready backend with Hono
- Test-driven development with cypress and vitest

## 📸 Screenshots

_Coming soon…_
