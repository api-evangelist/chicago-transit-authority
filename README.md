# Chicago Transit Authority (chicago-transit-authority)

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

The Chicago Transit Authority (CTA) is the public transit operator for the City of Chicago and 35 surrounding suburbs, operating the second largest public transit system in the United States with bus and rapid-transit (L) train services. The CTA Developer Center publishes open transit data feeds and APIs for developers building rider-facing applications, including the Train Tracker API for real-time L-train arrivals, the Bus Tracker API for real-time bus arrivals and vehicle locations, the Customer Alerts API for service status and disruptions, and GTFS schedule data feeds for the entire CTA bus and rail network.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Bus
- Bus Tracker
- Chicago
- CTA
- Customer Alerts
- GTFS
- L Train
- Open Data
- Public Transit
- Real-Time
- Train
- Train Tracker
- Transit
- Transportation

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-19

## APIs

### CTA Train Tracker API

The Train Tracker API provides real-time train arrival predictions and run/location information for all CTA L train lines. Endpoints include arrival predictions by station or stop, follow-this-train run tracking, and a locations service exposing the current latitude/longitude of in-service trains. Authentication requires a developer API key issued through the CTA Developer Center.

- **Human URL:** [https://www.transitchicago.com/developers/traintracker/](https://www.transitchicago.com/developers/traintracker/)
- **Base URL:** `http://lapi.transitchicago.com/api/1.0`

#### Tags

- L Train
- Real-Time
- Train Tracker
- Transit

#### Properties

- [Documentation](https://www.transitchicago.com/developers/traintracker/)
- [A P I Docs](https://www.transitchicago.com/developers/ttdocs/)
- [A P I Key Application](https://www.transitchicago.com/developers/traintrackerapply/)
- [Terms Of Use](https://www.transitchicago.com/developers/terms/)
- [OpenAPI](openapi/cta-train-tracker-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cta-train-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-train-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](spectral/chicago-transit-authority-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

### CTA Bus Tracker API

The Bus Tracker API series provides real-time bus arrival predictions, vehicle locations, route patterns, route lists, and stop directories for the CTA bus network. Endpoints support route, stop, and vehicle-based queries returning JSON or XML. Authentication requires a developer API key issued through the CTA Developer Center.

- **Human URL:** [https://www.transitchicago.com/developers/bustracker/](https://www.transitchicago.com/developers/bustracker/)
- **Base URL:** `http://www.ctabustracker.com/bustime/api/v2`

#### Tags

- Bus
- Bus Tracker
- Real-Time
- Transit

#### Properties

- [Documentation](https://www.transitchicago.com/developers/bustracker/)
- [Terms Of Use](https://www.transitchicago.com/developers/terms/)
- [OpenAPI](openapi/cta-bus-tracker-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cta-bus-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-bus-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CTA Customer Alerts API

The Customer Alerts API delivers real-time service status, planned outages, and disruption information for CTA bus and rail services. It provides both a route-level status feed and per-route or per-station detail. Authentication is not required for the public Customer Alerts feeds.

- **Human URL:** [https://www.transitchicago.com/developers/alerts/](https://www.transitchicago.com/developers/alerts/)
- **Base URL:** `http://www.transitchicago.com/api/1.0`

#### Tags

- Customer Alerts
- Real-Time
- Service Status
- Transit

#### Properties

- [Documentation](https://www.transitchicago.com/developers/alerts/)
- [Postman Collection](collections/cta-bus-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-bus-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cta-train-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-train-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CTA GTFS Schedule Feed

CTA publishes a GTFS (General Transit Feed Specification) schedule feed covering the physical layout, stop locations, and static schedules for the entire CTA bus and L train system. The feed is a downloadable ZIP archive that conforms to the GTFS reference and is updated when CTA service changes.

- **Human URL:** [https://www.transitchicago.com/developers/gtfs/](https://www.transitchicago.com/developers/gtfs/)
- **Base URL:** `https://www.transitchicago.com/downloads/sch_data/google_transit.zip`

#### Tags

- GTFS
- Schedule
- Static
- Transit

#### Properties

- [Documentation](https://www.transitchicago.com/developers/gtfs/)
- [Feed](https://www.transitchicago.com/downloads/sch_data/google_transit.zip)
- [Data Gov](https://catalog.data.gov/dataset/cta-system-information-developer-tool-gtfs-data)
- [Transitland](https://www.transit.land/feeds/f-dp3-cta)
- [Chicago Data Portal](https://data.cityofchicago.org/Transportation/CTA-System-Information-Developer-Tool-GTFS-Data/sp6w-yusg)
- [Postman Collection](collections/cta-bus-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-bus-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cta-train-tracker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cta-train-tracker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/chicago-transit-authority)
- [Website](https://www.transitchicago.com/)
- [Portal](https://www.transitchicago.com/developers/)
- [Terms Of Use](https://www.transitchicago.com/developers/terms/)
- [Privacy Policy](https://www.transitchicago.com/privacy/)
- [A P I Key Application](https://www.transitchicago.com/developers/traintrackerapply/)
- [Chicago Data Portal](https://data.cityofchicago.org)
- [System Map](https://www.transitchicago.com/maps/)
- [Newsroom](https://www.transitchicago.com/news/)
- [Contact Us](https://www.transitchicago.com/contactus/)
- [JSON-LD](json-ld/chicago-transit-authority-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](spectral/chicago-transit-authority-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)
- [Use Cases](undefined)
- [Standards](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
