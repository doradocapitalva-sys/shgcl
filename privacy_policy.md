# Privacy Policy — Spiral Horn OS

**Effective date:** 2026-05-07
**Applies to:** the Spiral Horn OS application (the "Application"), an internal-use software tool developed by and for Spiral Horn General Contractors LLC ("Spiral Horn", "we", "us") to read and analyze our own accounting data via the QuickBooks Online API and other integrations.

This Privacy Policy explains what information the Application accesses, how that information is used, and the rights of any individual whose data is processed by the Application.

## 1. Scope

The Application is used solely by Spiral Horn personnel for Spiral Horn's internal business operations. It is not offered to the general public, does not have customer-facing features, and does not have user accounts other than those created by Spiral Horn for its authorized personnel.

## 2. Information the Application accesses

When connected to a third-party service on behalf of an authorized Spiral Horn user, the Application reads only the data needed to support internal financial reporting, project tracking, and operational analysis. Specifically:

- **QuickBooks Online (Intuit):** chart of accounts, transactions (bills, invoices, journal entries, purchases, expenses, payments), balance sheet and profit-and-loss reports, customer and vendor lists, classes, and company metadata. The Application uses the `com.intuit.quickbooks.accounting` OAuth scope. The Application does not request or use payroll, payments, or any other Intuit scope.
- **JobTread:** project (job) records, location records, document records (vendor bills, invoices, change orders, payment applications), customer and vendor accounts, and associated metadata. Access is read-only.
- **Local files:** the Application also reads CSV exports and other files stored on the authorized user's local machine where the Application is installed.

The Application does not collect biometric data, location data, contact lists, browsing history, or any data type unrelated to financial and operational reporting.

## 3. How the information is used

Information accessed by the Application is used only to:

- Build internal reports, dashboards, and reconciliations for Spiral Horn's authorized personnel.
- Verify accounting data integrity across source systems.
- Support business decision-making for Spiral Horn's operations.

Information is **not** used to train machine-learning models, to profile individuals, to make automated decisions affecting individuals, or for any advertising, marketing, or monetization purpose.

## 4. Where the information is stored

All data accessed by the Application is stored locally on the authorized user's computer (typically in a SQLite database file inside the Spiral Horn OS project folder). The Application does **not** transmit accessed data to any Spiral Horn server or to any third party other than the source services themselves (e.g., the Application calls Intuit's and JobTread's APIs to fetch data, but does not forward that data outward). No cloud component, no analytics service, and no remote logging service receives accessed data.

## 5. How long the information is kept

Data fetched by the Application is retained on the authorized user's local machine for as long as that user, or Spiral Horn, finds it operationally useful. Authorized users may delete the local data store at any time. There is no centralized retention policy because there is no centralized storage.

## 6. Information sharing

We do not sell, rent, or otherwise share information accessed by the Application with any third party. The only outbound data flows are:

- Authentication requests to source-service identity providers (e.g., Intuit's OAuth servers) to refresh access tokens.
- Read requests to source-service APIs (e.g., Intuit's QuickBooks Online API) to fetch the data the Application is authorized to access.

We do not disclose accessed information to advertising networks, data brokers, marketing partners, or analytics providers.

## 7. Security

The Application stores credentials (API keys, OAuth refresh tokens) in local configuration files marked with restrictive operating-system permissions and excluded from any version-control system Spiral Horn uses. Authorized users are responsible for the physical security of the computers on which the Application is installed.

We follow reasonable practices to protect accessed information from unauthorized access, alteration, disclosure, or destruction. No security measure is perfect, however; we do not guarantee absolute security.

## 8. Children

The Application is not directed to children under 13, and we do not knowingly collect personal information from anyone under 13.

## 9. Your rights

Because the Application processes data about Spiral Horn's own business operations on Spiral Horn's own computers, individuals whose information appears in the source data (e.g., a vendor whose name appears on a bill, a customer whose contact information is in QBO) have the same rights with respect to that information as they would with respect to any internal Spiral Horn record. Specifically, individuals may:

- Request access to information we hold about them.
- Request correction of inaccurate information.
- Request deletion of information, subject to applicable record-keeping requirements.
- Object to processing or restrict processing in certain circumstances.

To exercise any of these rights, contact us at the email address below.

## 10. Changes to this Policy

We may update this Privacy Policy from time to time. Material changes will be reflected in the "Effective date" at the top of this document. Continued use of the Application after a change indicates acceptance of the updated Policy.

## 11. Contact

For questions about this Privacy Policy, or to exercise the rights described in Section 9, contact:

Spiral Horn General Contractors LLC
Email: hthakker@spiralhorngc.com

---

*This document is a starting-point template prepared 2026-05-07. Last reviewed: 2026-05-07.*
