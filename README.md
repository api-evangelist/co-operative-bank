# The Co-operative Bank (co-operative-bank)

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
