# DB Dumps

Raw database table exports for Barry Goldsmith from the hOS platform.
Note: `user_id` fields = `6daf1120-2e6a-488d-9174-51321f7308ca` (Barry).

## Source
- Exported directly from hOS production database
- Last synced: 2026-04-02

## Contents

| File | Table | Rows | Description |
|------|-------|------|-------------|
| `calendar_events.csv` | calendar_events | 157 | Scheduled events with dimensions, dates, and external IDs |
| `challenge_progress.csv` | challenge_progress | 3,932 | Daily challenge tracking (status, amount_tracked per challenge per date) |
| `challenge_states.csv` | challenge_states | 410 | Challenge assignments with title, objectives, difficulty ratings, and ranks |
| `desired_outcomes.csv` | desired_outcomes | 95 | Weekly desired outcomes with status (COMPLETED, FAILED, STARTED, NOT_STARTED) |
| `goals.csv` | goals | 18 | Long-term goals with dimensions (HEALTH, CAREER, etc.) and deep-dive details |
| `journal_note_replies.csv` | journal_note_replies | 22 | User replies to journal notes |
| `journal_notes.csv` | journal_notes | 491 | Journal entries (GENERAL, PROOF, REFLECTION_QUESTION) with challenge linkage and media |
| `weekly_outcomes.csv` | weekly_outcomes | 75 | Weekly outcomes/priorities with status (completed, failed, started, not_started) |
