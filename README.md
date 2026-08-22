# Luma AI (luma-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
