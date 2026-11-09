# DisasterAlert

Phase 1 monorepo scaffold for a crowdsourced natural-disaster reporting platform.

This initial commit establishes the workspace layout, shared disaster types, NestJS API health endpoint, Prisma/PostGIS data model and migration, illustrative seed data, Expo mobile shell, React admin shell, and local Docker Compose services.

## Phase 1 status

This is a starter scaffold, not a production-ready application. Authentication, report workflows, real-time events, maps, moderation, notifications, deployment, and comprehensive tests are planned for later phases. Dependencies, migrations, and tests have not yet been validated in this environment.

## Repository layout

- `apps/mobile` — Expo mobile shell
- `apps/admin` — React/Vite admin shell
- `packages/api` — NestJS API, Prisma schema, migration, and seed
- `packages/shared` — shared domain types
- `infra` — infrastructure notes

See the project README in the Phase 1 archive for setup notes.