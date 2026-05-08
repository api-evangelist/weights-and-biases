# Weights & Biases (weights-and-biases)

Weights & Biases is the ML developer platform for experiment tracking, model registry, artifact management, sweeps, reports, and (Weave) GenAI evaluation. The W&B API is primarily a GraphQL endpoint, surfaced through a Python `wandb.Api` SDK.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/weights-and-biases/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=weights-and-biases-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **W&B GraphQL API** - Public API at `https://api.wandb.ai/graphql`. Backs the Python `wandb.Api()` SDK. Runs, projects, sweeps, artifacts, reports, registries, automations.
- **W&B Import API (HTTP)** - HTTP file/import endpoint used by the wandb client to push metrics and artifacts.

## Tags
- ML, MLOps, Experiment Tracking, Model Registry, GenAI

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://wandb.ai/)
- [Documentation](https://docs.wandb.ai/)
- [Pricing](https://wandb.ai/site/pricing)
- [Source: wandb client](https://github.com/wandb/wandb)
- [Plans](plans/weights-and-biases-plans-pricing.yml)
- [RateLimits](rate-limits/weights-and-biases-rate-limits.yml)
- [FinOps](finops/weights-and-biases-finops.yml)

## Notes
- Pricing reconciled (research): Free (5 model seats, 5 GB storage), Pro from $60/mo (10 model seats, 100 GB), Enterprise custom. Weave data ingestion at $0.10/MB on Pro. Self-hosted W&B Server is free for personal use.
- Public API is GraphQL, not REST — query semantics handled through the SDK with MongoDB-style filtering on runs/artifacts.
- No published per-account REST rate limit.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
