# Agent notes
- Pure static site: a single `index.html` (inline CSS/JS), no build, no deps, no secrets.
- Dev: `docker compose -f docker-compose.base44.yml up -d` serves the repo root via nginx on port 3000 (bind-mounted; edits show on browser refresh, no live reload).
- Verify: `curl -s localhost:3000 | grep TraderStats`.
