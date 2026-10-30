# Federated Wireless

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

Federated Wireless, founded in 2012 and headquartered in Arlington, Virginia, is a shared- and unlicensed-spectrum coordination company. It is one of the FCC-certified CBRS Spectrum Access System (SAS) administrators for the 3.5 GHz band, operates a nationwide Environmental Sensing Capability (ESC) network, and is one of the seven 6 GHz Automated Frequency Coordination (AFC) systems the FCC Office of Engineering and Technology approved for commercial operation in February 2024. Its cloud-native platform — the Spectrum Controller, the Automated Network Planner (ANP) and the Spectrum AI physical-AI platform announced in June 2026 — assigns, monitors and optimizes spectrum for carriers, broadband providers, enterprises running private 5G/LTE, and government agencies. The programmable surface is real but almost entirely private: the regulated SAS-CBSD (WInnForum WINNF-TS-0016) and 6 GHz AFC device interfaces run on hosts that refuse public connections, and the Spectrum Controller's external SAS, IAM and KPI/analytics APIs are AWS API Gateway endpoints that return 403 to every anonymous request. Federated Wireless publishes no developer portal, no API reference and no machine-readable contract. The one openly discoverable agent surface is a remote Model Context Protocol server on federatedwireless.ai, advertised through RFC 8414 and RFC 9728 metadata, which fronts the company's WordPress content estate rather than its spectrum platform.

**Areas:** Company · Spectrum · CBRS · Wireless · Telecommunications · Private 5G · Shared Spectrum · Spectrum Access System · 6 GHz · Network Planning · RF Engineering · Government

## Federated Wireless on APIs.io

Everything profiled for Federated Wireless is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/federated-wireless/](https://apis.io/providers/federated-wireless/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Spectrum Controller External SAS API](https://apis.io/apis/federated-wireless/spectrum-controller-external-api/) — The external API of the Federated Wireless Spectrum Controller, the cloud platform that manages CBRS spectrum assignment, CBSD lifecycle, monitoring and…
- [Spectrum IAM API](https://apis.io/apis/federated-wireless/spectrum-iam-api/) — The identity and access-management service behind the Federated Wireless Spectrum Controller, called by the web application as IAM_BASE_URL. It backs…
- [Spectrum KPI Analytics and Reporting API](https://apis.io/apis/federated-wireless/spectrum-kpi-api/) — The analytics and reporting service behind the Spectrum Controller, called by the web application as both ANALYTICS_BASE_URL and REPORTING_BASE_URL. It…
- [SAS-CBSD Interface](https://apis.io/apis/federated-wireless/sas-cbsd-interface/) — The regulated Spectrum Access System to CBSD protocol interface Federated Wireless operates as an FCC-certified SAS administrator. The protocol —…
- [6 GHz AFC Device Interface](https://apis.io/apis/federated-wireless/afc-device-interface/) — The Automated Frequency Coordination system interface Federated Wireless operates for the 6 GHz band. On 2024-02-23 the FCC Office of Engineering and…
- [Federated Wireless MCP Server](https://apis.io/apis/federated-wireless/mcp-server/) — A remote Model Context Protocol server published on federatedwireless.ai, advertised through RFC 8414 OAuth authorization-server metadata and RFC 9728…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [federated-wireless](https://apis.io/servers/federated-wireless/federated-wireless/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Federated Wireless Authentication](https://apis.io/security/federated-wireless/federated-wireless-authentication/)
- [Federated Wireless Domain Security](https://apis.io/security/federated-wireless/federated-wireless-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Federated Wireless Scopes](https://apis.io/scopes/federated-wireless/federated-wireless-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Federated Wireless Plans Pricing](https://apis.io/plans/federated-wireless/federated-wireless-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Federated Wireless Rate Limits](https://apis.io/rate-limits/federated-wireless/federated-wireless-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://federatedwireless.ai/)
- [Sign up](https://myfederated.federatedwireless.com)
- [Support](https://federatedwireless.ai/support/)
- [Blog](https://federatedwireless.ai/resources/blog/)
- [Terms of service](https://federatedwireless.ai/terms-of-use/)
- [Privacy policy](https://federatedwireless.ai/privacy-policy/)
- [GitHub](https://github.com/federatedwireless)

## API Evangelist rating

**Kin Score 25.4** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.8 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 2.6 |
| Developer ergonomics | 28.6 |
| Access clarity | 34.2 |

**Agent readiness 19.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | platform (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 35.0** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/federated-wireless/](https://apis.io/providers/federated-wireless/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Federated Wireless: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/federated-wireless/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
