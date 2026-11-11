# Inventario — CRUD distribuido

Proyecto para aprender React, construyéndolo yo, guiado por Muse.

- **Frontend:** React + TypeScript (Vite)
- **Backend:** Go, API REST
- **Base de datos:** PostgreSQL
- **Lo distribuido:** patrón outbox (`outbox_events` + worker a `audit_log`)

## Cómo correrlo

```bash
# Backend
cd backend
go run .

# Frontend
cd frontend
npm install
npm run dev
```

## Estructura

- `frontend/` — app React + TypeScript
- `backend/` — API REST en Go
- `postman/` — colección para probar el API

## Roadmap

Ver `Roadmap_React_CRUD_Distribuido.md` (Fases 0–12, con gamificación).
