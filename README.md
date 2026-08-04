# Sisense (sisense)

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

Sisense is a business intelligence and analytics platform that enables organizations to build and embed analytics into applications and workflows. It provides REST APIs for managing dashboards, data models (Elasticubes and live models), users, groups, data security rules, and builds. The platform supports both extract-based and live data model architectures with comprehensive programmatic administration capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Data Models
- Embedded Analytics

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Sisense REST API v1

The Sisense REST API v1 provides programmatic access to dashboards, users, groups, Elasticubes, data security rules, and builds. It supports both extract-based Elasticube models and live data models. Authentication uses Bearer tokens obtained via the login endpoint or from User Profiles settings.

- **Human URL:** [https://developer.sisense.com/guides/restApi/v1/](https://developer.sisense.com/guides/restApi/v1/)
- **Base URL:** `https://your-sisense-host/api/v1`

#### Tags

- Dashboards
- Users
- Groups
- Elasticubes
- Data Models
- Analytics

#### Properties

- [Documentation](https://developer.sisense.com/guides/restApi/v1/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/openapi/sisense-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sisense-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sisense-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sisense REST API v2

The Sisense REST API v2 provides access to Datamodels (the v2 replacement for Elasticubes), builds, and advanced data model management capabilities including schema management, field configuration, and live data model operations.

- **Human URL:** [https://developer.sisense.com/guides/restApi/v2/](https://developer.sisense.com/guides/restApi/v2/)
- **Base URL:** `https://your-sisense-host/api/v2`

#### Tags

- Data Models
- Builds
- Analytics

#### Properties

- [Documentation](https://developer.sisense.com/guides/restApi/v2/)
- [Postman Collection](collections/sisense-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sisense-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sisense User and Role Management API

The Sisense User and Role Management API (RBAC) enables administrators to manage users, roles, and permissions programmatically. Available on select plans through contact with Customer Success Manager.

- **Human URL:** [https://dtdocs.sisense.com/article/user-and-role-management-api-rbac](https://dtdocs.sisense.com/article/user-and-role-management-api-rbac)
- **Base URL:** `https://your-sisense-host/api/v1`

#### Tags

- Users
- Roles
- RBAC
- Identity

#### Properties

- [Documentation](https://dtdocs.sisense.com/article/user-and-role-management-api-rbac)
- [Postman Collection](collections/sisense-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sisense-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sisense)
- [Website](https://www.sisense.com/)
- [Developer Portal](https://developer.sisense.com/)
- [Documentation](https://docs.sisense.com/)
- [Pricing](https://www.sisense.com/pricing/)
- [Blog](https://www.sisense.com/blog/)
- [Git Hub Org](https://github.com/sisense)
- [Community](https://community.sisense.com/)
- [Terms of Service](https://www.sisense.com/legal/terms-of-service/)
- [Privacy Policy](https://www.sisense.com/legal/privacy-policy/)
- [Support](https://support.sisense.com/)
- [Integrations](https://www.sisense.com/marketplace/)
- [L L Ms Txt](https://developer.sisense.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
