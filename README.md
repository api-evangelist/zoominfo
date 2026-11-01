# ZoomInfo

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

ZoomInfo is a B2B go-to-market intelligence platform whose contact and company database, buyer-intent signals, scoops and news feeds are sold to sales, marketing, operations and recruiting teams. Its API estate is mid-migration: the legacy Enterprise API on api.zoominfo.com is documented as deprecating, while the current GTM API on api.zoominfo.com/gtm ships six published OpenAPI specifications covering data, Copilot, GTM Studio, marketing, agents and platform. ZoomInfo also operates a hosted, OAuth-gated Model Context Protocol server at mcp.zoominfo.com and publishes 35 agent skills and a first-party CLI that talks to that MCP server rather than to REST.

**Areas:** B2B · B2B Data · Company Data · Contact Database · Contacts · Data · Lead Generation · Marketing Intelligence · Sales Intelligence · Intent Data · Go-To-Market · Data Enrichment

## ZoomInfo on APIs.io

Everything profiled for ZoomInfo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/zoominfo/](https://apis.io/providers/zoominfo/)** — or go straight to one of the APIs or properties below.

### APIs (42)

- [ZoomInfo Authentication API](https://apis.io/apis/zoominfo/zoominfo-authentication-api/) — The ZoomInfo API authenticates client access requests using a JSON Web Token (JWT). A JWT is a string that is generated by the server for the client that…
- [ZoomInfo Bulk API](https://apis.io/apis/zoominfo/zoominfo-bulk-api/) — Use the Bulk APIs to search, retrieve, and enrich large ZoomInfo company and contact datasets through asynchronous batch processes. With 20x more records…
- [ZoomInfo Company Enrich API](https://apis.io/apis/zoominfo/zoominfo-company-enrich-api/) — Use [Company Enrich](#59a59d9e-7eb9-44fa-904a-f10f9ab7c5fd) to retrieve company detail using valid query parameters. A Company Enrich request requires you…
- [ZoomInfo Company Location Enrich API](https://apis.io/apis/zoominfo/zoominfo-company-location-enrich-api/) — Use [Company Location Enrich](#2b221ad0-f6c2-40cb-b721-6513e90afd8d) to retrieve company location detail using valid query parameters. Refer to the examples…
- [ZoomInfo Company Master Data Enrich API](https://apis.io/apis/zoominfo/zoominfo-company-master-data-enrich-api/) — The new [Company Master Data Enrich](#8b6cffe4-cb34-44ab-ad5d-1953d372ffd3) endpoint brings together ZoomInfo firmographic data with the EverString…
- [ZoomInfo Company Search API](https://apis.io/apis/zoominfo/zoominfo-company-search-api/) — Use [Company Search](#4506f0ad-9147-4016-991f-ce8ef6700f07) to retrieve company data using valid query parameters. * To build your request, retrieve a list…
- [ZoomInfo Compliance API](https://apis.io/apis/zoominfo/zoominfo-compliance-api-api/) — Use the Compliance endpoints to request and return data related to data privacy and opt-out compliance for contacts stored in the ZoomInfo database.
- [ZoomInfo Contact Enrich API](https://apis.io/apis/zoominfo/zoominfo-contact-enrich-api/) — Use [Contact Enrich](#c145dd01-eb54-4fc2-bbdb-9edc04b7ea1b) to retrieve contact detail using valid query parameters. A Contact Enrich request requires you…
- [ZoomInfo Contact Search API](https://apis.io/apis/zoominfo/zoominfo-contact-search-api/) — Use [Contact Search](#2e5121fd-df42-41a4-95d6-0e8f24eebd92) to retrieve contacts using valid query parameters. * To build your request, retrieve a list of…
- [ZoomInfo Corporate Hierarchy Enrich API](https://apis.io/apis/zoominfo/zoominfo-corporate-hierarchy-enrich-api/) — Use [Corporate Hierarchy Enrich](#585acff6-f231-4109-b818-b2ff586c18d3) to retrieve corporate hierarchy detail using valid query parameters. A Corporate…
- [ZoomInfo Hashtags Enrich API](https://apis.io/apis/zoominfo/zoominfo-hashtags-enrich-api/) — Use [Hashtags Enrich](#886fb5cc-b587-4f26-bd68-892798d45ffe) to retrieve company hashtags using valid query parameters. A Hashtags Enrich request requires…
- [ZoomInfo Intent Enrich API](https://apis.io/apis/zoominfo/zoominfo-intent-enrich-api/) — Use [Intent Enrich](#c1e5300d-8ffb-40f0-b899-be98f884e505) to retrieve intent data using valid query parameters. Refer to the examples provided to build a…
- [ZoomInfo Intent Search API](https://apis.io/apis/zoominfo/zoominfo-intent-search-api/) — Use [Intent Search](#93f940a4-4381-49dd-8fbc-42cbc75a7a39) to retrieve Intent-related data using valid query parameters. * To build your request, retrieve a…
- [ZoomInfo Lookup API](https://apis.io/apis/zoominfo/zoominfo-lookup-api/) — This folder contains a series of lookup endpoints.
- [ZoomInfo Monitoring API/Webhooks API](https://apis.io/apis/zoominfo/zoominfo-monitoring-api-webhooks-api/) — ZoomInfo data is highly dynamic, with contacts, companies and related data being constantly updated in real-time in our database. Naturally, our clients…
- [ZoomInfo News Enrich API](https://apis.io/apis/zoominfo/zoominfo-news-enrich-api/) — Use [News Enrich](#a04f60d9-353e-4eb1-9c37-0539ee6b8d13) to retrieve news data using valid query parameters. Refer to the examples provided to build a valid…
- [ZoomInfo News Search API](https://apis.io/apis/zoominfo/zoominfo-news-search-api/) — Use [News Search](#4c4c979b-4495-4a17-8925-7d00c52c7e19) to retrieve news-related data using valid query parameters. * To build your request, retrieve a…
- [ZoomInfo OrgChart Enrich API](https://apis.io/apis/zoominfo/zoominfo-orgchart-enrich-api/) — Use [Org Chart Enrich](#763b3c10-41d1-4d52-9775-1712f712202e) to retrieve org chart detail using valid query parameters. Refer to the examples provided to…
- [ZoomInfo Scoop Enrich API](https://apis.io/apis/zoominfo/zoominfo-scoop-enrich-api/) — Use [Scoop Enrich](#545c603a-fbe5-48b6-b4b4-bdca626fead0) to retrieve Scoop data using valid query parameters. Refer to the examples provided to build a…
- [ZoomInfo Scoop Search API](https://apis.io/apis/zoominfo/zoominfo-scoop-search-api/) — Use [Scoop Search](#3099d72f-6857-4432-89c2-736410680e60) to retrieve scoop-related data using valid query parameters. * To build your request, retrieve a…
- [ZoomInfo Technology Enrich API](https://apis.io/apis/zoominfo/zoominfo-technology-enrich-api/) — Use [Technology Enrich](#9fc40c02-fe95-448f-a6f4-e903c85c81a9) to retrieve company technology detail using valid query parameters. Refer to the examples…
- [ZoomInfo Usage API](https://apis.io/apis/zoominfo/zoominfo-usage-api/) — You can use the Usage endpoint to find what your current API usage and limits are.
- [ZoomInfo WebSights API](https://apis.io/apis/zoominfo/zoominfo-websights-api-api/) — The Websights API identifies anonymous website traffic by resolving IP addresses (IPv4 & IPv6) to return company and ISP profiles and IP geolocation…
- [ZoomInfo Account Summary API](https://apis.io/apis/zoominfo/zoominfo-account-summary-api/) — The Account Summary API from ZoomInfo — 2 operation(s) for account summary.
- [ZoomInfo Agent Teams API](https://apis.io/apis/zoominfo/zoominfo-agent-teams-api/) — The Agent Teams API from ZoomInfo — 4 operation(s) for agent teams.
- [ZoomInfo Audiences API](https://apis.io/apis/zoominfo/zoominfo-audiences-api/) — The Audiences API from ZoomInfo — 20 operation(s) for audiences.
- [ZoomInfo Customer Buyer Persona API](https://apis.io/apis/zoominfo/zoominfo-customer-buyer-persona-api/) — The Customer Buyer Persona API from ZoomInfo — 4 operation(s) for customer buyer persona.
- [ZoomInfo Customer Competitors API](https://apis.io/apis/zoominfo/zoominfo-customer-competitors-api/) — The Customer Competitors API from ZoomInfo — 4 operation(s) for customer competitors.
- [ZoomInfo Customer Settings API](https://apis.io/apis/zoominfo/zoominfo-customer-settings-api/) — The Customer Settings API from ZoomInfo — 1 operation(s) for customer settings.
- [ZoomInfo Engagements API](https://apis.io/apis/zoominfo/zoominfo-engagements-api/) — The Engagements API from ZoomInfo — 2 operation(s) for engagements.
- [ZoomInfo Enrich API](https://apis.io/apis/zoominfo/zoominfo-enrich-api/) — The Enrich API from ZoomInfo — 9 operation(s) for enrich.
- [ZoomInfo Entities API](https://apis.io/apis/zoominfo/zoominfo-entities-api/) — The entities API from ZoomInfo — 3 operation(s) for entities.
- [ZoomInfo Entitlements API](https://apis.io/apis/zoominfo/zoominfo-entitlements-api/) — The Entitlements API from ZoomInfo — 1 operation(s) for entitlements.
- [ZoomInfo Ideal Customer Profile API](https://apis.io/apis/zoominfo/zoominfo-ideal-customer-profile-api/) — The Ideal Customer Profile API from ZoomInfo — 4 operation(s) for ideal customer profile.
- [ZoomInfo Insights API](https://apis.io/apis/zoominfo/zoominfo-insights-api/) — The Insights API from ZoomInfo — 1 operation(s) for insights.
- [ZoomInfo Interact [Experimental] API](https://apis.io/apis/zoominfo/zoominfo-interact-experimental-api/) — The Interact [Experimental] API from ZoomInfo — 3 operation(s) for interact [experimental].
- [ZoomInfo Products and Services API](https://apis.io/apis/zoominfo/zoominfo-products-and-services-api/) — The Products and Services API from ZoomInfo — 4 operation(s) for products and services.
- [ZoomInfo Pulses API](https://apis.io/apis/zoominfo/zoominfo-pulses-api/) — The Pulses API from ZoomInfo — 1 operation(s) for pulses.
- [ZoomInfo Recommendations API](https://apis.io/apis/zoominfo/zoominfo-recommendations-api/) — The Recommendations API from ZoomInfo — 3 operation(s) for recommendations.
- [ZoomInfo Search API](https://apis.io/apis/zoominfo/zoominfo-search-api/) — The Search API from ZoomInfo — 5 operation(s) for search.
- [ZoomInfo User API](https://apis.io/apis/zoominfo/zoominfo-user-api/) — The User API from ZoomInfo — 1 operation(s) for user.
- [ZoomInfo Workflows API](https://apis.io/apis/zoominfo/zoominfo-workflows-api/) — The Workflows API from ZoomInfo — 3 operation(s) for workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (8)

Multi-step workflows that chain operations into a business task.

- [ZoomInfo Authenticate and Search Contacts](https://apis.io/arazzos/zoominfo/zoominfo-authenticate-contact-search-workflow/)
- [ZoomInfo Resolve a Company from a URL](https://apis.io/arazzos/zoominfo/zoominfo-company-master-data-enrich-workflow/)
- [ZoomInfo Search and Enrich a Company](https://apis.io/arazzos/zoominfo/zoominfo-company-search-enrich-workflow/)
- [ZoomInfo Search a Company and Pull Its Intent](https://apis.io/arazzos/zoominfo/zoominfo-company-search-intent-enrich-workflow/)
- [ZoomInfo Search and Enrich a Contact](https://apis.io/arazzos/zoominfo/zoominfo-contact-search-enrich-workflow/)
- [ZoomInfo Find Intent Signals and Enrich the Account](https://apis.io/arazzos/zoominfo/zoominfo-intent-search-enrich-company-workflow/)
- [ZoomInfo Find Scoops and Enrich the Company](https://apis.io/arazzos/zoominfo/zoominfo-scoop-search-enrich-company-workflow/)
- [ZoomInfo Discover Scoops then Refine by Department](https://apis.io/arazzos/zoominfo/zoominfo-scoop-search-then-enrich-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Zoominfo Webhooks](https://apis.io/asyncapis/zoominfo/zoominfo-webhooks/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/zoominfo/](https://apis.io/graphqls/zoominfo/zoominfo-graphql/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [Hosted MCP Server](https://apis.io/servers/zoominfo/hosted-mcp-server/)
- [MCP Server](https://apis.io/servers/zoominfo/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Zoominfo Agentic Access](https://apis.io/agentic-access/zoominfo/zoominfo-agentic-access/)

#### JSON Schema (339)

The data models the API reads and writes.

- [AccountSummaryQuestionRequest](https://apis.io/schemas/zoominfo/zoominfo-account-summary-question-request/)
- [AccountSummaryQuestionResponse](https://apis.io/schemas/zoominfo/zoominfo-account-summary-question-response/)
- [AccountSummaryResponse](https://apis.io/schemas/zoominfo/zoominfo-account-summary-response/)
- [AddanobjectTypetoasubscription](https://apis.io/schemas/zoominfo/zoominfo-addanobject-typetoasubscription/)
- [Address](https://apis.io/schemas/zoominfo/zoominfo-address/)
- [Address1](https://apis.io/schemas/zoominfo/zoominfo-address1/)
- [Address2](https://apis.io/schemas/zoominfo/zoominfo-address2/)
- [AgentListResponse](https://apis.io/schemas/zoominfo/zoominfo-agent-list-response/)
- [AgentTeamDetailResponse](https://apis.io/schemas/zoominfo/zoominfo-agent-team-detail-response/)
- [AgentTeamRunResponse](https://apis.io/schemas/zoominfo/zoominfo-agent-team-run-response/)
- [AgentTeamRunsListResponse](https://apis.io/schemas/zoominfo/zoominfo-agent-team-runs-list-response/)
- [AgentTeamsListResponse](https://apis.io/schemas/zoominfo/zoominfo-agent-teams-list-response/)
- [AudiencesJsonApiList](https://apis.io/schemas/zoominfo/zoominfo-audiences-json-api-list/)
- [AuthenticateRequest](https://apis.io/schemas/zoominfo/zoominfo-authenticate-request/)
- [BulkCompanyEnrich](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-enrich/)
- [BulkCompanyEnrichRequest](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-enrich-request/)
- [BulkCompanyEnrichwithRequiredFields](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-enrichwith-required-fields/)
- [BulkCompanySearch-Preview](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-search-preview/)
- [BulkCompanySearch-Redeem](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-search-redeem/)
- [BulkCompanySearchRequest](https://apis.io/schemas/zoominfo/zoominfo-bulk-company-search-request/)
- [BulkContactEnrich](https://apis.io/schemas/zoominfo/zoominfo-bulk-contact-enrich/)
- [BulkContactEnrichRequest](https://apis.io/schemas/zoominfo/zoominfo-bulk-contact-enrich-request/)
- [BulkContactEnrichwithRequiredFields](https://apis.io/schemas/zoominfo/zoominfo-bulk-contact-enrichwith-required-fields/)
- [BulkContactSearch-Preview](https://apis.io/schemas/zoominfo/zoominfo-bulk-contact-search-preview/)
- [BulkContactSearch-Redeem](https://apis.io/schemas/zoominfo/zoominfo-bulk-contact-search-redeem/)
- …and 314 more published on APIs.io

#### JSON Structure (280)

Data models expressed in JSON Structure.

- [Zoominfo Addanobject Typetoasubscription Structure](https://apis.io/json-structure/zoominfo/zoominfo-addanobject-typetoasubscription-structure/)
- [Zoominfo Address Structure](https://apis.io/json-structure/zoominfo/zoominfo-address-structure/)
- [Zoominfo Address1 Structure](https://apis.io/json-structure/zoominfo/zoominfo-address1-structure/)
- [Zoominfo Address2 Structure](https://apis.io/json-structure/zoominfo/zoominfo-address2-structure/)
- [Zoominfo Authenticate Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-authenticate-request-structure/)
- [Zoominfo Bulk Company Enrich Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-enrich-request-structure/)
- [Zoominfo Bulk Company Enrich Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-enrich-structure/)
- [Zoominfo Bulk Company Enrichwith Required Fields Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-enrichwith-required-fields-structure/)
- [Zoominfo Bulk Company Search Preview Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-search-preview-structure/)
- [Zoominfo Bulk Company Search Redeem Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-search-redeem-structure/)
- [Zoominfo Bulk Company Search Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-company-search-request-structure/)
- [Zoominfo Bulk Contact Enrich Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-enrich-request-structure/)
- [Zoominfo Bulk Contact Enrich Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-enrich-structure/)
- [Zoominfo Bulk Contact Enrichwith Required Fields Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-enrichwith-required-fields-structure/)
- [Zoominfo Bulk Contact Search Preview Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-search-preview-structure/)
- [Zoominfo Bulk Contact Search Redeem Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-search-redeem-structure/)
- [Zoominfo Bulk Contact Search Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-contact-search-request-structure/)
- [Zoominfo Bulk Job Results Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-job-results-request-structure/)
- [Zoominfo Bulk Job Status Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-job-status-request-structure/)
- [Zoominfo Bulk Job Status Structure](https://apis.io/json-structure/zoominfo/zoominfo-bulk-job-status-structure/)
- [Zoominfo Changetheobject Typeforasubscription Structure](https://apis.io/json-structure/zoominfo/zoominfo-changetheobject-typeforasubscription-structure/)
- [Zoominfo Company Enrich Input Structure](https://apis.io/json-structure/zoominfo/zoominfo-company-enrich-input-structure/)
- [Zoominfo Company Enrich Output Structure](https://apis.io/json-structure/zoominfo/zoominfo-company-enrich-output-structure/)
- [Zoominfo Company Enrich Request Structure](https://apis.io/json-structure/zoominfo/zoominfo-company-enrich-request-structure/)
- [Zoominfo Company Funding Structure](https://apis.io/json-structure/zoominfo/zoominfo-company-funding-structure/)
- …and 255 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Zoominfo Context](https://apis.io/jsonld/zoominfo/zoominfo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [zoominfo API Vocabulary](https://apis.io/vocabularies/zoominfo/zoominfo-vocabulary/)

#### Examples (268)

Example requests and responses.

- [Zoominfo Addanobject Typetoasubscription Example](https://apis.io/examples/zoominfo/zoominfo-addanobject-typetoasubscription-example/)
- [Zoominfo Address Example](https://apis.io/examples/zoominfo/zoominfo-address-example/)
- [Zoominfo Address1 Example](https://apis.io/examples/zoominfo/zoominfo-address1-example/)
- [Zoominfo Address2 Example](https://apis.io/examples/zoominfo/zoominfo-address2-example/)
- [Zoominfo Authenticate Request Example](https://apis.io/examples/zoominfo/zoominfo-authenticate-request-example/)
- [Zoominfo Bulk Company Enrich Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-enrich-example/)
- [Zoominfo Bulk Company Enrich Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-enrich-request-example/)
- [Zoominfo Bulk Company Enrichwith Required Fields Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-enrichwith-required-fields-example/)
- [Zoominfo Bulk Company Search Preview Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-search-preview-example/)
- [Zoominfo Bulk Company Search Redeem Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-search-redeem-example/)
- [Zoominfo Bulk Company Search Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-company-search-request-example/)
- [Zoominfo Bulk Contact Enrich Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-enrich-example/)
- [Zoominfo Bulk Contact Enrich Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-enrich-request-example/)
- [Zoominfo Bulk Contact Enrichwith Required Fields Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-enrichwith-required-fields-example/)
- [Zoominfo Bulk Contact Search Preview Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-search-preview-example/)
- [Zoominfo Bulk Contact Search Redeem Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-search-redeem-example/)
- [Zoominfo Bulk Contact Search Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-contact-search-request-example/)
- [Zoominfo Bulk Job Results Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-job-results-request-example/)
- [Zoominfo Bulk Job Status Example](https://apis.io/examples/zoominfo/zoominfo-bulk-job-status-example/)
- [Zoominfo Bulk Job Status Request Example](https://apis.io/examples/zoominfo/zoominfo-bulk-job-status-request-example/)
- [Zoominfo Changetheobject Typeforasubscription Example](https://apis.io/examples/zoominfo/zoominfo-changetheobject-typeforasubscription-example/)
- [Zoominfo Company Enrich Input Example](https://apis.io/examples/zoominfo/zoominfo-company-enrich-input-example/)
- [Zoominfo Company Enrich Output Example](https://apis.io/examples/zoominfo/zoominfo-company-enrich-output-example/)
- [Zoominfo Company Enrich Request Example](https://apis.io/examples/zoominfo/zoominfo-company-enrich-request-example/)
- [Zoominfo Company Example](https://apis.io/examples/zoominfo/zoominfo-company-example/)
- …and 243 more published on APIs.io

#### Collections (25)

Postman and Open Collection request collections.

- [ZoomInfo](https://apis.io/collections/zoominfo/open-zoominfo/)
- [ZoomInfo Authentication API](https://apis.io/collections/zoominfo/open-zoominfo-authentication-api/)
- [ZoomInfo Authentication Bulk API](https://apis.io/collections/zoominfo/open-zoominfo-bulk-api/)
- [ZoomInfo Authentication Company Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-company-enrich-api/)
- [ZoomInfo Authentication Company Location Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-company-location-enrich-api/)
- [ZoomInfo Authentication Company Master Data Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-company-master-data-enrich-api/)
- [ZoomInfo Authentication Company Search API](https://apis.io/collections/zoominfo/open-zoominfo-company-search-api/)
- [ZoomInfo Authentication Compliance API API](https://apis.io/collections/zoominfo/open-zoominfo-compliance-api-api/)
- [ZoomInfo Authentication Contact Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-contact-enrich-api/)
- [ZoomInfo Authentication Contact Search API](https://apis.io/collections/zoominfo/open-zoominfo-contact-search-api/)
- [ZoomInfo Authentication Corporate Hierarchy Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-corporate-hierarchy-enrich-api/)
- [ZoomInfo Authentication Hashtags Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-hashtags-enrich-api/)
- [ZoomInfo Authentication Intent Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-intent-enrich-api/)
- [ZoomInfo Authentication Intent Search API](https://apis.io/collections/zoominfo/open-zoominfo-intent-search-api/)
- [ZoomInfo Authentication Lookup API](https://apis.io/collections/zoominfo/open-zoominfo-lookup-api/)
- [ZoomInfo Authentication Monitoring API/Webhooks API](https://apis.io/collections/zoominfo/open-zoominfo-monitoring-api-webhooks-api/)
- [ZoomInfo Authentication News Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-news-enrich-api/)
- [ZoomInfo Authentication News Search API](https://apis.io/collections/zoominfo/open-zoominfo-news-search-api/)
- [ZoomInfo Authentication OrgChart Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-orgchart-enrich-api/)
- [ZoomInfo Authentication Scoop Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-scoop-enrich-api/)
- [ZoomInfo Authentication Scoop Search API](https://apis.io/collections/zoominfo/open-zoominfo-scoop-search-api/)
- [ZoomInfo Authentication Technology Enrich API](https://apis.io/collections/zoominfo/open-zoominfo-technology-enrich-api/)
- [ZoomInfo Authentication Usage API](https://apis.io/collections/zoominfo/open-zoominfo-usage-api/)
- [ZoomInfo Authentication WebSights API API](https://apis.io/collections/zoominfo/open-zoominfo-websights-api-api/)
- [ZoomInfo](https://apis.io/collections/zoominfo/postman-zoominfo/)

#### Overlays (48)

OpenAPI overlays, including conversational phrasing for each operation.

- [Zoominfo Account Summary Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-account-summary-api-phrasing-overlay/)
- [Zoominfo Agent Teams Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-agent-teams-api-phrasing-overlay/)
- [Zoominfo Audiences Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-audiences-api-phrasing-overlay/)
- [Zoominfo Authentication Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-authentication-api-phrasing-overlay/)
- [Zoominfo Bulk Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-bulk-api-phrasing-overlay/)
- [Zoominfo Company Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-company-enrich-api-phrasing-overlay/)
- [Zoominfo Company Location Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-company-location-enrich-api-phrasing-overlay/)
- [Zoominfo Company Master Data Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-company-master-data-enrich-api-phrasing-overlay/)
- [Zoominfo Company Search Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-company-search-api-phrasing-overlay/)
- [Zoominfo Compliance Api Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-compliance-api-api-phrasing-overlay/)
- [Zoominfo Contact Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-contact-enrich-api-phrasing-overlay/)
- [Zoominfo Contact Search Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-contact-search-api-phrasing-overlay/)
- [Zoominfo Corporate Hierarchy Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-corporate-hierarchy-enrich-api-phrasing-overlay/)
- [Zoominfo Customer Buyer Persona Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-customer-buyer-persona-api-phrasing-overlay/)
- [Zoominfo Customer Competitors Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-customer-competitors-api-phrasing-overlay/)
- [Zoominfo Customer Settings Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-customer-settings-api-phrasing-overlay/)
- [Zoominfo Engagements Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-engagements-api-phrasing-overlay/)
- [Zoominfo Enrich Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-enrich-api-phrasing-overlay/)
- [Zoominfo Entities Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-entities-api-phrasing-overlay/)
- [Zoominfo Entitlements Api Phrasing Overlay](https://apis.io/overlays/zoominfo/zoominfo-entitlements-api-phrasing-overlay/)
- [Zoominfo Gtm Agent V1 Overlay](https://apis.io/overlays/zoominfo/zoominfo-gtm-agent-v1-overlay/)
- [Zoominfo Gtm Copilot V1 Overlay](https://apis.io/overlays/zoominfo/zoominfo-gtm-copilot-v1-overlay/)
- [Zoominfo Gtm Data V1 Overlay](https://apis.io/overlays/zoominfo/zoominfo-gtm-data-v1-overlay/)
- [Zoominfo Gtm Gtm Studio V1 Overlay](https://apis.io/overlays/zoominfo/zoominfo-gtm-gtm-studio-v1-overlay/)
- [Zoominfo Gtm Marketing V1 Overlay](https://apis.io/overlays/zoominfo/zoominfo-gtm-marketing-v1-overlay/)
- …and 23 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [ZoomInfo — jsonschema rules](https://apis.io/rules/zoominfo/zoominfo-jsonschema-spectral-rules/)
- [ZoomInfo API Rules](https://apis.io/rules/zoominfo/zoominfo-rules/)
- [ZoomInfo API Rules](https://apis.io/rules/zoominfo/zoominfo-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Zoominfo Authentication](https://apis.io/security/zoominfo/zoominfo-authentication/)
- [Zoominfo Domain Security](https://apis.io/security/zoominfo/zoominfo-domain-security/)
- [Zoominfo Trust Center](https://apis.io/security/zoominfo/zoominfo-trust-center/)
- [Zoominfo Vulnerability Disclosure](https://apis.io/security/zoominfo/zoominfo-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Zoominfo Scopes](https://apis.io/scopes/zoominfo/zoominfo-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Zoominfo Plans Pricing](https://apis.io/plans/zoominfo/zoominfo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Zoominfo Rate Limits](https://apis.io/rate-limits/zoominfo/zoominfo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Zoominfo Finops](https://apis.io/finops/zoominfo/zoominfo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.zoominfo.com/)
- [Documentation](https://docs.zoominfo.com)
- [Getting started](https://docs.zoominfo.com/docs/overview)
- [API reference](https://docs.zoominfo.com/reference/api-overview)
- [Pricing](https://www.zoominfo.com/pricing)
- [Sign up](https://developer.zoominfo.com/)
- [Support](https://www.zoominfo.com/about/help-center)
- [Blog](https://pipeline.zoominfo.com/)
- [Terms of service](https://www.zoominfo.com/legal/terms-of-use)
- [Privacy policy](https://www.zoominfo.com/legal/privacy-policy)
- [GitHub](https://github.com/Zoominfo)
- [Status](https://status.zoominfo.com)

## API Evangelist rating

**Kin Score 86.6** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 83.3 |
| Contract quality | 76.4 |
| Contract governance | 31.8 |
| Operational transparency | 92.1 |
| Developer ergonomics | 89.3 |
| Access clarity | 92.1 |

**Agent readiness 64.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/zoominfo/](https://apis.io/providers/zoominfo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for ZoomInfo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/zoominfo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
