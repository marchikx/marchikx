---
name: Hire / paid test task
about: Scoped diagnostic or 1-day paid test — I reply ≤24h with three ready checks
title: "[Hire] "
labels: hire
assignees: marchikx
---

## SLA

I reply **within 24 hours** (Europe/Madrid business days) with either a scoped estimate or three ready technical checks for a paid test. Sensitive details (repo access, secrets, customer data) — **after my first reply**, not in this public issue.

Secondary product: [Perfex↔n8n bridge on Gumroad](https://soluradev.gumroad.com/l/perfex-n8n-bridge).

## Who you are

- Company / role:
- Timezone:
- Preferred reply channel (email / Telegram):

## The problem (one paragraph)

What is breaking or missing today? Prefer outcome over stack wish-list.

## Why this matters in 30 days

Lost events, double charges, LLM spend, manual hours, blocked launch — pick what hurts.

## Constraints

- Deadline (if any):
- Budget band (optional):
- Stack already in production:
- Must-not-break systems:

## My three ready checks (I bring these — you do not write them)

Unless you override, a 1-day paid test starts from:

1. Fresh clone + `npm run verify` / `make verify` exits 0 on a thin spike in your stack
2. Webhook path returns **202** and a worker delivers / retries / DLQs correctly (or Stripe ledger `processWork` applies)
3. One failure mode you care about: bad HMAC, stale lease, unknown LLM model deny, or CRM adapter 401/429

## Contact

- Email or Telegram:
