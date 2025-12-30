<div align="center">

# reportforge

<a href="https://dev-kaiki-reportforge.vercel.app"><img src="https://img.shields.io/badge/LIVE%20DEMO-Vercel-111?style=for-the-badge&logo=vercel&logoColor=white"></a>
<a href="https://dev-kaiki-reportforge-api.onrender.com/docs"><img src="https://img.shields.io/badge/SWAGGER-API%20Docs-111?style=for-the-badge&logo=swagger&logoColor=white"></a>
<a href="https://github.com/dev-kaiki/reportforge"><img src="https://img.shields.io/badge/REPO-GitHub-111?style=for-the-badge&logo=github&logoColor=white"></a>

</div>

## Quick Links
- Live: https://dev-kaiki-reportforge.vercel.app
- Swagger: https://dev-kaiki-reportforge-api.onrender.com/docs

## Deploy (1-click)
- Deploy API (Render): https://render.com/deploy?repo=https://github.com/dev-kaiki/reportforge
- Deploy Web (Vercel): https://vercel.com/new/clone?repository-url=https://github.com/dev-kaiki/reportforge

---

# ReportForge â€” PDF Reports + History + JSON Export

[![CI](https://github.com/dev-kaiki/reportforge/actions/workflows/ci.yml/badge.svg)](https://github.com/dev-kaiki/reportforge/actions/workflows/ci.yml)
![Next](https://img.shields.io/badge/next.js-14-222?logo=next.js)
![NestJS](https://img.shields.io/badge/nestjs-10-222?logo=nestjs)
![Postgres](https://img.shields.io/badge/postgres-16-222?logo=postgresql)
![Docker](https://img.shields.io/badge/docker-ready-222?logo=docker)

Sistema de relatÃ³rios: cadastro, histÃ³rico por cliente, **export JSON** e geraÃ§Ã£o de **PDF profissional**.

> **Status atual:** repo criado a partir do template (API + Web + Postgres).  
> Endpoints prontos: `/health`, `/users` e Swagger `/docs`.  
> A geraÃ§Ã£o de PDF entra no roadmap abaixo.

---

## âœ… Roadmap (MVP do demo)
- [ ] CRUD: clientes
- [ ] CRUD: relatÃ³rios
- [ ] Export JSON por relatÃ³rio
- [ ] GeraÃ§Ã£o de PDF (layout profissional)
- [ ] Tela Web: lista + filtros + download

---

## â–¶ï¸ Rodar local
```powershell
corepack enable
corepack prepare pnpm@latest --activate

pnpm install
docker compose up -d

