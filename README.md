# Chicago Transit Authority (chicago-transit-authority)

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
