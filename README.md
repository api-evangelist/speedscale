# Speedscale

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
