# Luma AI (luma-ai)

Luma AI builds generative video (Dream Machine / Ray) and image (Photon) models, plus agent and 3D capture products. The Dream Machine API exposes REST endpoints for video and image generation with submit + poll semantics.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/luma-ai/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Video Generation, Image Generation, 3D, Dream Machine, Multimodal

## APIs
1. **Luma Dream Machine API** — video (Ray) + image (Photon) generation at `https://api.lumalabs.ai/dream-machine/v1`.
2. **Luma Agents API (uni-1)** — agent-style image gen/edit at `https://agents.lumalabs.ai/v1`.

## Common Properties
- [Website](https://lumalabs.ai/)
- [Documentation](https://docs.lumalabs.ai/)
- [Plans](plans/luma-ai-plans-pricing.yml) — reconciled
- [RateLimits](rate-limits/luma-ai-rate-limits.yml) — partial
- [FinOps](finops/luma-ai-finops.yml) — reconciled

## Pricing Snapshot
- Build (PAYG): Ray-2 video $0.08/sec; uni-1 image $0.0404/req (2048px); image edit $0.0434/req
- With image references: $0.0434–$0.0644 per request
- Photon: $0.32 per million pixels generated
- Scale: provisioned throughput $2,100–$3,800/month per unit (8-unit minimum)
- Enterprise: custom

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
