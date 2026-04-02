# DB Dumps

Raw database table exports for Barry Goldsmith from the hOS platform.
Note: `user_id` and `client_id` fields = `6daf1120-2e6a-488d-9174-51321f7308ca` (Barry).

## Source
- Exported directly from hOS production database
- Last synced: 2026-04-02

## Contents

| File | Table | Rows | Description |
|------|-------|------|-------------|
| `optimal_day_activities.csv` | Activities | 157 | Scheduled daily activities with dimensions (sleep, career, meals, etc.) |
| `challenge_progress.csv` | Challenge progress | 3,932 | Daily challenge tracking (status, amount_tracked per challenge per date) |
| `sprint_challenges.csv` | Sprint challenges | 410 | Challenge assignments to sprints with objectives and frequency configs |
| `weekly_priorities.csv` | Weekly priorities | 95 | Weekly goals/priorities with status (COMPLETED, FAILED, STARTED, etc.) |
| `goals.csv` | Goals | 18 | Long-term goals with dimensions and deep-dive details |
| `note_replies.csv` | Note replies | 22 | Replies to journal notes |
| `notes.csv` | Notes | 491 | Journal notes (GENERAL, PROOF, REFLECTION_QUESTION) with challenge linkage |
