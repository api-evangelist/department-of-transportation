# Department of Transportation (department-of-transportation)

The U.S. Department of Transportation (DOT) and its operating administrations - NHTSA, FMCSA, FAA, FRA, FTA, MARAD, PHMSA, and BTS - publish a number of public APIs covering vehicles, motor carriers, aviation, transit, freight, and transportation statistics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-transportation/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-transportation/main/apis.yml)

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

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### NHTSA vPIC API

Vehicle Product Information Catalog. Decode VINs and look up makes, models, manufacturers, and World Manufacturer Identifiers.

- **Human URL:** [https://vpic.nhtsa.dot.gov/api/](https://vpic.nhtsa.dot.gov/api/)
- **Base URL:** `https://vpic.nhtsa.dot.gov/api`

#### Tags

- NHTSA
- VIN
- Vehicles

#### Properties

- [Documentation](https://vpic.nhtsa.dot.gov/api/)
- [OpenAPI](openapi/nhtsa-vpic-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nhtsa-vpic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-vpic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/vehicle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/vin-decode-example.json)

### NHTSA Vehicle Safety API

Vehicle, equipment, child-seat, and tire recalls; consumer complaints; defect investigations; 5-Star Safety Ratings.

- **Human URL:** [https://api.nhtsa.gov/](https://api.nhtsa.gov/)
- **Base URL:** `https://api.nhtsa.gov`

#### Tags

- NHTSA
- Recalls
- Safety

#### Properties

- [Documentation](https://api.nhtsa.gov/)
- [OpenAPI](openapi/nhtsa-recalls-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nhtsa-recalls-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-recalls-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/recall-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/recall-example.json)

### FMCSA QCMobile API

Federal Motor Carrier Safety Administration carrier registration, operating-authority, inspection, and crash data.

- **Human URL:** [https://mobile.fmcsa.dot.gov/qc/services/getting-started](https://mobile.fmcsa.dot.gov/qc/services/getting-started)
- **Base URL:** `https://mobile.fmcsa.dot.gov/qc/services`

#### Tags

- FMCSA
- Motor Carriers

#### Properties

- [Documentation](https://mobile.fmcsa.dot.gov/qc/services/getting-started)
- [OpenAPI](openapi/fmcsa-qcmobile-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fmcsa-qcmobile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fmcsa-qcmobile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/carrier-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://mobile.fmcsa.dot.gov/qc/services/manage)

### FAA Airport Status API

Real-time airport status, weather, and delay information for major U.S. airports.

- **Human URL:** [https://www.faa.gov/data](https://www.faa.gov/data)
- **Base URL:** `https://soa.smext.faa.gov/asws/api/airport`

#### Tags

- FAA
- Aviation
- Airports

#### Properties

- [Documentation](https://www.faa.gov/data)
- [OpenAPI](openapi/faa-system-status-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/faa-system-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/faa-system-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bureau of Transportation Statistics Data Portal

Public datasets and downloadable data products published by BTS.

- **Human URL:** [https://www.bts.gov/data-portals](https://www.bts.gov/data-portals)

#### Tags

- BTS
- Statistics

#### Properties

- [Documentation](https://www.bts.gov/data-portals)
- [Postman Collection](collections/faa-system-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/faa-system-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fmcsa-qcmobile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fmcsa-qcmobile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-recalls-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-recalls-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-vpic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-vpic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Federal Railroad Administration Safety Data

FRA Office of Safety Analysis - rail incident, accident, and inspection data.

- **Human URL:** [https://safetydata.fra.dot.gov/](https://safetydata.fra.dot.gov/)

#### Tags

- FRA
- Rail

#### Properties

- [Documentation](https://safetydata.fra.dot.gov/OfficeofSafety/Default.aspx)
- [Postman Collection](collections/faa-system-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/faa-system-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fmcsa-qcmobile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fmcsa-qcmobile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-recalls-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-recalls-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-vpic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-vpic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Federal Transit Administration National Transit Database

Public-transportation operating, financial, and asset data submitted by transit agencies under the National Transit Database.

- **Human URL:** [https://www.transit.dot.gov/ntd](https://www.transit.dot.gov/ntd)

#### Tags

- FTA
- Transit

#### Properties

- [Documentation](https://www.transit.dot.gov/ntd)
- [Postman Collection](collections/faa-system-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/faa-system-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fmcsa-qcmobile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fmcsa-qcmobile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-recalls-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-recalls-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-vpic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-vpic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PHMSA Pipeline Safety Data

Pipeline and Hazardous Materials Safety Administration incident, mileage, and operator data for U.S. pipelines.

- **Human URL:** [https://www.phmsa.dot.gov/data-and-statistics](https://www.phmsa.dot.gov/data-and-statistics)

#### Tags

- PHMSA
- Pipelines

#### Properties

- [Documentation](https://www.phmsa.dot.gov/data-and-statistics)
- [Postman Collection](collections/faa-system-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/faa-system-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fmcsa-qcmobile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fmcsa-qcmobile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-recalls-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-recalls-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/nhtsa-vpic-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nhtsa-vpic-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usdot)
- [Portal](https://www.transportation.gov/)
- [Documentation](https://www.transportation.gov/digitalstrategy/developer)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
