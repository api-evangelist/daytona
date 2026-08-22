# Daytona (daytona)

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

Daytona provides secure, elastic sandbox infrastructure for running AI-generated code, with sub-90ms sandbox creation, multi-language runtimes, and full filesystem, process, Git, and Language Server Protocol APIs. Sandboxes are stateful, snapshot-able, and deployable across US, EU, and Asia regions, and the platform supports HIPAA, SOC 2, and GDPR. Target customers are AI agent companies, coding-agent builders, data teams, RL labs, and enterprises that need to execute untrusted or LLM-authored code in isolation. Daytona ships Python and TypeScript SDKs (with Ruby, Go, and Java available) backed by a documented REST API and OpenAPI specs. Pricing is pay-as-you-go and per-second across vCPU, memory, GPU, and storage with a $200 free credit.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/daytona/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/daytona/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Sandboxes
- Secure Execution
- AI Agents
- Coding Agents
- Code Interpreter
- Snapshots
- Multi-Region
- HIPAA
- SOC 2
- GDPR
- Python
- TypeScript
- Open Source
- LSP

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Daytona Sandbox API

The Daytona Sandbox API creates and manages isolated cloud sandboxes with process execution, filesystem operations, Git integration, and a Language Server Protocol toolbox. SDKs and the REST API let agents provision per-task environments, stream stdout/stderr, snapshot state, and share volumes.

- **Human URL:** [https://www.daytona.io/docs](https://www.daytona.io/docs)
- **Base URL:** `https://app.daytona.io/api`

#### Tags

- Sandboxes
- Process
- Filesystem
- Git
- LSP
- Snapshots
- Volumes

#### Properties

- [Documentation](https://www.daytona.io/docs)
- [API Reference](https://www.daytona.io/docs/en/api-reference)
- [Getting Started](https://www.daytona.io/docs/en/getting-started)
- [Sign Up](https://app.daytona.io/)
- [OpenAPI](https://app.daytona.io/api/docs/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://app.daytona.io/api/docs/toolbox-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [SDK](https://pypi.org/project/daytona/)
- [SDK](https://www.npmjs.com/package/@daytona/sdk)
- [GitHub Repository](https://github.com/daytonaio/daytona)
- [Pricing](https://www.daytona.io/pricing)
- [Postman Collection](collections/daytona.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/daytona.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.daytona.io)
- [Documentation](https://www.daytona.io/docs)
- [Blog](https://www.daytona.io/dotfiles)
- [GitHub Organization](https://github.com/daytonaio)
- [GitHub Repository](https://github.com/daytonaio/daytona)
- [Pricing](https://www.daytona.io/pricing)
- [Customers](https://www.daytona.io/customers)
- [Sign Up](https://app.daytona.io/)
- [Terms of Service](https://www.daytona.io/terms)
- [Privacy Policy](https://www.daytona.io/privacy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
