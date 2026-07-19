# Third-Party Vendor Risk Assessment: SaaS Loan Platform

A comprehensive third-party risk assessment of a critical cloud vendor (**CloudLedger Technologies Ltd**) and their loan-origination platform (**OriginateCloud**) evaluated on behalf of a regulated financial institution (**Meridian Trust Bank plc**). 

This project demonstrates the full GRC lifecycle loop: scoping/tiering by inherent risk, auditing vendor questionnaires against multi-framework assurance evidence (SOC 2 Type II, ISO 27001, Penetration Tests), scoring dynamic findings via a 5x5 Likelihood x Impact matrix, and compiling a binding remediation roadmap mapped to regulatory guidelines (including EU DORA alignment).

## Core Architectural Discrepancy Found
While the vendor answered "Yes" or claimed robust controls across their security questionnaire, cross-referencing their underlying technical audit documents revealed critical vulnerabilities—most notably an administrative console exposed to the public internet completely devoid of Multi-Factor Authentication (MFA), and an offshore customer support desk with production records access that was completely hidden/excluded from their SOC 2 and ISO examination boundaries.

## Project Structure
```text
third-party-vendor-risk-assessment/
├── evidence/
│   └── scoring/                     # Risk matrices and tiering charts
├── findings-register.xlsx           # Completed assessment workbook
├── README.md                        # Portfolio framework and walkthrough
└── vendor-risk-assessment-report.md # Executive GRC delivery report
