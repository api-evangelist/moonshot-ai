# Moonshot AI (moonshot-ai)

Moonshot AI is a Chinese foundation model company best known for Kimi, an LLM with industry-leading long-context capabilities. The Moonshot platform exposes OpenAI-compatible chat completion, files, batch, models, balance, and token-estimation APIs at `https://api.moonshot.ai`.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/moonshot-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=moonshot-ai-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, Long Context, Kimi

## APIs
- **Moonshot AI Platform API** — OpenAI-compatible inference, files, batch, models, balance, and token estimation. Base URL: `https://api.moonshot.ai`. [Docs](https://platform.kimi.ai/docs) · [OpenAPI](openapi/moonshot-ai-openapi.json) · [Console](https://platform.kimi.ai/console/api-keys) · [Playground](https://platform.kimi.ai/playground)

### Models
Kimi K2.6 (multimodal, 256K context), Kimi K2.5, Kimi K2, Moonshot V1 (8K/32K/128K).

## Plans, Rate Limits, FinOps
- [Plans](plans/moonshot-ai-plans-pricing.yml) — Pay-as-you-go per million tokens; batch at 50% off; tiers Tier0–Tier5 by cumulative recharge.
- [RateLimits](rate-limits/moonshot-ai-rate-limits.yml) — Tier0: 3 RPM / 1 concurrency; Tier5: 10K RPM / 1000 concurrency / 5M TPM.
- [FinOps](finops/moonshot-ai-finops.yml) — FOCUS-aligned profile (prepaid recharge, usage-metered tokens).

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://www.moonshot.ai/)
- [Documentation](https://platform.kimi.ai/docs)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
