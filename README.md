# Konsentus

Konsentus is a UK-headquartered specialist provider of identity verification and trust services for open banking and open finance ecosystems. Its flagship Konsentus Verify SaaS API gives Financial Institutions (ASPSPs) real-time PSD2 Third-Party Provider (TPP) identity and regulatory checking against National Competent Authority registers across the EEA, validating eIDAS, OBIE, and OBHD certificates with the issuing Qualified Trust Service Provider. The Konsentus Certificate Chain Service keeps the eIDAS trust chain current, and the Konsentus Open Trust Platform plus advisory practice helps central banks and market operators stand up national open finance trust frameworks under PSD2, PSD3, and FiDA. Trusted by 250+ financial institutions globally.

- Portal: https://www.konsentus.com
- API Reference: https://developers.konsentus.com/api-reference/introduction.html
- Swagger: https://swagger.konsentus.com/
- Certificate Chain Service Docs: https://docs.psd.konsentus.com/
- GitHub: https://github.com/konsentus
- LinkedIn: https://www.linkedin.com/company/konsentus/
- X: https://twitter.com/konsentus/

## APIs

### Konsentus Verify API

Real-time SaaS API that ASPSPs call to identify and regulate-check Third-Party Providers under PSD2 Open Banking. Validates Base64-encoded eIDAS certificates with the issuing Qualified Trust Service Provider (QTSP), confirms TPP regulated status with the relevant National Competent Authority (NCA) on a pan-EEA basis, and returns the payment services the TPP is authorised to provide in the requested jurisdiction.

- Documentation: https://developers.konsentus.com/api-reference/introduction.html
- OpenAPI: [openapi/konsentus-verify-api-openapi.yml](openapi/konsentus-verify-api-openapi.yml)

### Konsentus Certificate Chain Service API

Managed service that maintains the up-to-date eIDAS certificate trust chain required to secure PSD2 Open Banking API traffic. Tracks EU trusted list updates, QTSP changes, and root/intermediate certificate rotation.

- Documentation: https://docs.psd.konsentus.com/

### Konsentus Open Trust Platform

End-to-end platform used by central banks and market operators to build, manage, and maintain national or regional open finance trust frameworks. Covers participant onboarding, directory services, certificate issuance, consent infrastructure, and regulatory reporting for PSD2, PSD3, and FiDA.

- Documentation: https://www.konsentus.com

## Features

- Real-time Third-Party Provider (TPP) identity verification via eIDAS certificates
- Real-time TPP regulatory status checking against National Competent Authority registers (pan-EEA)
- Support for eIDAS, OBIE, and OBHD certificate test scenarios
- Certificate Chain Service tracking EU trusted list, QTSP changes, and certificate rotation
- Immutable audit log of every identity and regulatory check
- OAuth 2.0 access token issuance, validation, and lifecycle management on behalf of ASPSPs
- Directory of 5,000+ regulated PISPs, AISPs, and ASPSPs
- Deployment as SaaS API, customer portal, or on-premise
- Pay-only-for-what-you-consume commercial model
- Open Trust Platform for central banks and market operators building open finance frameworks
- Advisory and training services for PSD2, PSD3, and FiDA market participants

## Tags

Open Banking, Open Finance, PSD2, PSD3, FiDA, TPP Verification, Identity, eIDAS, Trust Services, Regulatory Checking, Financial Services
