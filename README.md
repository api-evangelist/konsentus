# Konsentus (konsentus)

Konsentus is a UK-headquartered specialist provider of identity verification and trust services
for open banking and open finance ecosystems. Its flagship Konsentus Verify SaaS API gives
Financial Institutions (ASPSPs) real-time PSD2 Third-Party Provider (TPP) identity and
regulatory checking against National Competent Authority registers across the EEA, validating
eIDAS, OBIE, and OBHD certificates with the issuing Qualified Trust Service Provider. The
Konsentus Certificate Chain Service keeps the eIDAS trust chain current, and the Konsentus
Open Trust Platform plus advisory practice helps central banks and market operators stand up
national open finance trust frameworks under PSD2, PSD3, and FiDA. Trusted by 250+ financial
institutions globally.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/konsentus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/konsentus/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Open Banking
- Open Finance
- PSD2
- PSD3
- FiDA
- TPP Verification
- Identity
- eIDAS
- Trust Services
- Regulatory Checking
- Financial Services

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Konsentus Verify API

Real-time SaaS API that Financial Institutions (ASPSPs) call to identify and regulate-check
Third-Party Providers (TPPs) under PSD2 Open Banking. The PSP Checking Service validates a
Base64-encoded eIDAS certificate with the issuing Qualified Trust Service Provider (QTSP),
confirms the TPP's regulated status with the relevant National Competent Authority (NCA)
on a pan-EEA basis, and returns the payment services the TPP is authorised to provide in
the requested jurisdiction. Supports eIDAS, OBIE, and OBHD certificate test scenarios.

- **Human URL:** [https://developers.konsentus.com/api-reference/introduction.html](https://developers.konsentus.com/api-reference/introduction.html)
- **Base URL:** `https://api.konsentus.com`

#### Tags

- Open Banking
- PSD2
- TPP Verification
- Identity
- eIDAS
- Regulatory Checking

#### Properties

- [Documentation](https://developers.konsentus.com/api-reference/introduction.html)
- [Swagger](https://swagger.konsentus.com/)
- [Authentication](https://developers.konsentus.com/api-reference/fi-authentication.html)
- [Versioning](https://developers.konsentus.com/api-reference/endpoint-versioning.html)
- [Documentation](https://developers.konsentus.com/api-reference/transaction-jurisdictions.html)
- [Errors](https://developers.konsentus.com/api-reference/error-codes.html)
- [OpenAPI](openapi/konsentus-verify-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/konsentus-verify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/konsentus-verify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Konsentus Certificate Chain Service API

Managed service that maintains the up-to-date eIDAS certificate trust chain required to
secure PSD2 Open Banking API traffic. Removes the burden of tracking EU trusted list
updates, QTSP changes, and root/intermediate certificate rotation for ASPSPs.

- **Human URL:** [https://docs.psd.konsentus.com/](https://docs.psd.konsentus.com/)

#### Tags

- Open Banking
- PSD2
- Certificates
- eIDAS
- Trust Chain

#### Properties

- [Documentation](https://docs.psd.konsentus.com/)
- [Postman Collection](collections/konsentus-verify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/konsentus-verify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Konsentus Open Trust Platform

End-to-end platform used by central banks and market operators to build, manage, and
maintain national or regional open finance trust frameworks. Covers participant onboarding,
directory services, certificate issuance and management, consent infrastructure, and
regulatory reporting for emerging open finance regimes including FiDA.

- **Human URL:** [https://www.konsentus.com](https://www.konsentus.com)

#### Tags

- Open Banking
- Open Finance
- Trust Framework
- Directory
- Ecosystem

#### Properties

- [Documentation](https://www.konsentus.com)
- [Postman Collection](collections/konsentus-verify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/konsentus-verify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.konsentus.com)
- [Documentation](https://developers.konsentus.com/api-reference/introduction.html)
- [Documentation](https://docs.psd.konsentus.com/)
- [Swagger](https://swagger.konsentus.com/)
- [Getting Started](https://developers.konsentus.com/api-reference/getting-started.html)
- [Authentication](https://developers.konsentus.com/api-reference/fi-authentication.html)
- [Versioning](https://developers.konsentus.com/api-reference/endpoint-versioning.html)
- [Errors](https://developers.konsentus.com/api-reference/error-codes.html)
- [Glossary](https://developers.konsentus.com/api-reference/glossary.html)
- [Release Notes](https://developers.konsentus.com/api-reference/release-notes.html)
- [Support](https://developers.konsentus.com/api-reference/support.html)
- [F A Q](https://developers.konsentus.com/api-reference/faqs.html)
- [Sandbox](https://www.konsentus.com/first-psd2-open-banking-tpp-sandbox/)
- [Privacy Policy](https://www.konsentus.com/privacy-policy)
- [Terms of Service](https://www.konsentus.com/terms-conditions)
- [Acceptable Use Policy](https://www.konsentus.com/acceptable-use-policy)
- [Cookie Policy](https://www.konsentus.com/cookie-policy)
- [Contact](https://www.konsentus.com/contact)
- [Blog](https://www.konsentus.com/content-hub)
- [Press Releases](https://www.konsentus.com/press-releases)
- [Events](https://www.konsentus.com/events)
- [LinkedIn](https://www.linkedin.com/company/konsentus/)
- [X (Twitter)](https://twitter.com/konsentus/)
- [GitHub Organization](https://github.com/konsentus)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
