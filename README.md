# Tock (tock)

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

Tock is a Chicago-founded reservation, ticketed events, takeout, and delivery management platform for restaurants, wineries, and hospitality venues. Founded in 2014 by Nick Kokonas, Brian Fitzpatrick, and Grant Achatz to support prepaid and ticketed dining (originated at Alinea Group), Tock pioneered the prepaid reservation model and expanded into takeout, wine delivery, and experience ticketing through the pandemic. Squarespace acquired Tock for approximately $400 million in 2021, then sold it to American Express in June 2024 as part of Amex's strategy to deepen its dining and premium-experience footprint. Tock is operated as an Amex-owned property today and continues to serve restaurants globally through exploretock.com. Tock publishes API documentation and data-model specifications at api.exploretock.com covering its Reservation and Guest data models. Programmatic access is delivered through a Data Exports API (twice-daily reservation and guest exports), a Guest Profile Ingest API (create/update of basic guest information), and a real-time Reservation Webhook. API and webhook access is an entitlement of the Premium and Premium Unlimited plans; partners request an API key by emailing integrate@tockhq.com from a Tock Dashboard Account Owner. There is no self-serve developer signup; deeper POS, CRM, marketing, loyalty, and ticketing integrations are coordinated through Tock's partnerships team.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tock/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tock/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Hospitality
- Reservations
- Restaurants
- Wineries
- Ticketed Events
- Takeout
- Delivery
- Experiences
- Dining
- American Express

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-06-03

## APIs

### Tock Reservation API

Reservation data model and delivery surface published at api.exploretock.com. Reservation records (bookings, ticketed experiences, takeout/delivery orders, parties, pricing, payments, refunds, notes, and post-visit feedback) are delivered to approved partners through a twice-daily Data Exports API and a real-time Reservation Webhook. Tock publishes a Swagger 2.0 data-model spec for the canonical reservation object; reservation data is read-only via API (it cannot be modified programmatically). Access requires a Tock API key and a Premium or Premium Unlimited plan.

- **Human URL:** [https://api.exploretock.com/docs/latest/reservation.html](https://api.exploretock.com/docs/latest/reservation.html)

#### Tags

- REST
- Reservations
- Ticketed Events
- Takeout
- Delivery
- Webhooks
- Data Export

#### Properties

- [Documentation](https://api.exploretock.com/docs/latest/reservation.html)
- [API Reference](https://api.exploretock.com/docs/latest/reservation.html)
- [OpenAPI](openapi/tock-reservation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tock-reservation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tock-reservation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/reservation-reservation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/reservation-reservation-structure.json)
- [JSON-LD](json-ld/tock-reservation-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/reservation-reservation-example.json)
- [Authentication](https://tock.zendesk.com/hc/en-us/articles/25447494175508-API-FAQ)
- [Partners](https://www.exploretock.com/partners)

### Tock Guest API

Guest (CRM) data model and ingest surface published at api.exploretock.com. Guest profiles capture contact details, dietary restrictions and preferences, tags, per-business and group-level notes and spend, and loyalty program references. Profiles are read via the Data Exports API and created or updated via the Guest Profile Ingest API, which supports basic guest information only. Tock publishes a Swagger 2.0 data-model spec for the canonical guest profile object. Access requires a Tock API key and a Premium or Premium Unlimited plan.

- **Human URL:** [https://api.exploretock.com/docs/latest/guest_profile.html](https://api.exploretock.com/docs/latest/guest_profile.html)

#### Tags

- REST
- Guests
- CRM
- Data Export
- Ingest

#### Properties

- [Documentation](https://api.exploretock.com/docs/latest/guest_profile.html)
- [API Reference](https://api.exploretock.com/docs/latest/guest_profile.html)
- [OpenAPI](openapi/tock-guest-profile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tock-guest-profile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tock-guest-profile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/guest-profile-guest-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/guest-profile-guest-profile-structure.json)
- [JSON-LD](json-ld/tock-guest-profile-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/guest-profile-guest-profile-example.json)
- [Authentication](https://tock.zendesk.com/hc/en-us/articles/25447494175508-API-FAQ)
- [Partners](https://www.exploretock.com/partners)

## Common Properties

- [Website](https://www.exploretock.com/)
- [Documentation](https://api.exploretock.com/docs/latest/reservation.html)
- [GitHub Organization](https://github.com/tocktix)
- [Partners](https://www.exploretock.com/partners)
- [Sign Up](https://www.exploretock.com/business)
- [Login](https://www.exploretock.com/login)
- [Customers](https://www.exploretock.com/restaurants)
- [Support](https://help.exploretock.com/)
- [Blog](https://www.exploretock.com/journal)
- [Privacy Policy](https://www.exploretock.com/privacy)
- [Terms of Service](https://www.exploretock.com/terms)
- [LinkedIn](https://www.linkedin.com/company/tock)
- [X (Twitter)](https://twitter.com/exploretock)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [Plans](plans/tock-plans-pricing.yml)
- [Rate Limits](rate-limits/tock-rate-limits.yml)
- [Fin Ops](finops/tock-finops.yml)
- [Vocabulary](vocabulary/tock-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
