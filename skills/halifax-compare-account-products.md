---
name: Compare Halifax account and lending products
description: Pull Halifax personal/business current account, SME loan and commercial credit card reference data from the public OBIE Open Data APIs to compare products.
api: openapi/openbanking-opendata-standard-swagger.json
operations: [getPersonalCurrentAccounts, getBusinessCurrentAccounts, getUnsecuredSmeLoans, getCommercialCreditCards]
---

# Compare Halifax account and lending products

Halifax publishes standardised product reference data under the OBIE Open Data
standard — **public and unauthenticated**. Use it to compare fees, rates,
eligibility and features across products.

## Steps

1. **Personal current accounts** —
   `GET https://api.halifax.co.uk/open-banking/v2.2/personal-current-accounts`
   (operation `getPersonalCurrentAccounts`).
2. **Business current accounts** —
   `GET https://api.halifax.co.uk/open-banking/v2.2/business-current-accounts`
   (operation `getBusinessCurrentAccounts`).
3. **Unsecured SME loans** —
   `GET https://api.halifax.co.uk/open-banking/v2.2/unsecured-sme-loans`
   (operation `getUnsecuredSmeLoans`).
4. **Commercial credit cards** —
   `GET https://api.halifax.co.uk/open-banking/v2.2/commercial-credit-cards`
   (operation `getCommercialCreditCards`).
5. **Normalise and compare.** Each response follows the OBIE product schema
   (overdraft rates, fees, features, eligibility). Extract the fields you care
   about and compare across products or against other CMA9 banks.

## Notes

- These are **product reference** APIs, not account data. Reading a customer's
  own accounts requires the FAPI-secured Read/Write AIS API (`accounts` scope,
  TPP onboarding) — see `authentication/halifax-authentication.yml`.
- Use conditional requests (`If-None-Match`) to cache; handle `429` with backoff.
