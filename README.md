# The Watcher (MVP)

Goal: Turn news headlines (RSS) into opinion-based market analysis cards.
Format: consensus at top, professional lenses below (Macro, Quant, Historian, Policy, Commodities), badges (Horizon, Intensity, Uncertainty, Persistence).

Stack (all free):
- Frontend + API: Next.js on Vercel
- Database: Supabase (Postgres free tier)
- Ingestion: RSS via serverless cron
- UI: Tailwind + shadcn/ui

Next TODOs:
- [ ] Scaffold Next.js app
- [ ] Connect Supabase and create tables
- [ ] Simple `/api/ingest` to fetch RSS and insert
- [ ] Render placeholder “signal card” with consensus + lens slots
