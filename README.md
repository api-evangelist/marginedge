# MarginEdge

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

MarginEdge is a restaurant back-office platform that automates invoice processing, inventory, recipe costing, and bill payment, syncing daily food cost and sales data into a restaurant's accounting system. Founded in 2015, it serves over 7,000 restaurants across all 50 states. For developers, MarginEdge publishes a public API through a dedicated developer portal that lets authorized parties programmatically retrieve invoice and product data from the restaurants they are permitted to access. Typical consumers include multi-unit operators building custom reporting, accounting groups, and business intelligence providers contracting with MarginEdge customers to deliver data services.

**Areas:** Restaurant · Back Office · Invoices · Inventory · Accounting · Reporting

## MarginEdge on APIs.io

Everything profiled for MarginEdge is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/marginedge/](https://apis.io/providers/marginedge/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [MarginEdge Categories API](https://apis.io/apis/marginedge/marginedge-categories-api/) — Accounting categories
- [MarginEdge Orders API](https://apis.io/apis/marginedge/marginedge-orders-api/) — Invoices/orders processed in MarginEdge
- [MarginEdge Products API](https://apis.io/apis/marginedge/marginedge-products-api/) — Products tracked in a restaurant
- [MarginEdge Restaurant Units API](https://apis.io/apis/marginedge/marginedge-restaurant-units-api/) — Restaurants, groups, and group categories you can access
- [MarginEdge Vendors API](https://apis.io/apis/marginedge/marginedge-vendors-api/) — Vendors and their items and packaging

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [marginedge](https://apis.io/servers/marginedge/marginedge/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Marginedge Agentic Access](https://apis.io/agentic-access/marginedge/marginedge-agentic-access/)

#### JSON Schema (10)

The data models the API reads and writes.

- [GetAvailableRestaurantUnitsResponseModel](https://apis.io/schemas/marginedge/public-api-get-available-restaurant-units-response-model/)
- [GetCategoriesResponseModel](https://apis.io/schemas/marginedge/public-api-get-categories-response-model/)
- [GetGroupCategoriesResponseModel](https://apis.io/schemas/marginedge/public-api-get-group-categories-response-model/)
- [GetGroupsResponseModel](https://apis.io/schemas/marginedge/public-api-get-groups-response-model/)
- [GetOrderDetailResponseModel](https://apis.io/schemas/marginedge/public-api-get-order-detail-response-model/)
- [GetOrdersResponseModel](https://apis.io/schemas/marginedge/public-api-get-orders-response-model/)
- [GetProductsResponseModel](https://apis.io/schemas/marginedge/public-api-get-products-response-model/)
- [GetVendorItemsPackagingResponseModel](https://apis.io/schemas/marginedge/public-api-get-vendor-items-packaging-response-model/)
- [GetVendorItemsResponseModel](https://apis.io/schemas/marginedge/public-api-get-vendor-items-response-model/)
- [GetVendorsResponseModel](https://apis.io/schemas/marginedge/public-api-get-vendors-response-model/)

#### JSON Structure (10)

Data models expressed in JSON Structure.

- [Public Api Get Available Restaurant Units Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-available-restaurant-units-response-model-structure/)
- [Public Api Get Categories Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-categories-response-model-structure/)
- [Public Api Get Group Categories Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-group-categories-response-model-structure/)
- [Public Api Get Groups Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-groups-response-model-structure/)
- [Public Api Get Order Detail Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-order-detail-response-model-structure/)
- [Public Api Get Orders Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-orders-response-model-structure/)
- [Public Api Get Products Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-products-response-model-structure/)
- [Public Api Get Vendor Items Packaging Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-vendor-items-packaging-response-model-structure/)
- [Public Api Get Vendor Items Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-vendor-items-response-model-structure/)
- [Public Api Get Vendors Response Model Structure](https://apis.io/json-structure/marginedge/public-api-get-vendors-response-model-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Marginedge Context](https://apis.io/jsonld/marginedge/marginedge-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Marginedge Vocabulary](https://apis.io/vocabularies/marginedge/marginedge-vocabulary/)

#### Examples (10)

Example requests and responses.

- [Public Api Get Available Restaurant Units Response Model Example](https://apis.io/examples/marginedge/public-api-get-available-restaurant-units-response-model-example/)
- [Public Api Get Categories Response Model Example](https://apis.io/examples/marginedge/public-api-get-categories-response-model-example/)
- [Public Api Get Group Categories Response Model Example](https://apis.io/examples/marginedge/public-api-get-group-categories-response-model-example/)
- [Public Api Get Groups Response Model Example](https://apis.io/examples/marginedge/public-api-get-groups-response-model-example/)
- [Public Api Get Order Detail Response Model Example](https://apis.io/examples/marginedge/public-api-get-order-detail-response-model-example/)
- [Public Api Get Orders Response Model Example](https://apis.io/examples/marginedge/public-api-get-orders-response-model-example/)
- [Public Api Get Products Response Model Example](https://apis.io/examples/marginedge/public-api-get-products-response-model-example/)
- [Public Api Get Vendor Items Packaging Response Model Example](https://apis.io/examples/marginedge/public-api-get-vendor-items-packaging-response-model-example/)
- [Public Api Get Vendor Items Response Model Example](https://apis.io/examples/marginedge/public-api-get-vendor-items-response-model-example/)
- [Public Api Get Vendors Response Model Example](https://apis.io/examples/marginedge/public-api-get-vendors-response-model-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [MarginEdge Public API](https://apis.io/collections/marginedge/open-marginedge/)
- [MarginEdge Public Categories API](https://apis.io/collections/marginedge/open-marginedge-categories-api/)
- [MarginEdge Public Categories Orders API](https://apis.io/collections/marginedge/open-marginedge-orders-api/)
- [MarginEdge Public Categories Products API](https://apis.io/collections/marginedge/open-marginedge-products-api/)
- [MarginEdge Public Categories Restaurant Units API](https://apis.io/collections/marginedge/open-marginedge-restaurant-units-api/)
- [MarginEdge Public Categories Vendors API](https://apis.io/collections/marginedge/open-marginedge-vendors-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [MarginEdge — jsonschema rules](https://apis.io/rules/marginedge/marginedge-jsonschema-spectral-rules/)
- [MarginEdge API Rules](https://apis.io/rules/marginedge/marginedge-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Marginedge Authentication](https://apis.io/security/marginedge/marginedge-authentication/)
- [Marginedge Domain Security](https://apis.io/security/marginedge/marginedge-domain-security/)
- [Marginedge Trust Center](https://apis.io/security/marginedge/marginedge-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Marginedge Plans Pricing](https://apis.io/plans/marginedge/marginedge-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Marginedge Rate Limits](https://apis.io/rate-limits/marginedge/marginedge-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Marginedge Finops](https://apis.io/finops/marginedge/marginedge-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.marginedge.com/)
- [Documentation](https://developer.marginedge.com/)
- [Pricing](https://www.marginedge.com/pricing/)
- [Support](https://help.marginedge.com/hc/en-us)
- [Blog](https://www.marginedge.com/blog)

## API Evangelist rating

**Kin Score 38.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 60.1 |
| Contract governance | 27.3 |
| Operational transparency | 5.3 |
| Developer ergonomics | 29.8 |
| Access clarity | 26.3 |

**Agent readiness 56.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/marginedge/](https://apis.io/providers/marginedge/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for MarginEdge: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/marginedge/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
