---
name: Hire / paid test task
about: One problem → scoped diagnostic or 1-day paid test with acceptance checks
title: "[Hire] "
labels: hire
assignees: marchikx
---

## Who you are

- Company / role:
- Timezone:
- How you found this profile:

## The problem (one paragraph)

What is breaking or missing today? Prefer outcome over stack wish-list.  
Links (repo / ticket / Loom / diagram) welcome.

## Why this is urgent / valuable

What happens if nothing changes in 30 days? (lost events, double charges, LLM spend, manual hours, blocked launch…)

## Constraints

- Deadline (if any):
- Budget band (optional):
- Stack already in production:
- Must-not-break systems:

## Acceptance checks for a 1-day paid test (optional but preferred)

List 2–5 checks I can run or demo (commands, HTTP probes, screenshots, metrics).

Example shape:

1. Fresh clone + `npm run verify` / `pytest` exits 0 on a thin spike
2. Webhook path returns 202 and a worker processes / DLQs correctly
3. One failure-mode test you care about (retry, idempotency, budget kill switch)

## Contact

- Email or Telegram (preferred reply channel):
