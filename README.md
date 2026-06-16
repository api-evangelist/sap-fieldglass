# SAP Fieldglass (sap-fieldglass)

SAP Fieldglass is a cloud-based vendor management system (VMS) that enables organizations to manage their contingent workforce, services procurement, and external talent. It provides REST APIs for managing work orders, job postings, statements of work, worker profiles, time sheets, invoices, and external talent across more than 165 countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/apis.yml)

## Tags

- Contingent Workforce
- External Talent
- Human Capital Management
- Services Procurement
- Statements of Work
- Vendor Management
- Workforce Management

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### SAP Fieldglass REST API

Core REST API for SAP Fieldglass that allows clients to send and receive integrated data directly against the application. Supports upload (POST/PUT) and download (GET) of data in JSON and CSV formats for contingent workforce and services procurement management.

- **Human URL:** [https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION](https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION)
- **Base URL:** `https://www.fieldglass.net/api`

#### Tags

- Contingent Workforce
- Integration
- REST
- Work Orders

#### Properties

- [Documentation](https://help.sap.com/doc/a5fdbd31ebe94832aef0eb79066a8087/cloud/en-US/SAPFieldglassRESTAPIIntegrationGeneralReferenceGuide.pdf)
- [Hub](https://api.sap.com/package/FieldglassAPI/rest)
- [Authentication](https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION)

### SAP Fieldglass Approval API

Enables programmatic approval workflows for contingent workforce and services procurement documents including work orders, statements of work, and time sheets within SAP Fieldglass.

- **Human URL:** [https://api.sap.com/api/approvals/overview](https://api.sap.com/api/approvals/overview)
- **Base URL:** `https://www.fieldglass.net/api/approvals`

#### Tags

- Approvals
- Workflows
- Work Orders

#### Properties

- [Documentation](https://api.sap.com/api/approvals/overview)
- [Hub](https://api.sap.com/api/approvals/resource)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/openapi/sap-fieldglass-approval-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### SAP Fieldglass OData-Based Analytic API

OData-based analytic API for SAP Fieldglass providing access to business analytics, reporting data, and operational metrics for contingent workforce and services procurement management.

- **Human URL:** [https://api.sap.com/api/datahub/overview](https://api.sap.com/api/datahub/overview)
- **Base URL:** `https://www.fieldglass.net/api/datahub`

#### Tags

- Analytics
- Business Intelligence
- OData
- Reporting

#### Properties

- [Documentation](https://api.sap.com/api/datahub/overview)
- [Hub](https://api.sap.com/api/datahub/resource)
- [Documentation](https://help.sap.com/doc/3921dd506108442f9ddc6350cb0628c3/cloud/en-US/SAPFieldglassBusinessAnalyticsAPISpecifications.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/openapi/sap-fieldglass-odata-analytic-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### SAP Fieldglass Identity Management API

SCIM-based identity management API for SAP Fieldglass enabling user provisioning, deprovisioning, and lifecycle management for workers, buyers, and suppliers across the contingent workforce platform.

- **Human URL:** [https://api.sap.com/api/scim/overview](https://api.sap.com/api/scim/overview)
- **Base URL:** `https://www.fieldglass.net/api/scim`

#### Tags

- Identity Management
- Provisioning
- SCIM
- User Management

#### Properties

- [Documentation](https://api.sap.com/api/scim/overview)
- [Hub](https://api.sap.com/package/FieldglassAPI/rest)

### SAP Fieldglass Pick List Value Download API

Retrieves configurable pick list values from SAP Fieldglass for use in integration and data validation, including worker types, cost centers, regions, and other reference data.

- **Human URL:** [https://api.sap.com/api/pickListValueDownload/resource](https://api.sap.com/api/pickListValueDownload/resource)
- **Base URL:** `https://www.fieldglass.net/api/pickListValues`

#### Tags

- Configuration
- Pick Lists
- Reference Data

#### Properties

- [Documentation](https://api.sap.com/api/pickListValueDownload/resource)
- [Hub](https://api.sap.com/package/FieldglassAPI/rest)

### SAP Fieldglass Background Check API

Integrates background check services with SAP Fieldglass work orders, enabling posting of background check results and status updates for contingent workers tied to specific work order IDs.

- **Human URL:** [https://help.sap.com/doc/7baf3b6dbe4d4495a0e2afa668c70a76/cloud/en-US/SAPFieldglassBackgroundCheckAPITechnicalSpecifications.pdf](https://help.sap.com/doc/7baf3b6dbe4d4495a0e2afa668c70a76/cloud/en-US/SAPFieldglassBackgroundCheckAPITechnicalSpecifications.pdf)
- **Base URL:** `https://www.fieldglass.net/api/backgroundCheck`

#### Tags

- Background Checks
- Compliance
- Work Orders
- Workers

#### Properties

- [Documentation](https://help.sap.com/doc/7baf3b6dbe4d4495a0e2afa668c70a76/cloud/en-US/SAPFieldglassBackgroundCheckAPITechnicalSpecifications.pdf)
- [Hub](https://api.sap.com/package/FieldglassAPI/rest)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/openapi/sap-fieldglass-background-check-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### SAP Fieldglass Audit Trail API

Provides access to the audit trail of changes and actions performed in SAP Fieldglass, enabling compliance tracking, change history retrieval, and activity monitoring for contingent workforce records.

- **Human URL:** [https://api.sap.com/package/FieldglassAPI/rest](https://api.sap.com/package/FieldglassAPI/rest)
- **Base URL:** `https://www.fieldglass.net/api/auditTrail`

#### Tags

- Audit
- Compliance
- Monitoring

#### Properties

- [Hub](https://api.sap.com/package/FieldglassAPI/rest)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/openapi/sap-fieldglass-audit-trail-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### SAP Fieldglass Business Analytics API

REST API for accessing SAP Fieldglass business analytics reports, providing structured reporting data for spend, headcount, and operational metrics related to contingent workforce management.

- **Human URL:** [https://api.sap.com/package/FieldglassAPI/rest](https://api.sap.com/package/FieldglassAPI/rest)
- **Base URL:** `https://www.fieldglass.net/api/report`

#### Tags

- Analytics
- Business Intelligence
- Reporting

#### Properties

- [Hub](https://api.sap.com/package/FieldglassAPI/rest)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sap-fieldglass/refs/heads/main/openapi/sap-fieldglass-business-analytics-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.sap.com/products/hcm/contingent-workforce-management.html)
- [Documentation](https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION)
- [Git Hub Org](https://github.com/SAP)
- [LinkedIn](https://www.linkedin.com/company/sapfieldglass/)
- [Blog](https://community.sap.com/t5/spend-management-blog-posts-by-sap/bg-p/spend-management-blog-posts-by-sap)
- [Pricing](https://www.sap.com/products/hcm/contingent-workforce-management/pricing.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [X (Twitter)](https://x.com/sapfieldglass)
- [Plans](plans/sap-fieldglass-plans-pricing.yml)
- [Rate Limits](rate-limits/sap-fieldglass-rate-limits.yml)
- [Fin Ops](finops/sap-fieldglass-finops.yml)
- [Authentication](https://help.sap.com/docs/SAP_FIELDGLASS_INTEGRATION)
- [Hub](https://api.sap.com/package/FieldglassAPI/overview)
- [Hub](https://api.sap.com/package/FieldglassAPI/rest)
- [Community](https://pages.community.sap.com/topics/spend-management/fieldglass)
- [Support](https://help.sap.com/docs/SAP_Fieldglass)
- [Terms of Service](https://www.fieldglass.com/terms-and-conditions)
- [Privacy Policy](https://www.fieldglass.com/privacy-policy)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
