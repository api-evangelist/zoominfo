# ZoomInfo GraphQL Schema

## Overview

This conceptual GraphQL schema represents the ZoomInfo B2B data and intelligence API. ZoomInfo provides programmatic access to its contact database, company intelligence, intent signals, scoops, news, technology tracking, corporate hierarchy, and enrichment capabilities. The schema is derived from the ZoomInfo REST API surface at https://api-docs.zoominfo.com and the developer portal at https://developer.zoominfo.com.

## Schema Source

- Developer Portal: https://developer.zoominfo.com
- API Reference: https://api-docs.zoominfo.com
- Authentication Docs: https://api-docs.zoominfo.com/#authentication
- OpenAPI Spec: openapi/zoominfo-openapi.yml

## Type Summary

The schema defines the following named types:

| Type | Description |
|------|-------------|
| `Contact` | A business professional with job, company, and contact information |
| `ContactDetails` | Aggregated contact reach data: emails, phones, LinkedIn |
| `ContactEmail` | A single email address associated with a contact |
| `ContactPhone` | A single phone number associated with a contact |
| `ContactLinkedIn` | LinkedIn profile reference for a contact |
| `PersonDetails` | Extended person record with employment history and education |
| `DirectDial` | Verified direct-dial phone number for a contact |
| `MobilePhone` | Mobile phone number for a contact |
| `EmailAddress` | Standalone email address with deliverability metadata |
| `EmploymentHistory` | Historical employment record for a person |
| `Education` | Educational background entry |
| `EducationDegree` | Degree type and level within an education record |
| `RecommendedContact` | A related contact suggested by ZoomInfo's matching engine |
| `Company` | A business entity with firmographic and intelligence data |
| `CompanyDetails` | Full enriched company record including financials and hierarchy |
| `CompanySize` | Employee count and growth metrics for a company |
| `CompanyRevenue` | Revenue figures and ranges for a company |
| `CompanyIndustry` | Industry classification data for a company |
| `CompanyType` | Public/private/non-profit classification for a company |
| `CompanySICCode` | Standard Industrial Classification code for a company |
| `CompanyNAICS` | North American Industry Classification System code |
| `CompanyRanking` | Industry or Forbes-style ranking for a company |
| `Competitor` | A competing company in the same market segment |
| `SubUnitTypeInfo` | A division or sub-unit within a corporate hierarchy |
| `Website` | Website URL and domain information |
| `Technology` | A technology product used by a company |
| `TechDetails` | Extended technology record with detection history |
| `TechCategory` | Category classification for a technology product |
| `TechVendor` | Vendor information for a technology product |
| `TechAttribute` | Key-value attribute on a technology record |
| `Funding` | Aggregated funding information for a company |
| `FundingRound` | A single funding round with amount, date, and investors |
| `FundingAmount` | A monetary value with currency |
| `Investor` | An investor that participated in a funding round |
| `InvestorDetails` | Extended investor record with type and portfolio info |
| `FundingStage` | Stage label for a funding round (e.g., Series A, Seed) |
| `News` | A news article related to a company or contact |
| `NewsDetails` | Extended news record with full text and sentiment |
| `NewsSource` | Publication metadata for a news article |
| `Location` | A geographic address with coordinates |
| `LocationDetails` | Extended location record with company association |
| `HQ` | Headquarters address for a company |
| `AdditionalLocation` | A non-headquarters office location for a company |
| `LocationMatch` | Output from a location enrichment call |
| `SearchQuery` | Input parameters for a search operation |
| `SearchFilter` | A single field filter applied to a search |
| `SearchResults` | Generic paginated result set from a search |
| `ContactResults` | Paginated contact search results |
| `CompanyResults` | Paginated company search results |
| `PersonResults` | Paginated person search results |
| `Enrich` | Configuration for an enrichment request |
| `EnrichDetails` | Input parameters for an enrichment operation |
| `EnrichInput` | A single key-value input field for enrichment matching |
| `EnrichResult` | Output from an enrichment operation |
| `EnrichedRecord` | A single matched and enriched record |
| `MatchReason` | Explanation of why a record matched an enrichment input |
| `BulkEnrich` | Configuration for a bulk enrichment job |
| `BulkEnrichRecord` | A single input record in a bulk enrichment job |
| `BulkEnrichResults` | Output from a completed bulk enrichment job |
| `BulkJobStatus` | Status of a submitted bulk processing job |
| `Scoop` | A business intelligence scoop about a company |
| `ScoopDetails` | Extended scoop record with source and context |
| `ScoopType` | Classification type for a scoop |
| `Intent` | Buyer intent signal for a company and topic set |
| `IntentDetails` | Extended intent record with weekly trend data |
| `IntentTopic` | A single intent topic with score and signal history |
| `IntentDataPoint` | A weekly data point in an intent trend series |
| `DomainLookup` | Input and output for resolving a domain to a company |
| `AudienceDetails` | An audience definition built from ZoomInfo segments |
| `Segment` | A saved segment or filter set for targeting |
| `Integration` | A configured CRM or marketing platform integration |
| `IntegrationConfig` | Configuration details for an integration |
| `FieldMapping` | A field mapping rule within an integration configuration |
| `APIKey` | An API key credential with rate limit metadata |
| `Token` | A JWT bearer token returned from authentication |
| `RateLimit` | Rate limiting metadata for the current API key |
| `PageInfo` | Pagination metadata for a result set |
| `Webhook` | A registered webhook subscription |
| `WebhookDeliveryStats` | Delivery success and failure counts for a webhook |
| `ComplianceRecord` | GDPR and privacy compliance data for a person |
| `FamilyTree` | Corporate hierarchy showing parent and subsidiary companies |
| `CompanyNode` | A node in a corporate hierarchy tree |
| `OrgChartNode` | A node in a company organizational chart |
| `SocialMediaURLs` | Social media profile links for a company or contact |
| `ExternalURL` | A labeled external URL attached to a record |
| `Hashtag` | A hashtag or topic tag associated with a company |
| `DescriptionList` | A reference list of enumerated values |
| `DescriptionListItem` | A single item in a reference description list |
| `UsageStats` | API usage and credit consumption metrics |
| `EndpointUsage` | Per-endpoint breakdown of API usage |

## Key Capabilities

### Authentication

ZoomInfo uses username/password authentication to obtain a JWT bearer token. The token is passed in subsequent API calls.

```graphql
mutation {
  authenticate(username: "user@example.com", password: "secret") {
    accessToken
    expiresIn
    tokenType
  }
}
```

### Contact Search

Search for contacts using filters on job title, company, department, management level, geography, and more.

```graphql
query {
  searchContacts(query: {
    filters: [
      { field: "jobTitle", value: "VP of Sales" },
      { field: "companyRevenue", operator: "GTE", value: "10000000" }
    ]
    pageSize: 25
  }) {
    totalResults
    data {
      id
      firstName
      lastName
      jobTitle
      contactDetails {
        emails { address { address } }
        directDial { number }
      }
      company { id name }
    }
  }
}
```

### Company Enrichment

Enrich a company record using domain or company name as input.

```graphql
query {
  enrichCompany(input: {
    enrichType: "company"
    inputData: [{ field: "website", value: "salesforce.com" }]
    outputFields: ["id", "name", "revenue", "employeeCount", "technologies"]
  }) {
    matchStatus
    data {
      companyData {
        companyDetails {
          name
          revenue { amount currency }
          size { employeeCount employeeCountRange }
          technologies { name category { categoryName } }
        }
      }
    }
  }
}
```

### Intent Data

Retrieve buyer intent signals for companies researching specific topics.

```graphql
query {
  searchIntent(query: {
    filters: [
      { field: "topics", values: ["CRM Software", "Sales Automation"] },
      { field: "scoreThreshold", value: "70" }
    ]
  }) {
    data {
      ... on Intent {
        companyId
        companyName
        score
        topics { topicName score trend weeklySignals }
      }
    }
  }
}
```

### Bulk Operations

Submit bulk contact or company enrichment jobs for large-scale data processing.

```graphql
mutation {
  submitBulkContactEnrich(input: {
    jobType: "contactEnrich"
    inputData: [
      { recordId: "rec001", inputFields: [{ field: "email", value: "jane@acme.com" }] }
    ]
    outputFields: ["firstName", "lastName", "jobTitle", "directDial"]
    notificationUrl: "https://myapp.example.com/webhooks/zoominfo"
  }) {
    jobId
    status
    totalRecords
  }
}
```

### Webhooks

Register webhooks to receive real-time notifications about data changes.

```graphql
mutation {
  createWebhook(input: {
    name: "Intent Alerts"
    url: "https://myapp.example.com/webhooks/intent"
    events: ["intent.score.increased", "intent.new.topic"]
    secret: "webhook-signing-secret"
    isActive: true
  }) {
    webhookId
    status
    createdAt
  }
}
```

## Notes

- This is a conceptual schema. ZoomInfo does not currently publish an official GraphQL endpoint; this schema represents the API surface translated into GraphQL types.
- Field availability depends on the ZoomInfo subscription tier and licensed data packages.
- Rate limits and credit consumption vary by endpoint and subscription level; see https://api-docs.zoominfo.com/rate-limits.
- Bulk job results are delivered asynchronously; poll `bulkJobStatus` or use a webhook to detect completion.
- All operations require a valid bearer token obtained via the `authenticate` mutation.
