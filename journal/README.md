# Journal

All journal notes with individual detail files.

## Source
- Endpoint: `/journal/notes?limit=50&offset=N` (list) and `/journal/notes/:id` (detail)
- Last synced: 2026-03-31

## Contents
- `notes.json` — All 337 notes (sorted by created_at)
- `notes/` — Individual note detail files (337 files)

## Schema (key fields)
- `note_id` — Unique note identifier
- `text` — Note content
- `note_type` — Type (general, etc.)
- `sprint_id` — Associated sprint
- `created_at` / `updated_at` — Timestamps
- `replies` — Coach replies (in detail files)
