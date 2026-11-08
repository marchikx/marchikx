# Andrii Marchuk

**Reliability patterns for AI and webhook automation** — delivery queues, payment ledgers, LLM cost guardrails, and agent pipelines. Built to be verified with one command.

Spain · Open to paid contracts and a **1-day paid test task**  
→ [Open a Hire / test issue](https://github.com/marchikx/marchikx/issues/new?template=hire.md) · [Perfex↔n8n bridge on Gumroad](https://soluradev.gumroad.com/l/perfex-n8n-bridge)

---

## Start here by who you are

| You are… | Open first |
|---|---|
| Founder needing automation that does not drop events | [`ops-hq-demo`](https://github.com/marchikx/ops-hq-demo) → [`webhook-relay`](https://github.com/marchikx/webhook-relay) |
| Agency delivering n8n / CRM work | [`perfex-n8n-bridge`](https://github.com/marchikx/perfex-n8n-bridge) → [`n8n-crm-control-plane`](https://github.com/marchikx/n8n-crm-control-plane) |
| CTO reviewing senior engineering signal | [`stripe-payments-ledger`](https://github.com/marchikx/stripe-payments-ledger) · [`llm-guardrails`](https://github.com/marchikx/llm-guardrails) · [`nextjs-security-kit`](https://github.com/marchikx/nextjs-security-kit) |
| Curious, not hiring yet | Give a paid test — or skim [`ted-tender-radar`](https://github.com/marchikx/ted-tender-radar) |

Every public repo: **`make verify`** (or `npm run verify` / `pytest`) from a fresh clone → exit 0. MIT. CI on `main`.

---

## Track A — Integrations & reliability

- **[webhook-relay](https://github.com/marchikx/webhook-relay)** — outbox/inbox, leases, backoff, DLQ, HMAC, idempotency
- **[n8n-crm-control-plane](https://github.com/marchikx/n8n-crm-control-plane)** — signed n8n actions + HubSpot / Pipedrive / Salesforce adapters
- **[perfex-n8n-bridge](https://github.com/marchikx/perfex-n8n-bridge)** — Perfex CRM ↔ n8n (product on Gumroad)

## Track B — AI, agents & data

- **[llm-guardrails](https://github.com/marchikx/llm-guardrails)** — fail-closed daily ceiling, kill switch, PII redaction
- **[intent-radar](https://github.com/marchikx/intent-radar)** — Ashby ATS intake → normalize → gates → score (offline fixtures)
- **[ted-tender-radar](https://github.com/marchikx/ted-tender-radar)** — TED notice normalize/score + evidence store
- **[solura-ai-bot](https://github.com/marchikx/solura-ai-bot)** — Telegram + Gemini + SQLite, layered Python

## Track C — Products & full-stack

- **[ops-hq-demo](https://github.com/marchikx/ops-hq-demo)** — dark ops HQ demo (deliveries, payments, LLM budget)
- **[stripe-payments-ledger](https://github.com/marchikx/stripe-payments-ledger)** — Stripe webhook → 202 → worker, idempotent ledger
- **[nextjs-security-kit](https://github.com/marchikx/nextjs-security-kit)** — CSRF, SSRF, rate limit, audit hash chain, RBAC
- **[affiliate-core-saas](https://github.com/marchikx/affiliate-core-saas)** — Laravel multi-tenant affiliate + payouts
- **[redline-detailing-landing](https://github.com/marchikx/redline-detailing-landing)** — Next.js premium landing

---

## How I work

- Prefer **async 202 → worker** over sync webhook processing
- **Fail-closed** on cost and security gates
- Tests cover **failure paths**, not only happy paths
- One-command verify so you can check without trusting a screenshot

## Hire

1. Open the hire issue with your problem in one paragraph  
2. Optional: buy the Perfex↔n8n bridge if that is the exact need  
3. I reply with a scoped diagnostic or a 1-day paid test acceptance criteria

