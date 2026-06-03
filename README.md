# MarginEdge (marginedge)

MarginEdge is a restaurant back-office platform that automates invoice processing, inventory, recipe costing, and bill payment, syncing daily food cost and sales data into a restaurant's accounting system. Founded in 2015, it serves over 7,000 restaurants across all 50 states. For developers, MarginEdge publishes a public API through a dedicated developer portal that lets authorized parties programmatically retrieve invoice and product data from the restaurants they are permitted to access. Typical consumers include multi-unit operators building custom reporting, accounting groups, and business intelligence providers contracting with MarginEdge customers to deliver data services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/marginedge/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant
 - Back Office
 - Invoices
 - Inventory
 - Accounting
 - Reporting

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-02

## APIs

### MarginEdge Public API

The MarginEdge Public API lets authorized developers programmatically retrieve invoice and product data from the MarginEdge restaurants they are permitted to access. It is documented through the MarginEdge developer portal and is commonly used by multi-unit operators, accounting groups, and business intelligence providers to pull operational data into custom reporting and analytics tools. The API is read-only (GET only), authenticated with an `x-api-key` header, served at `https://api.marginedge.com/public`, and pages large collections through an opaque `nextPage` cursor.

**Human URL:** [https://developer.marginedge.com/](https://developer.marginedge.com/)

#### Tags:

 - Invoices
 - Products
 - Vendors
 - Categories
 - Restaurant Units
 - Reporting

#### Properties

- [Documentation](https://developer.marginedge.com/)
- [Documentation](https://help.marginedge.com/hc/en-us/articles/28081506932499-MarginEdge-Public-API)
- [OpenAPI](openapi/marginedge-openapi.yml)
- [NaftikoCapability](capabilities/marginedge-categories.yaml)
- [NaftikoCapability](capabilities/marginedge-orders.yaml)
- [NaftikoCapability](capabilities/marginedge-products.yaml)
- [NaftikoCapability](capabilities/marginedge-restaurant-units.yaml)
- [NaftikoCapability](capabilities/marginedge-vendors.yaml)

## Common Properties

- [Website](https://www.marginedge.com/)
- [Documentation](https://developer.marginedge.com/)
- [Pricing](https://www.marginedge.com/pricing/)
- [Support](https://help.marginedge.com/hc/en-us)
- [Blog](https://www.marginedge.com/blog)
- [LinkedIn](https://www.linkedin.com/company/marginedge)
- [SpectralRules](rules/marginedge-spectral-rules.yml)
- [Vocabulary](vocabulary/marginedge-vocabulary.yml)
- [Plans](plans/marginedge-plans-pricing.yml)
- [RateLimits](rate-limits/marginedge-rate-limits.yml)
- [FinOps](finops/marginedge-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [MarginEdge Public API](openapi/marginedge-openapi.yml) — 10 operations across Orders, Products, Vendors, Categories, and Restaurant Units

### JSON Schema

10 standalone JSON Schema files extracted from the OpenAPI response models in [json-schema/](json-schema/).

### JSON Structure

10 JSON Structure representations in [json-structure/](json-structure/).

### JSON-LD

- [MarginEdge Context](json-ld/marginedge-context.jsonld) — Linked-data context mapping invoice, product, vendor, category, and restaurant-unit terms

### Examples

10 example payloads (one per response model) in [examples/](examples/).

## Capabilities

Self-contained Naftiko capabilities, one per MarginEdge business surface (OpenAPI tag). Each file inlines its `consumes` block plus a REST exposer and an MCP exposer.

| Capability | API | Tools | Persona |
|------------|-----|-------|---------|
| [Categories](capabilities/marginedge-categories.yaml) | MarginEdge Public API | 1 | Accounting Group |
| [Orders](capabilities/marginedge-orders.yaml) | MarginEdge Public API | 2 | Accounting Group |
| [Products](capabilities/marginedge-products.yaml) | MarginEdge Public API | 1 | BI Provider |
| [Restaurant Units](capabilities/marginedge-restaurant-units.yaml) | MarginEdge Public API | 3 | Multi-Unit Operator |
| [Vendors](capabilities/marginedge-vendors.yaml) | MarginEdge Public API | 3 | Accounting Group |

## Vocabulary

- [MarginEdge Vocabulary](vocabulary/marginedge-vocabulary.yml) — Unified taxonomy mapping 5 resources, 2 actions, 5 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [MarginEdge Spectral Rules](rules/marginedge-spectral-rules.yml) — 36 rules across info, servers, paths, operations, tags, parameters, responses, schemas, and security categories enforcing MarginEdge API conventions

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/marginedge-plans-pricing.yml) — All-inclusive per-location subscription ($350/location base, $500/location with Freepour); Public API included at no extra cost
- [Rate Limits](rate-limits/marginedge-rate-limits.yml) — Per-API-key access via AWS API Gateway; cursor pagination via `nextPage`
- [FinOps](finops/marginedge-finops.yml) — FOCUS-aligned per-location subscription billing model

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
