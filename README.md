# Andrii Marchuk

**Reliability for webhooks, payments, and LLM spend** — patterns you can verify with one command.

Spain · Paid contracts · **≤24h reply** · [Hire / paid test](https://github.com/marchikx/marchikx/issues/new?template=hire.md) · [Gumroad: Perfex↔n8n](https://soluradev.gumroad.com/l/perfex-n8n-bridge)

**Proof:** [live Ops HQ](https://marchikx.github.io/ops-hq-demo/) runs `webhook-relay` → DLQ, Stripe `202→worker`, `llm-guardrails` deny — Playwright-covered.

| Pin | Why open it |
|---|---|
| [ops-hq-demo](https://github.com/marchikx/ops-hq-demo) | Interactive failure-path console |
| [webhook-relay](https://github.com/marchikx/webhook-relay) | Outbox, lease fencing, HMAC, DLQ |
| [stripe-payments-ledger](https://github.com/marchikx/stripe-payments-ledger) | Idempotent Stripe 202→worker |
| [llm-guardrails](https://github.com/marchikx/llm-guardrails) | Fail-closed daily ceiling |
| [nextjs-security-kit](https://github.com/marchikx/nextjs-security-kit) | CSRF TTL, SSRF, audit chain |
| [perfex-n8n-bridge](https://github.com/marchikx/perfex-n8n-bridge) | Perfex CRM ↔ n8n product |

Every public repo: `make verify` / `npm run verify` → exit 0. MIT. CI on `main`.

---

<details>
<summary>More repos (not pins)</summary>

- [n8n-crm-control-plane](https://github.com/marchikx/n8n-crm-control-plane) — signed n8n actions + HubSpot/Pipedrive/Salesforce
- [intent-radar](https://github.com/marchikx/intent-radar) — Ashby ATS intake → gates → score
- [ted-tender-radar](https://github.com/marchikx/ted-tender-radar) — TED notice normalize/score (offline fixtures)
- [solura-ai-bot](https://github.com/marchikx/solura-ai-bot) — Telegram + Gemini + SQLite
- [affiliate-core-saas](https://github.com/marchikx/affiliate-core-saas) — Laravel multi-tenant affiliate
- [redline-detailing-landing](https://github.com/marchikx/redline-detailing-landing) — Next.js landing

</details>

### Bar I hire against

Async **202 → worker**, fail-closed cost/security gates, failure-path tests, no fake prod traffic claims.
