# The Co-operative Bank (co-operative-bank)

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

The Co-operative Bank plc is a UK high-street retail and commercial bank, headquartered in Manchester and long known for its customer-led ethical banking policy. In January 2025 it completed its acquisition by Coventry Building Society, becoming part of the member-owned Coventry Building Society Group; it also operates the online-only "smile" brand. It is authorised by the PRA and regulated by the FCA and PRA, and is an FCA-authorised ASPSP under PSD2 and the UK Open Banking regime. It is not one of the nine CMA-mandated banks (CMA9), but implements the Open Banking Implementation Entity (OBIE) Read/Write API Standard (v3.1).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/co-operative-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/co-operative-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- Confirmation of Funds
- Fintech

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### The Co-operative Bank Account Information API (AIS)

OBIE Read/Write Account & Transaction Information (AISP) API for The Co-operative Bank and smile brands — account-access consents, accounts, balances, transactions, direct debits, standing orders and scheduled payments. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA); requires TPP onboarding.

- **Human URL:** [https://www.developer.co-operativebank.co.uk/apis/aisp/](https://www.developer.co-operativebank.co.uk/apis/aisp/)
- **Base URL:** `https://openbanking-retail.apis.co-operativebank.co.uk/apis/retail/open-banking/v3.1/aisp`

#### Tags

- Account Information
- AISP
- Open Banking

#### Properties

- [Documentation](https://www.developer.co-operativebank.co.uk/apis/aisp/)
- [API Reference](https://www.developer.co-operativebank.co.uk/apis/aisp/endpoints-and-errors/)

### The Co-operative Bank Payment Initiation API (PIS)

OBIE Read/Write Payment Initiation (PISP) API for The Co-operative Bank and smile brands — domestic payments, domestic scheduled payments and domestic standing orders, with their associated consents. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA); requires TPP onboarding.

- **Human URL:** [https://www.developer.co-operativebank.co.uk/apis/pisp/](https://www.developer.co-operativebank.co.uk/apis/pisp/)
- **Base URL:** `https://openbanking-retail.apis.co-operativebank.co.uk/apis/retail/open-banking/v3.1/pisp`

#### Tags

- Payment Initiation
- PISP
- Payments
- Open Banking

#### Properties

- [Documentation](https://www.developer.co-operativebank.co.uk/apis/pisp/)
- [API Reference](https://www.developer.co-operativebank.co.uk/apis/pisp/endpoints-and-errors/)

### The Co-operative Bank Confirmation of Funds API (CBPII)

OBIE Read/Write Confirmation of Funds (CBPII / Card-Based Payment Instrument) API — funds-confirmation consent and funds-confirmation checks for The Co-operative Bank and smile brands. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA); requires TPP onboarding.

- **Human URL:** [https://www.developer.co-operativebank.co.uk/apis/cbpii/](https://www.developer.co-operativebank.co.uk/apis/cbpii/)
- **Base URL:** `https://openbanking-retail.apis.co-operativebank.co.uk/apis/retail/open-banking/v3.1/cbpii`

#### Tags

- Confirmation of Funds
- CBPII
- Open Banking

#### Properties

- [Documentation](https://www.developer.co-operativebank.co.uk/apis/cbpii/)
- [API Reference](https://www.developer.co-operativebank.co.uk/apis/cbpii/endpoints-and-errors/)

### The Co-operative Bank Open Data API (OBIE standard)

Public, unauthenticated OBIE Open Data reference data (ATMs, Branches, Personal & Business Current Accounts, Unsecured SME Loans, Commercial Credit Cards). A live Co-operative Bank Open Data host was not confirmed during this bootstrap, so no bank-specific base URL is asserted; the attached OpenAPI is the shared OBIE Open Data API Standard, not a Co-operative Bank contract.

- **Human URL:** [https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

#### Tags

- Open Data
- ATM Locator
- Branch Locator
- Products

#### Properties

- [OpenAPI](openapi/obie-open-data-api-standard-swagger.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

## Common Properties

- [Website](https://www.co-operativebank.co.uk/)
- [Developer Portal](https://www.developer.co-operativebank.co.uk/)
- [Documentation](https://www.developer.co-operativebank.co.uk/apis/)
- [Getting Started](https://www.developer.co-operativebank.co.uk/get-started/)
- [Sandbox](https://www.developer.co-operativebank.co.uk/help-and-support/sandbox-environment/)
- [Status Page](https://www.developer.co-operativebank.co.uk/help-and-support/service-status/)
- [Support](https://www.developer.co-operativebank.co.uk/help-and-support/frequently-asked-questions/)
- [Privacy Policy](https://www.developer.co-operativebank.co.uk/help-and-support/privacy-cookie-policies/)
- [LinkedIn](https://www.linkedin.com/company/the-co-operative-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
