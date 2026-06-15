# Weights & Biases (weights-and-biases)

Weights & Biases is the ML developer platform for experiment tracking, model registry, artifact management, sweeps, reports, and (Weave) GenAI evaluation. The W&B API is primarily a GraphQL endpoint, surfaced through a Python `wandb.Api` SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/weights-and-biases/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/weights-and-biases/refs/heads/main/apis.yml)

## Tags

- ML
- MLOps
- Experiment Tracking
- Model Registry
- GenAI

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### W&B GraphQL API

The W&B Public API is a GraphQL endpoint at `https://api.wandb.ai/graphql`. It backs the Python `wandb.Api()` SDK and exposes runs, projects, sweeps, artifacts, reports, registries, and automations. Authentication is via API key.

- **Human URL:** [https://docs.wandb.ai/ref/python/public-api/api/](https://docs.wandb.ai/ref/python/public-api/api/)
- **Base URL:** `https://api.wandb.ai/graphql`

#### Tags

- GraphQL
- Experiments
- Runs
- Artifacts
- Sweeps

#### Properties

- [Documentation](https://docs.wandb.ai/ref/python/public-api/api/)
- [Authentication](https://docs.wandb.ai/guides/track/public-api-guide)
- [SDK](https://docs.wandb.ai/ref/python/)
- [Postman Collection](collections/weights-and-biases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weights-and-biases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### W&B Import API (HTTP)

The wandb client uses an HTTP file/import endpoint to push run metrics, system stats, and artifacts. Generally accessed through the SDK rather than directly.

- **Human URL:** [https://docs.wandb.ai/guides/track/log/](https://docs.wandb.ai/guides/track/log/)
- **Base URL:** `https://api.wandb.ai/files`

#### Tags

- HTTP
- Logging
- Ingestion

#### Properties

- [Documentation](https://docs.wandb.ai/guides/track/log/)
- [Postman Collection](collections/weights-and-biases.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weights-and-biases.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://wandb.ai/)
- [Portal](https://docs.wandb.ai/)
- [Pricing](https://wandb.ai/site/pricing)
- [Source Code](https://github.com/wandb/wandb)
- [Plans](plans/weights-and-biases-plans-pricing.yml)
- [Rate Limits](rate-limits/weights-and-biases-rate-limits.yml)
- [Fin Ops](finops/weights-and-biases-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
