# Speedscale

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

Speedscale is an API traffic replay and performance testing platform that captures production API traffic and replays it in test environments for load testing, regression testing, and validation of AI-generated code. It enables teams to simulate realistic traffic patterns without building test scripts from scratch, with native Kubernetes support, service virtualization, PII-safe replay, and MCP integration for AI coding agents.

**URL:** [https://speedscale.com](https://speedscale.com)

## Products

- **Proxymock** — Free local-first traffic capture and mocking CLI tool
- **Speedscale Platform** — Cloud-based traffic replay, load testing, and CI/CD integration
- **speedctl** — The primary CLI (`speedctl`) for data collection, replay scheduling, and infrastructure control
- **Kubernetes Operator** — Helm-based operator for automatic sidecar injection and traffic capture

## Key Capabilities

- Full payload capture of requests/responses, headers, auth tokens, and timing
- Deterministic traffic replay in disposable sandboxes
- Service virtualization for mocking upstream dependencies
- Load testing at production-scale traffic volumes
- PII-safe replay with automatic field masking
- MCP integration for Claude Code, Cursor, and GitHub Copilot
- CI/CD pipeline integration for automated regression testing
- New Relic and Datadog observability integrations

## Pricing

| Tier | Description |
|------|-------------|
| Free (proxymock) | Local mocking, unlimited captures, community support |
| Pro | Cloud replay, CI/CD integration, team collaboration |
| Enterprise | BYOC, SSO, SLAs, dedicated support |

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

API Mocking, API Testing, Kubernetes, Load Testing, Performance Testing, Regression Testing, Service Virtualization, Traffic Replay

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-02

## APIs

### Speedscale Platform

Traffic capture and replay for load testing, regression testing, and validating AI-generated code.

**Human URL:** [https://speedscale.com](https://speedscale.com)

#### Properties

| Type | URL |
|------|-----|
| Documentation | [https://docs.speedscale.com](https://docs.speedscale.com) |
| Getting Started | [https://docs.speedscale.com/guides/getting-started/](https://docs.speedscale.com/guides/getting-started/) |
| CLI Reference | [https://docs.speedscale.com/reference/cli/](https://docs.speedscale.com/reference/cli/) |
| Pricing | [https://speedscale.com/pricing/](https://speedscale.com/pricing/) |
| Blog | [https://speedscale.com/blog](https://speedscale.com/blog) |
| GitHub | [https://github.com/speedscale](https://github.com/speedscale) |

## Common Resources

| Type | URL |
|------|-----|
| Website | [https://speedscale.com](https://speedscale.com) |
| Documentation | [https://docs.speedscale.com](https://docs.speedscale.com) |
| GitHub Organization | [https://github.com/speedscale](https://github.com/speedscale) |
| CLI (speedctl) | [https://github.com/speedscale/speedscale-cli](https://github.com/speedscale/speedscale-cli) |
| Helm Chart | [https://github.com/speedscale/operator-helm](https://github.com/speedscale/operator-helm) |
| Proxymock Examples | [https://github.com/speedscale/proxymock-examples](https://github.com/speedscale/proxymock-examples) |
| Login | [https://app.speedscale.com](https://app.speedscale.com) |
| Signup | [https://app.speedscale.com/signup](https://app.speedscale.com/signup) |
| Support | [https://docs.speedscale.com/support/](https://docs.speedscale.com/support/) |
| Twitter | [https://twitter.com/speedscaleinc](https://twitter.com/speedscaleinc) |
| LinkedIn | [https://www.linkedin.com/company/speedscale](https://www.linkedin.com/company/speedscale) |
| YouTube | [https://www.youtube.com/@speedscale](https://www.youtube.com/@speedscale) |

## Artifacts

| Type | File |
|------|------|
| JSON Schema | [json-schema/speedscale-traffic-schema.json](json-schema/speedscale-traffic-schema.json) |
| JSON Structure | [json-structure/speedscale-traffic-structure.json](json-structure/speedscale-traffic-structure.json) |
| JSON-LD Context | [json-ld/speedscale-context.jsonld](json-ld/speedscale-context.jsonld) |
| Vocabulary | [vocabulary/speedscale-vocabulary.yml](vocabulary/speedscale-vocabulary.yml) |
| Example | [examples/speedscale-snapshot-example.json](examples/speedscale-snapshot-example.json) |
| Spectral Rules | [rules/speedscale-rules.yml](rules/speedscale-rules.yml) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
