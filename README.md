# Tock (tock)

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
