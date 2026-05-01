# Department of Transportation

The U.S. Department of Transportation (DOT) and its operating administrations - NHTSA, FMCSA, FAA, FRA, FTA, MARAD, PHMSA, and BTS - publish a number of public APIs covering vehicles, motor carriers, aviation, transit, freight, and transportation statistics. This repository inventories the catalog as an APIs.yml index plus generated artifacts for the APIs that have a real, public surface area.

**APIs.yml:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-transportation/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Transportation
- Vehicles
- Aviation
- Motor Carriers

## Repository Layout

- [`apis.yml`](apis.yml) — APIs.json/yml index
- [`openapi/`](openapi/) — OpenAPI 3.1 specifications
- [`json-schema/`](json-schema/) — JSON Schemas for vehicles, recalls, and carriers
- [`json-ld/`](json-ld/) — JSON-LD context aligning DOT terms to schema.org
- [`vocabulary/`](vocabulary/) — Controlled vocabulary across NHTSA, FMCSA, FAA, FTA, BTS
- [`capabilities/`](capabilities/) — Capability catalog
- [`rules/`](rules/) — Access, rate-limit, and attribution rules
- [`examples/`](examples/) — Representative response payloads

## APIs in this Index

### NHTSA
- **vPIC API** — VIN decoding, makes, models, manufacturers
- **Vehicle Safety API** — recalls, complaints, investigations, 5-Star Safety Ratings

### FMCSA
- **QCMobile API** — motor carrier registration, authority, inspections, crashes

### FAA
- **Airport Status API** — real-time airport status, delays, weather

### Other Administrations
- **BTS Data Portal** — Bureau of Transportation Statistics datasets
- **FRA Safety Data** — rail safety analytics
- **FTA National Transit Database** — public-transit data
- **PHMSA Pipeline Safety Data** — pipeline incidents and operators

## Authentication

- **NHTSA vPIC, NHTSA Vehicle Safety, FAA Airport Status** — public, no key required
- **FMCSA QCMobile** — webKey query parameter
- **BTS, FTA, FRA, PHMSA** — primarily downloadable datasets

## Data License

DOT data is U.S. government work in the public domain. Attribute the originating administration when republishing.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
