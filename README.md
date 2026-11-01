# Tock

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

Tock is a Chicago-founded reservation, ticketed events, takeout, and delivery management platform for restaurants, wineries, and hospitality venues. Founded in 2014 by Nick Kokonas, Brian Fitzpatrick, and Grant Achatz to support prepaid and ticketed dining (originated at Alinea Group), Tock pioneered the prepaid reservation model and expanded into takeout, wine delivery, and experience ticketing through the pandemic. Squarespace acquired Tock for approximately $400 million in 2021, then sold it to American Express in June 2024 as part of Amex's strategy to deepen its dining and premium-experience footprint. Tock is operated as an Amex-owned property today and continues to serve restaurants globally through exploretock.com. Tock publishes API documentation and data-model specifications at api.exploretock.com covering its Reservation and Guest data models. Programmatic access is delivered through a Data Exports API (twice-daily reservation and guest exports), a Guest Profile Ingest API (create/update of basic guest information), and a real-time Reservation Webhook. API and webhook access is an entitlement of the Premium and Premium Unlimited plans; partners request an API key by emailing integrate@tockhq.com from a Tock Dashboard Account Owner. There is no self-serve developer signup; deeper POS, CRM, marketing, loyalty, and ticketing integrations are coordinated through Tock's partnerships team.

**Areas:** Hospitality · Reservations · Restaurant · Wineries · Ticketed Events · Takeout · Delivery · Experience · Dining · American Express

## Tock on APIs.io

Everything profiled for Tock is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tock/](https://apis.io/providers/tock/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Tock Reservation API](https://apis.io/apis/tock/reservation-api/) — Reservation data model and delivery surface published at api.exploretock.com. Reservation records (bookings, ticketed experiences, takeout/delivery orders,…
- [Tock Guest API](https://apis.io/apis/tock/guest-api/) — Guest (CRM) data model and ingest surface published at api.exploretock.com. Guest profiles capture contact details, dietary restrictions and preferences,…
- [Tock Data Exports API](https://apis.io/apis/tock/tock-data-exports-api/) — Twice-daily export of all historical reservation and guest data for the locations in a Tock business group. Payloads follow the published Reservation data…
- [Tock Guest Profile Ingest API](https://apis.io/apis/tock/tock-guest-profile-ingest-api/) — Add and update basic guest information and guest-profile tags in Tock, following the published Guest data model (patron identity, contact details, dietary…
- [Tock Real-time Reservation Webhook](https://apis.io/apis/tock/tock-reservation-webhook/) — Real-time webhook that delivers reservation updates for all locations within a Tock business group to a partner-supplied endpoint URL. The partner provides…
- [Tock Real-time Guest Profile Webhook](https://apis.io/apis/tock/tock-guest-profile-webhook/) — Real-time webhook that delivers guest-profile updates for all locations within a Tock business group to a partner-supplied endpoint URL. Tock POSTs…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (51)

The data models the API reads and writes.

- [tockAddress](https://apis.io/schemas/tock/guest-profile-address/)
- [tockAuditedNote](https://apis.io/schemas/tock/guest-profile-audited-note/)
- [tockBusiness](https://apis.io/schemas/tock/guest-profile-business/)
- [tockBusinessGroupGuestProfile](https://apis.io/schemas/tock/guest-profile-business-group-guest-profile/)
- [tockBusinessGroupSpend](https://apis.io/schemas/tock/guest-profile-business-group-spend/)
- [tockBusinessGuestProfile](https://apis.io/schemas/tock/guest-profile-business-guest-profile/)
- [tockBusinessSpend](https://apis.io/schemas/tock/guest-profile-business-spend/)
- [tockDay](https://apis.io/schemas/tock/guest-profile-day/)
- [tockDayType](https://apis.io/schemas/tock/guest-profile-day-type/)
- [tockExternalIntegrationAttribute](https://apis.io/schemas/tock/guest-profile-external-integration-attribute/)
- [tockGetGuestResponse](https://apis.io/schemas/tock/guest-profile-get-guest-response/)
- [tockGuestProfile](https://apis.io/schemas/tock/guest-profile-guest-profile/)
- [tockImportedGuestProfile](https://apis.io/schemas/tock/guest-profile-imported-guest-profile/)
- [tockLink](https://apis.io/schemas/tock/guest-profile-link/)
- [tockLinkType](https://apis.io/schemas/tock/guest-profile-link-type/)
- [tockNoteType](https://apis.io/schemas/tock/guest-profile-note-type/)
- [tockOptInSource](https://apis.io/schemas/tock/guest-profile-opt-in-source/)
- [tockPatron](https://apis.io/schemas/tock/guest-profile-patron/)
- [tockPhone](https://apis.io/schemas/tock/guest-profile-phone/)
- [tockPhoneType](https://apis.io/schemas/tock/guest-profile-phone-type/)
- [tockBusiness](https://apis.io/schemas/tock/reservation-business/)
- [tockDiscount](https://apis.io/schemas/tock/reservation-discount/)
- [tockDiscountDiscountType](https://apis.io/schemas/tock/reservation-discount-discount-type/)
- [tockExperienceVariety](https://apis.io/schemas/tock/reservation-experience-variety/)
- [tockGetReservationResponse](https://apis.io/schemas/tock/reservation-get-reservation-response/)
- …and 26 more published on APIs.io

#### JSON Structure (51)

Data models expressed in JSON Structure.

- [Guest Profile Address Structure](https://apis.io/json-structure/tock/guest-profile-address-structure/)
- [Guest Profile Audited Note Structure](https://apis.io/json-structure/tock/guest-profile-audited-note-structure/)
- [Guest Profile Business Group Guest Profile Structure](https://apis.io/json-structure/tock/guest-profile-business-group-guest-profile-structure/)
- [Guest Profile Business Group Spend Structure](https://apis.io/json-structure/tock/guest-profile-business-group-spend-structure/)
- [Guest Profile Business Guest Profile Structure](https://apis.io/json-structure/tock/guest-profile-business-guest-profile-structure/)
- [Guest Profile Business Spend Structure](https://apis.io/json-structure/tock/guest-profile-business-spend-structure/)
- [Guest Profile Business Structure](https://apis.io/json-structure/tock/guest-profile-business-structure/)
- [Guest Profile Day Structure](https://apis.io/json-structure/tock/guest-profile-day-structure/)
- [Guest Profile Day Type Structure](https://apis.io/json-structure/tock/guest-profile-day-type-structure/)
- [Guest Profile External Integration Attribute Structure](https://apis.io/json-structure/tock/guest-profile-external-integration-attribute-structure/)
- [Guest Profile Get Guest Response Structure](https://apis.io/json-structure/tock/guest-profile-get-guest-response-structure/)
- [Guest Profile Guest Profile Structure](https://apis.io/json-structure/tock/guest-profile-guest-profile-structure/)
- [Guest Profile Imported Guest Profile Structure](https://apis.io/json-structure/tock/guest-profile-imported-guest-profile-structure/)
- [Guest Profile Link Structure](https://apis.io/json-structure/tock/guest-profile-link-structure/)
- [Guest Profile Link Type Structure](https://apis.io/json-structure/tock/guest-profile-link-type-structure/)
- [Guest Profile Note Type Structure](https://apis.io/json-structure/tock/guest-profile-note-type-structure/)
- [Guest Profile Opt In Source Structure](https://apis.io/json-structure/tock/guest-profile-opt-in-source-structure/)
- [Guest Profile Patron Structure](https://apis.io/json-structure/tock/guest-profile-patron-structure/)
- [Guest Profile Phone Structure](https://apis.io/json-structure/tock/guest-profile-phone-structure/)
- [Guest Profile Phone Type Structure](https://apis.io/json-structure/tock/guest-profile-phone-type-structure/)
- [Reservation Business Structure](https://apis.io/json-structure/tock/reservation-business-structure/)
- [Reservation Discount Discount Type Structure](https://apis.io/json-structure/tock/reservation-discount-discount-type-structure/)
- [Reservation Discount Structure](https://apis.io/json-structure/tock/reservation-discount-structure/)
- [Reservation Experience Variety Structure](https://apis.io/json-structure/tock/reservation-experience-variety-structure/)
- [Reservation Get Reservation Response Structure](https://apis.io/json-structure/tock/reservation-get-reservation-response-structure/)
- …and 26 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Tock Guest Profile Context](https://apis.io/jsonld/tock/tock-guest-profile-context/)
- [Tock Reservation Context](https://apis.io/jsonld/tock/tock-reservation-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Tock Vocabulary](https://apis.io/vocabularies/tock/tock-vocabulary/)

#### Examples (36)

Example requests and responses.

- [Guest Profile Address Example](https://apis.io/examples/tock/guest-profile-address-example/)
- [Guest Profile Audited Note Example](https://apis.io/examples/tock/guest-profile-audited-note-example/)
- [Guest Profile Business Example](https://apis.io/examples/tock/guest-profile-business-example/)
- [Guest Profile Business Group Guest Profile Example](https://apis.io/examples/tock/guest-profile-business-group-guest-profile-example/)
- [Guest Profile Business Group Spend Example](https://apis.io/examples/tock/guest-profile-business-group-spend-example/)
- [Guest Profile Business Guest Profile Example](https://apis.io/examples/tock/guest-profile-business-guest-profile-example/)
- [Guest Profile Business Spend Example](https://apis.io/examples/tock/guest-profile-business-spend-example/)
- [Guest Profile Day Example](https://apis.io/examples/tock/guest-profile-day-example/)
- [Guest Profile External Integration Attribute Example](https://apis.io/examples/tock/guest-profile-external-integration-attribute-example/)
- [Guest Profile Get Guest Response Example](https://apis.io/examples/tock/guest-profile-get-guest-response-example/)
- [Guest Profile Guest Profile Example](https://apis.io/examples/tock/guest-profile-guest-profile-example/)
- [Guest Profile Imported Guest Profile Example](https://apis.io/examples/tock/guest-profile-imported-guest-profile-example/)
- [Guest Profile Link Example](https://apis.io/examples/tock/guest-profile-link-example/)
- [Guest Profile Patron Example](https://apis.io/examples/tock/guest-profile-patron-example/)
- [Guest Profile Phone Example](https://apis.io/examples/tock/guest-profile-phone-example/)
- [Reservation Business Example](https://apis.io/examples/tock/reservation-business-example/)
- [Reservation Discount Example](https://apis.io/examples/tock/reservation-discount-example/)
- [Reservation Get Reservation Response Example](https://apis.io/examples/tock/reservation-get-reservation-response-example/)
- [Reservation Gift Card Example](https://apis.io/examples/tock/reservation-gift-card-example/)
- [Reservation Key Value Example](https://apis.io/examples/tock/reservation-key-value-example/)
- [Reservation Loyalty Program Example](https://apis.io/examples/tock/reservation-loyalty-program-example/)
- [Reservation Note Example](https://apis.io/examples/tock/reservation-note-example/)
- [Reservation Patron Example](https://apis.io/examples/tock/reservation-patron-example/)
- [Reservation Payout Example](https://apis.io/examples/tock/reservation-payout-example/)
- [Reservation Purchased Custom Charge Example](https://apis.io/examples/tock/reservation-purchased-custom-charge-example/)
- …and 11 more published on APIs.io

#### Collections (2)

Postman and Open Collection request collections.

- [Tock Guest Model](https://apis.io/collections/tock/open-tock-guest-profile/)
- [Tock Reservation Model](https://apis.io/collections/tock/open-tock-reservation/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Tock — jsonschema rules](https://apis.io/rules/tock/tock-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Tock Authentication](https://apis.io/security/tock/tock-authentication/)
- [Tock Domain Security](https://apis.io/security/tock/tock-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tock Plans Pricing](https://apis.io/plans/tock/tock-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tock Rate Limits](https://apis.io/rate-limits/tock/tock-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Tock Finops](https://apis.io/finops/tock/tock-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.exploretock.com/)
- [Documentation](https://api.exploretock.com/docs/latest/reservation.html)
- [Support](https://help.exploretock.com/)
- [Blog](https://www.exploretock.com/journal)
- [Terms of service](https://www.exploretock.com/terms)
- [Privacy policy](https://www.exploretock.com/privacy)
- [GitHub](https://github.com/tocktix)

## API Evangelist rating

**Kin Score 35.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 43.9 |
| Contract governance | 23.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 32.9 |

**Agent readiness 17.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tock/](https://apis.io/providers/tock/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Tock: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tock/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
