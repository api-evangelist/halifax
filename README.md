# Halifax (halifax)

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
