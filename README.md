# Smart Inventory & Supply Chain Management System

Next.js dashboard with Node API routes, PostgreSQL persistence, Redis-backed alerts, stock monitoring, supplier management, forecasting, and reports.

## Run

```bash
cp .env.example .env
docker compose up -d
npm install
npm run dev
```

Open `http://localhost:3000`.

## Useful Commands

```bash
npm run db:seed
npm run build
npm run lint
```

The app shows seeded fallback data if database variables are not configured, then switches to PostgreSQL and Redis when `.env` is available.
