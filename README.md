# CarMax (carmax)

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

CarMax (NYSE: KMX) is the largest retailer of used cars in the United States, operating an omnichannel business that spans brick-and-mortar stores, carmax.com online purchasing, home delivery, financing, appraisals, and trade-ins. CarMax does not publish a public developer portal, but its engineering organization operates an extensive internal API program built around distinct API roles (Data Access Layer, Business Logic Layer, Server-Driven UI, Backend for Frontend). Public-facing APIs documented by the CarMax Engineering Blog include a Store Locations API and a Vehicle Inventory API, and CarMax has publicly discussed a Server-Driven UI API that controls vehicle search filters across web and mobile. Partner and syndication integrations are handled case by case rather than through a self-service portal.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/carmax/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consumer
- **Access:** Partner

## Tags

- Auto Financing
- Auto Retail
- Appraisals
- Automotive
- Omnichannel
- Retail
- Server-Driven UI
- Used Cars
- Vehicle Inventory
- VIN Lookup

## Overview

CarMax pioneered the no-haggle used-car retail model and has since built a tightly integrated digital and physical experience. On the technology side, the CarMax Engineering Blog openly discusses how the company runs dozens of product teams and an API Guild to keep their API ecosystem consistent, scalable, and transparent. The team organizes APIs by role: Data Access Layer APIs that wrap data sources, Business Logic Layer APIs that compose those, Server-Driven UI APIs that drive web and mobile experiences, and Backend For Frontend APIs that shape payloads per channel. Two APIs are named publicly on the blog - a Store Locations API and a Vehicle Inventory API - and CarMax also describes a Server-Driven UI API that governs the carmax.com vehicle search filters.

## APIs

### CarMax Store Locations API
The CarMax Store Locations API, discussed publicly on the CarMax Engineering Blog, exposes details about all CarMax store locations including addresses, hours, services offered, and geographic metadata. It is consumed primarily by carmax.com, the CarMax mobile app, and CarMax's digital marketing and SEO systems. The API is not offered as a self-service product to third parties.

**Human URL:** [https://www.carmax.com/stores](https://www.carmax.com/stores)

#### Features
- Address, hours, and services per store
- Geographic metadata for mapping
- Used as a source of truth across CarMax channels

#### Use Cases
- Store locator on carmax.com and mobile
- SEO and local-landing-page generation
- Internal operations dashboards

### CarMax Vehicle Inventory API
The CarMax Vehicle Inventory API exposes details about all used vehicles currently in CarMax's nationwide inventory, including year/make/model, trim, mileage, price, exterior and interior attributes, photos, and stock number. The API powers carmax.com's search experience and the Vehicle Detail Page. It is consumed internally and surfaced to customers through CarMax's own products rather than opened as a public partner feed.

**Human URL:** [https://www.carmax.com/cars](https://www.carmax.com/cars)

#### Features
- Nationwide used-vehicle inventory
- Year/make/model/trim, mileage, price, stock number
- Exterior, interior, and photo metadata
- Powers carmax.com search and VDP

#### Use Cases
- Online vehicle search and listing pages
- Home delivery and store-transfer eligibility
- Price and market analytics
- Third-party automotive marketplaces (via syndication agreements)

### CarMax Vehicle Search Server-Driven UI API
The CarMax Vehicle Search Server-Driven UI API controls the search filters and list layouts presented across carmax.com and CarMax's mobile apps. It was rewritten approximately three years prior to March 2026 and is an example of a Server-Driven UI pattern where the back end determines which filters and controls render on the client. It is an internal API, not published for external developers.

**Human URL:** [https://www.carmax.com/cars](https://www.carmax.com/cars)

#### Features
- Server-Driven UI filter and layout payloads
- Consistent web and mobile experience
- Back-end controlled A/B testing and rollout

#### Use Cases
- Unified search UX across channels
- Rapid filter experimentation
- Per-market and per-user personalization

## Common Properties

- [Website](https://www.carmax.com/)
- [Stores](https://www.carmax.com/stores)
- [Cars](https://www.carmax.com/cars)
- [Finance](https://www.carmax.com/finance)
- [Sell Your Car](https://www.carmax.com/sell-my-car)
- [Engineering Blog](https://medium.com/carmax-engineering-blog)
- [Careers](https://jobs.carmax.com/)
- [Investor Relations](https://investors.carmax.com/)
- [Customer Service](https://www.carmax.com/customer-service)
- [Terms of Service](https://www.carmax.com/terms)
- [Privacy Policy](https://www.carmax.com/privacy)
- [LinkedIn](https://www.linkedin.com/company/carmax)
- [X](https://x.com/CarMax)
- [Facebook](https://www.facebook.com/CarMax)

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
