# CarMax (carmax)
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
