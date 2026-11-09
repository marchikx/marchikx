---
name: Hire / paid test task
about: Tell me what is breaking — I reply within 24h
title: "[Hire] "
labels: hire
assignees: marchikx
---

## How this works

I reply **within 24 hours** (Europe/Madrid business days) with either a short estimate or three concrete checks for a **1-day paid test**.

Do **not** paste secrets, customer data, or private repo invites here. Share those after I reply.

Also sell: [Perfex ↔ n8n bridge (Gumroad)](https://soluradev.gumroad.com/l/perfex-n8n-bridge).

## Who you are

- Company / role:
- Timezone:
- Best way to reach you (email or Telegram):

## What is breaking (plain language)

One paragraph. Example: “Stripe webhooks sometimes double-process refunds” or “n8n misses Perfex events overnight.”

## Why it matters

What happens if nothing changes for 30 days?

## Constraints (optional)

- Deadline:
- Budget band:
- Stack already live:
- Systems we must not break:

## What I usually bring to a paid test (you can change this)

1. Fresh clone of a thin spike + `npm run verify` / `make verify` exits 0  
2. One happy path that matches your stack (webhook `202` + worker, or payment ledger, or LLM gate)  
3. One failure path you care about (retry/DLQ, bad signature, over-budget deny)

## Contact

- Email or Telegram:
