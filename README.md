# Sisense

Sisense is a business intelligence and analytics platform that enables organizations to build and embed analytics into applications and workflows. It provides REST APIs for managing dashboards, data models (Elasticubes and live models), users, groups, data security rules, and builds. The platform supports both extract-based and live data model architectures with comprehensive programmatic administration capabilities.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sisense/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-02

## APIs

### Sisense REST API v1

The Sisense REST API v1 provides programmatic access to dashboards, users, groups, Elasticubes, data security rules, and builds. Authentication uses Bearer tokens obtained via the login endpoint or User Profiles settings.

**Human URL:** https://developer.sisense.com/guides/restApi/v1/
**Base URL:** https://your-sisense-host/api/v1

#### Properties

- [Documentation](https://developer.sisense.com/guides/restApi/v1/)
- [OpenAPI](openapi/sisense-rest-api-openapi.yml)

### Sisense REST API v2

The Sisense REST API v2 provides access to Datamodels (the modern replacement for Elasticubes), builds, and advanced data model management.

**Human URL:** https://developer.sisense.com/guides/restApi/v2/

#### Properties

- [Documentation](https://developer.sisense.com/guides/restApi/v2/)

### Sisense User and Role Management API (RBAC)

Enables administrators to manage users, roles, and permissions programmatically with role-based access control.

**Human URL:** https://dtdocs.sisense.com/article/user-and-role-management-api-rbac

#### Properties

- [Documentation](https://dtdocs.sisense.com/article/user-and-role-management-api-rbac)

## OpenAPI Specifications

- [Sisense REST API](openapi/sisense-rest-api-openapi.yml)

## Capabilities

- [Analytics Administration](capabilities/analytics-administration.yaml) - Unified dashboard, user, group, Elasticube, and data security management workflow

### Shared Definitions

- [Sisense](capabilities/shared/sisense.yaml)

## Rules

- [Sisense Rules](rules/sisense-rules.yml)

## JSON Schemas

- [Dashboard Schema](json-schema/sisense-dashboard-schema.json)
- [User Schema](json-schema/sisense-user-schema.json)

## JSON Structures

- [Dashboard Structure](json-structure/sisense-dashboard-structure.json)

## JSON-LD

- [Sisense Context](json-ld/sisense-context.jsonld)

## Examples

- [List Dashboards](examples/sisense-list-dashboards-example.json)
- [Create User](examples/sisense-create-user-example.json)

## Vocabulary

- [Sisense Vocabulary](vocabulary/sisense-vocabulary.yml)

## Common Links

- **Website:** https://www.sisense.com/
- **Developer Portal:** https://developer.sisense.com/
- **Documentation:** https://docs.sisense.com/
- **Pricing:** https://www.sisense.com/pricing/
- **Blog:** https://www.sisense.com/blog/
- **GitHub:** https://github.com/sisense
- **Community:** https://community.sisense.com/
- **Support:** https://support.sisense.com/
- **Terms of Service:** https://www.sisense.com/legal/terms-of-service/
- **Privacy Policy:** https://www.sisense.com/legal/privacy-policy/

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
