# ReportForge — PDF Reports + History + JSON Export

[![CI](https://github.com/dev-kaiki/reportforge/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/reportforge/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Sistema de relatórios: cadastro, histórico por cliente, **export JSON** e geração de **PDF profissional**.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> A geração de PDF entra no roadmap abaixo.

---

## ✅ Roadmap (MVP do demo)
- [ ] CRUD: clientes
- [ ] CRUD: relatórios
- [ ] Export JSON por relatório
- [ ] Geração de PDF (layout profissional)
- [ ] Tela Web: lista + filtros + download

---

## ▶️ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d
