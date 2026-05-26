# Security Policy

## Supported Versions

Currently, only the latest release of the DuckDB Simulator is supported with security updates. 

| Version | Supported          |
| ------- | ------------------ |
| v1.0.x  | :white_check_mark: |
| < 1.0   | :x:                |

## Data Privacy & Architecture

The **DuckDB Simulator** is a **100% Client-Side** application. This architecture intrinsically limits many typical web vulnerabilities:

1. **Zero Data Egress:** All imported CSV datasets, executed queries, and schema architectures live strictly within the volatile memory (RAM) and local storage (IndexedDB/LocalStorage) of your browser.
2. **No Backend Database:** We do not route queries through external servers. There is no central database to breach.
3. **No API Keys:** The platform operates without relying on costly third-party AI APIs or backend microservices, eliminating the risk of key exposure.

## Reporting a Vulnerability

While the platform is highly secure by design, we take all potential vulnerabilities seriously (e.g., Cross-Site Scripting (XSS) in result rendering or Macro exploits).

If you discover a security vulnerability within this project, please follow these steps:

1. **Do not disclose it publicly** (e.g., do not create a public GitHub Issue).
2. Email the maintainer directly or contact via provided developer channels:
   - Developer: Adewale Samson Adeagbo
   - LinkedIn: [linkedin.com/in/adewalesamsonadeagbo](https://linkedin.com/in/adewalesamsonadeagbo)
3. Provide a clear description of the vulnerability, the steps to reproduce it, and the potential impact.

We will acknowledge receipt of your vulnerability report within 48 hours and strive to resolve it swiftly.
