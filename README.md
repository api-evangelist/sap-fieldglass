# SAP Fieldglass (sap-fieldglass)

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
