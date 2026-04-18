# ZoomInfo (zoominfo)
ZoomInfo is a leading B2B contact database and sales intelligence platform that provides detailed company and contact information, helping sales and marketing teams identify and connect with potential customers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - B2B, B2B Data, Company Data, Contact Database, Contacts, Data, Lead Generation, Marketing Intelligence, Sales Intelligence

## Timestamps

- **Created:** 2025-02-09
- **Modified:** 2026-04-18

## APIs

### ZoomInfo
The ZoomInfo API is a set of HTTPS endpoints you can use to programmatically retrieve and integrate ZoomInfo data into your existing technology stack and workflows.

**Human URL:** [https://www.zoominfo.com/](https://www.zoominfo.com/)

#### Tags:

 - Authentication, Contact Search, Company Search, Contact Enrich, Company Enrich, Intent Search, News Search, Scoop Search, Technology Enrich, Webhooks, Bulk Operations, WebSights, Compliance, Lookup, Corporate Hierarchy, Org Chart

#### Properties

- [Documentation](https://www.zoominfo.com/solutions/data-as-a-service/enterprise-api)
- [OpenAPI](openapi/zoominfo-openapi.yml)
- [Python SDK](https://github.com/Zoominfo/api-auth-python-client)
- [Java SDK](https://github.com/Zoominfo/api-auth-java-client)
- [Node.js SDK](https://github.com/Zoominfo/api-auth-nodejs-client)
- [C# SDK](https://github.com/Zoominfo/api-auth-csharp-client)

## Common Properties

- [Pricing](https://www.zoominfo.com/pricing)
- [Blog](https://pipeline.zoominfo.com/)
- [Customers](https://www.zoominfo.com/about/case-studies)
- [Partners](https://www.zoominfo.com/partner)
- [Support](https://www.zoominfo.com/about/help-center)
- [FAQ](https://www.zoominfo.com/faqs/business)
- [Glossary](https://pipeline.zoominfo.com/glossary)
- [Authentication](https://api-docs.zoominfo.com/#authentication)
- [GettingStarted](https://api-docs.zoominfo.com/getting-started)
- [RateLimits](https://api-docs.zoominfo.com/rate-limits)
- [TermsOfService](https://www.zoominfo.com/about/terms-of-service)
- [PrivacyPolicy](https://www.zoominfo.com/about/privacy-policy)
- [StatusPage](https://status.zoominfo.com)
- [DeveloperPortal](https://api-docs.zoominfo.com)
- [APIReference](https://api-docs.zoominfo.com)
- [GitHubOrganization](https://github.com/Zoominfo)
- [MCP Server](https://github.com/Zoominfo/zoominfo-mcp-plugin)

## Features

| Name | Description |
|------|-------------|
| Contact Search | Search for contacts by job title, company, location, industry, and other criteria |
| Company Search | Search for companies by industry, revenue, employee count, location, and technology stack |
| Contact Enrichment | Enrich contact records with verified email addresses, phone numbers, and professional details |
| Company Enrichment | Enrich company records with firmographic data including revenue, employee count, and technographics |
| Intent Data | Identify companies showing buying intent signals based on content consumption patterns |
| Scoops | Access business intelligence scoops about company changes, hiring, and strategic initiatives |
| News Intelligence | Search and enrich news articles related to companies and contacts |
| Technology Tracking | Identify technologies used by companies across their tech stack |
| Corporate Hierarchy | Map organizational structures including parent companies, subsidiaries, and divisions |
| Org Chart | Access organizational chart data showing reporting relationships within companies |
| Webhooks | Real-time notifications for data changes and updates via webhook subscriptions |
| Bulk Operations | Submit batch search and enrichment jobs for large-scale data processing |
| WebSights | Identify website visitors by IP address and enrich with company information |
| Compliance | Access compliance data to support GDPR and privacy regulation requirements |

## Use Cases

| Name | Description |
|------|-------------|
| Sales Prospecting | Identify and prioritize ideal prospects using firmographic and intent data to build targeted sales pipelines |
| Lead Enrichment | Automatically enrich inbound leads with verified contact and company data for faster qualification |
| Account-Based Marketing | Build targeted account lists and personalize outreach using detailed company intelligence |
| CRM Data Hygiene | Cleanse and update CRM records with accurate contact information and company details |
| Market Research | Analyze market segments, technology adoption, and competitive landscapes using company data |
| Competitive Intelligence | Monitor competitor activities, technology changes, and strategic moves through scoops and news |
| Buyer Intent Analysis | Identify accounts actively researching solutions in your category based on intent signals |
| Website Visitor Identification | Convert anonymous website traffic into identified company accounts using IP enrichment |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Native integration to enrich and sync contact and company data with Salesforce CRM |
| HubSpot | Seamless integration to push enriched data into HubSpot CRM and marketing automation |
| Microsoft Dynamics 365 | Integration to enrich records and sync data with Microsoft Dynamics CRM |
| Marketo | Marketing automation integration for lead enrichment and scoring with Marketo |
| Outreach | Sales engagement platform integration for enriched prospect data in Outreach sequences |
| Salesloft | Integration to power Salesloft cadences with verified contact information |
| Slack | Notifications and alerts for intent signals and data updates delivered to Slack channels |
| Snowflake | Data sharing integration to access ZoomInfo data directly in Snowflake data warehouse |
| Google Ads | Audience targeting integration to reach ideal prospects with Google advertising campaigns |
| LinkedIn | Integration to match and enrich LinkedIn profile data with ZoomInfo intelligence |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ZoomInfo OpenAPI](openapi/zoominfo-openapi.yml)

### JSON Schema

84 schema files extracted from ZoomInfo API components. See [json-schema/](json-schema/) for all files.

### JSON Structure

84 JSON Structure files converted from JSON Schema. See [json-structure/](json-structure/) for all files.

### JSON-LD

- [ZoomInfo Context](json-ld/zoominfo-context.jsonld) -- 84 types, 117 properties

### Examples

84 example JSON files generated from JSON Schema. See [examples/](examples/) for all files.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ZoomInfo API](capabilities/shared/zoominfo-api.yaml) -- 35 operations for B2B data intelligence

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Sales Prospecting](capabilities/sales-prospecting.yaml) | ZoomInfo API | 10 | Sales Representative |
| [Data Enrichment](capabilities/data-enrichment.yaml) | ZoomInfo API | 15 | Data Operations Analyst |

## Vocabulary

- [ZoomInfo Vocabulary](vocabulary/zoominfo-vocabulary.yaml) -- Unified taxonomy mapping 15 resources, 12 actions, 2 workflows, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [ZoomInfo Spectral Rules](rules/zoominfo-spectral-rules.yml) -- 35 rules across 10 categories enforcing ZoomInfo API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
