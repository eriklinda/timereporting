# Time Reporting – Monorepo

Generated 2025-04-28.

## Snabbstart

```bash
# Install pnpm om du inte redan har det
npm i -g pnpm

# Installera beroenden
pnpm install

# Starta både Next.js‑webben och NestJS‑API:et samtidigt
pnpm dev
```

| App | Port | Beskrivning |
|-----|------|------------|
| **web** | 3000 | Next.js 14, SSR |
| **api** | 3001 | NestJS 10, REST / Swagger |

## Deployment

* **Frontend** → Vercel  
* **API** → Railway (Docker)  
* **Database** → Supabase (Postgres)

Env‑filer (`.env`) är exkluderade via `.gitignore`.
