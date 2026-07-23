---
name: Find the nearest Halifax ATM or branch
description: Use the public OBIE Open Data APIs to locate Halifax cashpoints and branches by area, with no authentication.
api: openapi/openbanking-opendata-standard-swagger.json
operations: [getAtms, getBranches]
---

# Find the nearest Halifax ATM or branch

Halifax publishes ATM and branch locations as **public, unauthenticated** OBIE
Open Data APIs. No credentials, keys, or onboarding are required.

## Steps

1. **List ATMs** — `GET https://api.halifax.co.uk/open-banking/v2.2/atms`
   (operation `getAtms`). Returns the full set of Halifax cashpoints, each with
   a geographic location (latitude/longitude), postcode, accessibility features,
   and supported services.
2. **List branches** — `GET https://api.halifax.co.uk/open-banking/v2.2/branches`
   (operation `getBranches`) for branch locations, opening hours and services.
3. **Filter client-side by proximity.** The Open Data endpoints return the full
   national dataset in a single document (no server-side geo query). Parse the
   response and compute distance from the user's location yourself.

## Conventions

- **Conditional requests:** send `If-None-Match` (ETag) or `If-Modified-Since`
  to avoid re-transferring unchanged reference data.
- **Media type:** responses use `application/prs.openbanking.opendata.v1.3+json`.
- **Rate limiting:** a `429 Too Many Requests` means back off and retry later.
- **No auth:** never attach an Authorization header — these endpoints are open.

See `conventions/halifax-conventions.yml` and `errors/halifax-problem-types.yml`.
