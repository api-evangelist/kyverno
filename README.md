# Kyverno (kyverno)

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

Kyverno is a Kubernetes native policy management engine for security, automation, and governance. It uses Kubernetes admission controllers to validate, mutate, and generate configurations using policies written as Kubernetes resources.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kyverno/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kyverno/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- Governance
- Kubernetes
- Policy Management
- Security

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Kyverno

Kyverno is a Kubernetes-native policy engine that runs as a dynamic admission controller to validate, mutate, and generate Kubernetes resources using policies written as Kubernetes resources. It supports policy types across multiple API groups including kyverno.io, policies.kyverno.io, and policyreport.io, covering validation, mutation, generation, cleanup, and image verification use cases.

- **Human URL:** [https://kyverno.io/](https://kyverno.io/)

#### Tags

- Kubernetes
- Policy
- Security

#### Properties

- [Documentation](https://kyverno.io/docs/introduction/)
- [Getting Started](https://kyverno.io/docs/installation/)
- [Reference](https://kyverno.io/docs/policy-types/)
- [Changelog](https://kyverno.io/docs/releases/)
- [GitHub Repository](https://github.com/kyverno/kyverno)
- [Postman Collection](collections/kyverno-policy-reporter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kyverno-policy-reporter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kyverno CLI

The Kyverno CLI provides a command-line interface for applying and testing Kyverno policies against Kubernetes resources outside of a cluster. It can be used in CI/CD pipelines to validate resources before deployment, run policy tests, and interact with JMESPath expressions used in policy rules.

- **Human URL:** [https://kyverno.io/docs/kyverno-cli/](https://kyverno.io/docs/kyverno-cli/)

#### Tags

- CLI
- Developer Tools
- Kubernetes
- Policy

#### Properties

- [Documentation](https://kyverno.io/docs/kyverno-cli/)
- [Reference](https://kyverno.io/docs/kyverno-cli/reference/kyverno/)
- [GitHub Repository](https://github.com/kyverno/kyverno)
- [Postman Collection](collections/kyverno-policy-reporter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kyverno-policy-reporter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kyverno Policy Reporter API

The Kyverno Policy Reporter REST API provides endpoints for querying PolicyReport and ClusterPolicyReport custom resources generated by Kyverno. It exposes policy results, status counts, and resource-level violation data, and serves as the backend for the Policy Reporter UI.

- **Human URL:** [https://kyverno.github.io/policy-reporter/](https://kyverno.github.io/policy-reporter/)

#### Tags

- Observability
- Policy Reports
- REST API

#### Properties

- [Documentation](https://kyverno.github.io/policy-reporter/)
- [Reference](https://kyverno.github.io/policy-reporter/core/api-reference/)
- [Getting Started](https://kyverno.github.io/policy-reporter/guide/getting-started/)
- [GitHub Repository](https://github.com/kyverno/policy-reporter)
- [OpenAPI](openapi/kyverno-policy-reporter-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kyverno-policy-reporter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kyverno-policy-reporter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/nirmata)
- [Website](https://kyverno.io/)
- [Documentation](https://kyverno.io/docs/)
- [Getting Started](https://kyverno.io/docs/installation/)
- [Changelog](https://kyverno.io/docs/releases/)
- [GitHub Organization](https://github.com/kyverno)
- [GitHub Repository](https://github.com/kyverno/kyverno)
- [Blog](https://kyverno.io/blog/)
- [Community](https://kyverno.io/community/)
- [JSON Schema](json-schema/kyverno-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kyverno-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://kyverno.io/integrations)
- [L L Ms Txt](https://kyverno.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
