# Chicago Transit Authority (chicago-transit-authority)

The Chicago Transit Authority (CTA) is the public transit operator for the City of Chicago and 35 surrounding suburbs, operating the second largest public transit system in the United States with bus and rapid-transit (L) train services. The CTA Developer Center publishes open transit data feeds and APIs for developers building rider-facing applications, including the Train Tracker API, Bus Tracker API, Customer Alerts API, and GTFS schedule data feeds.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-23

## APIs

### CTA Train Tracker API

Real-time train arrival predictions and run/location data for all CTA L train lines. Requires an API key from the CTA Developer Center.

**Human URL:** [https://www.transitchicago.com/developers/traintracker/](https://www.transitchicago.com/developers/traintracker/)

**Base URL:** `http://lapi.transitchicago.com/api/1.0`

#### Properties

- [Documentation](https://www.transitchicago.com/developers/traintracker/)
- [API Reference](https://www.transitchicago.com/developers/ttdocs/)
- [API Key Application](https://www.transitchicago.com/developers/traintrackerapply/)
- [OpenAPI Spec](openapi/cta-train-tracker-openapi.yml)

### CTA Bus Tracker API

Real-time bus arrival predictions, vehicle locations, route patterns, and stop directories for the CTA bus network. Requires an API key.

**Human URL:** [https://www.transitchicago.com/developers/bustracker/](https://www.transitchicago.com/developers/bustracker/)

**Base URL:** `http://www.ctabustracker.com/bustime/api/v2`

#### Properties

- [Documentation](https://www.transitchicago.com/developers/bustracker/)
- [OpenAPI Spec](openapi/cta-bus-tracker-openapi.yml)

### CTA Customer Alerts API

Real-time service status, planned outages, and disruption information. No authentication required.

**Human URL:** [https://www.transitchicago.com/developers/alerts/](https://www.transitchicago.com/developers/alerts/)

### CTA GTFS Schedule Feed

A GTFS-compliant ZIP archive describing the physical layout, stop locations, and static schedules for the entire CTA bus and rail system.

**Human URL:** [https://www.transitchicago.com/developers/gtfs/](https://www.transitchicago.com/developers/gtfs/)

**Feed:** [google_transit.zip](https://www.transitchicago.com/downloads/sch_data/google_transit.zip)

## Common Properties

- [Website](https://www.transitchicago.com/)
- [CTA Developer Center](https://www.transitchicago.com/developers/)
- [Developer Terms of Use](https://www.transitchicago.com/developers/terms/)
- [Privacy Policy](https://www.transitchicago.com/privacy/)
- [API Key Application](https://www.transitchicago.com/developers/traintrackerapply/)
- [Chicago Data Portal](https://data.cityofchicago.org)
- [System Map](https://www.transitchicago.com/maps/)
- [Newsroom](https://www.transitchicago.com/news/)
- [Contact Us](https://www.transitchicago.com/contactus/)
- [JSON-LD Context](json-ld/chicago-transit-authority-context.jsonld)
- [Naftiko Capabilities](naftiko/chicago-transit-authority-capabilities.yml)
- [Spectral Rules](spectral/chicago-transit-authority-spectral.yml)

## Features

- Real-Time Train Arrivals
- Real-Time Bus Arrivals
- Train Run Locations
- Bus Vehicle Locations
- Route and Stop Directories
- Customer Alerts and Service Status
- Planned Outage Notifications
- GTFS Static Schedule Feed
- API Key Issuance
- Open Chicago Transit Data

## Use Cases

- Rider-Facing Mobile Apps
- Trip Planners and Routing
- Real-Time Arrival Displays
- Service Disruption Notifications
- Schedule Visualizations
- Accessibility Tooling
- Smart City Dashboards
- Multimodal Transit Apps
- Research and Open Data Analysis

## Standards

- GTFS
- GTFS-Realtime (consumed via partners)
- REST
- JSON
- XML

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
