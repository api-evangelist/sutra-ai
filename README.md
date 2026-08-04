# SUTRA (Two AI) (sutra-ai)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

SUTRA is a family of multilingual large language models from Two AI (Numeric), fluent in 50+ languages including Hindi, Gujarati, Tamil, Bengali, Korean, Arabic, and Japanese. The SUTRA API is OpenAI-compatible and serves the SUTRA-V2 instruction/conversation model and the SUTRA-R0 reasoning model through a single Bearer-authenticated REST interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sutra-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sutra-ai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Multilingual
- Inference
- Reasoning

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### SUTRA Chat Completions (Multilingual) API

OpenAI-compatible chat completions powered by SUTRA-V2 across 50+ languages, with streaming (SSE), temperature, max_tokens, and presence_penalty controls for conversational and multilingual workloads.

- **Human URL:** [https://docs.two.ai/docs/getting-started](https://docs.two.ai/docs/getting-started)
- **Base URL:** `https://api.two.ai/v2`

#### Tags

- Chat
- Completions
- Multilingual
- LLM

#### Properties

- [Documentation](https://docs.two.ai/docs/getting-started)
- [API Reference](https://docs.two.ai/docs/models/sutra-v2-guide)
- [OpenAPI](openapi/sutra-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/sutra-ai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/sutra-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sutra-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SUTRA Reasoning API

Advanced multi-step reasoning with the SUTRA-R0 model, surfaced through the same OpenAI-compatible chat completions endpoint for structured problem-solving and deep contextual analysis.

- **Human URL:** [https://docs.two.ai/docs/models/sutra-r0-guide](https://docs.two.ai/docs/models/sutra-r0-guide)
- **Base URL:** `https://api.two.ai/v2`

#### Tags

- Reasoning
- Chain of Thought
- Multilingual

#### Properties

- [Documentation](https://docs.two.ai/docs/models/sutra-r0-guide)
- [OpenAPI](openapi/sutra-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sutra-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sutra-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SUTRA Models API

Lists the SUTRA models available to an account (e.g. sutra-v2, sutra-r0) via the OpenAI-compatible models endpoint.

- **Human URL:** [https://docs.two.ai/docs/getting-started](https://docs.two.ai/docs/getting-started)
- **Base URL:** `https://api.two.ai/v2`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.two.ai/docs/getting-started)
- [OpenAPI](openapi/sutra-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sutra-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sutra-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/sutra-dev)
- [LinkedIn](https://www.linkedin.com/company/two-ai)
- [Website](https://www.two.ai)
- [Documentation](https://docs.two.ai/docs)
- [Plans](plans/sutra-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/sutra-ai-rate-limits.yml)
- [Fin Ops](finops/sutra-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
