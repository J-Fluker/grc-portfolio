# Third-Party Tool Security Assessment

| Field | Details |
|---|---|
| **Client** | Lemonav Labs |
| **Date** | January 23–25, 2026 |
| **Type** | Vendor / Third-Party Risk Management |
| **Framework** | Internal GRC Policies (TP-01, TP-02, TP-03, GR-01, GR-02, AC-01–03) |

---

## Overview

Evaluated three vendor tool requests against Lemonav's internal security requirements. Assessment covered SOC 2 documentation review, data sensitivity classification, access provisioning controls, and compliance with internal third-party risk policies.

**Tools Assessed:** PromoSpark · CloudBox AI · PeopleFlow

---

## Key Metrics

| Metric | Result |
|---|---|
| Tools Assessed | 3 |
| Approved (Conditional) | 2 — PromoSpark, PeopleFlow |
| Rejected | 1 — CloudBox AI |
| Risk Levels Used | Low / Medium / High |

---

## Findings

### Highest Risk — CloudBox AI (Rejected)
- SOC 2 certification listed as "in progress" — no current attestation
- Unclear data retention policies for source code (intellectual property risk)
- Insufficient documentation to meet TP-01 vendor security requirements

### Key KPI Gap — PeopleFlow
- SOC 2 Type II report was **14 months old**, exceeding the 12-month currency standard
- Conditionally approved pending updated documentation and a refreshed Data Processing Agreement (DPA)

### PromoSpark
- Conditionally approved pending updated DPA and additional clarification on data handling

---

## Outcome

| Vendor | Decision | Condition |
|---|---|---|
| CloudBox AI | ❌ Rejected | SOC 2 not current; IP risk unresolved |
| PeopleFlow | ✅ Conditional Approval | Updated DPA + current SOC 2 required |
| PromoSpark | ✅ Conditional Approval | Updated DPA required |

---

## Next Steps
- Formalize TP-01 vendor review questionnaire to standardize future assessments
- Establish quarterly vendor review cadence per TP-02 policy requirements

---

## Frameworks Applied
- Internal GRC Policies: TP-01, TP-02, TP-03
- Governance policies: GR-01, GR-02
- Access control policies: AC-01 through AC-03
