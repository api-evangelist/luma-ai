# Luma AI (luma-ai)

Luma AI builds generative video (Dream Machine / Ray) and image (Photon) models, plus agent and 3D capture products. The Dream Machine API exposes REST endpoints for video and image generation with submit + poll semantics, an agent uni-1 model, and SDKs for Python, JavaScript, Go, and a CLI. Pricing is per-second for video and per-request or per-pixel for images.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/luma-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/luma-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Video Generation
- Image Generation
- 3D
- Dream Machine
- Multimodal

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Luma Dream Machine API

REST API for video (Ray series) and image (Photon) generation. Submit a generation request, then poll for status. Documentation at https://docs.lumalabs.ai/. Auth via API key from https://lumalabs.ai/dream-machine/api/keys.

- **Human URL:** [https://docs.lumalabs.ai/](https://docs.lumalabs.ai/)
- **Base URL:** `https://api.lumalabs.ai/dream-machine/v1`

#### Tags

- Video Generation
- Image Generation
- Ray
- Photon
- Dream Machine

#### Properties

- [Documentation](https://docs.lumalabs.ai/)
- [Sign Up](https://lumalabs.ai/dream-machine/api/keys)
- [Pricing](https://lumalabs.ai/dream-machine/api/billing/overview)
- [Status Page](https://status.lumalabs.ai/)
- [AsyncAPI](asyncapi/luma-ai-callback-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/luma-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/luma-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luma Agents API (uni-1)

Agent-style image generation/editing with a reasoning endpoint and a generation endpoint. Uses /v1/generations submit and /v1/generations/{generation_id} polling pattern at https://agents.lumalabs.ai/v1.

- **Human URL:** [https://docs.agents.lumalabs.ai/](https://docs.agents.lumalabs.ai/)
- **Base URL:** `https://agents.lumalabs.ai/v1`

#### Tags

- Agents
- Image Generation
- Image Editing

#### Properties

- [Documentation](https://docs.agents.lumalabs.ai/)
- [Postman Collection](collections/luma-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/luma-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/lumalabs)
- [LinkedIn](https://www.linkedin.com/company/luma-ai)
- [Website](https://lumalabs.ai/)
- [Documentation](https://docs.lumalabs.ai/)
- [Plans](plans/luma-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/luma-ai-rate-limits.yml)
- [Fin Ops](finops/luma-ai-finops.yml)
- [L L Ms Txt](https://docs.lumalabs.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
