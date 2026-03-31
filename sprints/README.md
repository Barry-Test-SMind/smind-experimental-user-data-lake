# Sprints

All sprint data including active, draft, and finished sprints.

## Source
- Endpoint: `/sprints?limit=100` (all) and `/sprint` (latest)
- Last synced: 2026-03-31

## Contents
- `all.json` — All sprints (1 active, 20 finished)
- `latest.json` — Current active sprint detail

## Schema (key fields)
- `sprint_id` — Unique sprint identifier
- `start_date` / `end_date` — Sprint date range
- `challenges` — Sprint challenges with progress
- `status` — Sprint status
