# Halifax (halifax)

Halifax is a major British high-street banking brand serving personal and business customers with current accounts, savings, mortgages, credit cards, loans, and insurance. It operates as a trading division of Bank of Scotland plc, a wholly owned subsidiary of Lloyds Banking Group, and is authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the PRA. As one of the UK Open Banking CMA9 mandated ASPSPs, Halifax publishes the full Open Banking Implementation Entity (OBIE) API surface — public Open Data APIs plus the FAPI-secured Read/Write APIs for Account and Transaction Information, Payment Initiation, and Confirmation of Funds.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/halifax/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/halifax/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- CMA9
- United Kingdom
- Payments
- Account Information
- Open Data

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Halifax Open Data ATM Locator API

Public, unauthenticated OBIE Open Data API returning the location and details of every Halifax cashpoint (ATM) in the UK. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/atms`

#### Tags

- Open Data
- ATM
- Locator

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard (not a bank-proprietary contract)
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/atm-locator/atm-locator.html)

### Halifax Open Data Branch Locator API

Public, unauthenticated OBIE Open Data API returning a directory of all Halifax branches in the UK. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/branches`

#### Tags

- Open Data
- Branch
- Locator

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/branchlocator/branch-locator.html)

### Halifax Open Data Personal Current Accounts API

Public, unauthenticated OBIE Open Data API publishing personal current account product reference data. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/personal-current-accounts`

#### Tags

- Open Data
- Personal Current Accounts
- Products

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/pca/pca.html)

### Halifax Open Data Business Current Accounts API

Public, unauthenticated OBIE Open Data API publishing business current account product reference data. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/business-current-accounts`

#### Tags

- Open Data
- Business Current Accounts
- Products

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/bca/bca.html)

### Halifax Open Data Unsecured SME Loans API

Public, unauthenticated OBIE Open Data API publishing unsecured SME loan product reference data. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/unsecured-sme-loans`

#### Tags

- Open Data
- SME Loans
- Products

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/unsecuredsmeloans/unsecured-sme-loans.html)

### Halifax Open Data Commercial Credit Cards API

Public, unauthenticated OBIE Open Data API publishing commercial credit card product reference data. Confirmed live (HTTP 200, JSON).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v2.2/commercial-credit-cards`

#### Tags

- Open Data
- Commercial Credit Cards
- Products

#### Properties

- [OpenAPI](openapi/openbanking-opendata-standard-swagger.json) — shared OBIE Open Data standard
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/ccc/ccc.html)

### Halifax Account and Transaction Information API (AIS)

OBIE Read/Write Account and Transaction Information (AIS) API for authorised AISPs. FAPI-secured (OAuth2/OIDC, PSD2 SCA, mTLS, OBIE/eIDAS certificates); onboarded via the Lloyds Banking Group Developer Portal. Base path follows the OBIE Read/Write v3.1 standard on the confirmed `api.halifax.co.uk` host and is not independently verified (authentication-gated).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/read-write](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v3.1/aisp`

#### Tags

- Open Banking
- Account Information
- AIS
- Read/Write

#### Properties

- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/v3.1.11/profiles/account-and-transaction-api-profile.html)

### Halifax Payment Initiation API (PIS)

OBIE Read/Write Payment Initiation (PIS) API for authorised PISPs. FAPI-secured (OAuth2/OIDC, PSD2 SCA, mTLS, OBIE/eIDAS certificates); onboarded via the Lloyds Banking Group Developer Portal. Base path follows the OBIE Read/Write v3.1 standard on the confirmed `api.halifax.co.uk` host and is not independently verified (authentication-gated).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/read-write](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v3.1/pisp`

#### Tags

- Open Banking
- Payment Initiation
- PIS
- Read/Write

#### Properties

- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/v3.1.11/profiles/payment-initiation-api-profile.html)

### Halifax Confirmation of Funds API (CBPII)

OBIE Read/Write Confirmation of Funds (CBPII) API for authorised CBPIIs. FAPI-secured (OAuth2/OIDC, PSD2 SCA, mTLS, OBIE/eIDAS certificates); onboarded via the Lloyds Banking Group Developer Portal. Base path follows the OBIE Read/Write v3.1 standard on the confirmed `api.halifax.co.uk` host and is not independently verified (authentication-gated).

- **Human URL:** [https://developer.lloydsbanking.com/prod01/lbg/read-write](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- **Base URL:** `https://api.halifax.co.uk/open-banking/v3.1/cbpii`

#### Tags

- Open Banking
- Confirmation of Funds
- CBPII
- Read/Write

#### Properties

- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/read-write)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/v3.1.11/profiles/confirmation-of-funds-api-profile.html)

## Common Properties

- [Website](https://www.halifax.co.uk/)
- [Developer Portal](https://developer.lloydsbanking.com/)
- [Documentation](https://developer.lloydsbanking.com/prod01/lbg/opendata_halifax)
- [Support](https://developer.lloydsbanking.com/prod01/lbg/lbg-support)
- [LinkedIn](https://www.linkedin.com/company/halifax)
- [Terms of Service](https://www.halifax.co.uk/aboutonline/legal-information.html)
- [Privacy Policy](https://www.halifax.co.uk/aboutonline/security-and-privacy.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
