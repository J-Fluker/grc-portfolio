# The GRC Connection Behind 3 Cybersecurity Breaches

| Field | Details |
|---|---|
| **Type** | Thought Leadership / GRC Analysis |
| **Date** | 2025 |
| **Breaches Analyzed** | Equifax (2017), Capital One (2019), + 1 additional |

---

## Overview

Analyzed three landmark cybersecurity breaches through a GRC lens, identifying the governance failures, risk management gaps, and compliance weaknesses that enabled or worsened each incident. The analysis connects real-world breach consequences to preventable GRC control failures.

---

## Key Metrics

| Metric | Value |
|---|---|
| Breaches Analyzed | 3 |
| GRC Pillars Applied Per Breach | 3 (Governance, Risk, Compliance) |
| Equifax Total Cleanup Cost | $1.4 Billion+ |
| Capital One Records Exposed | 100 Million+ |
| Americans Affected (Equifax) | 148 Million |

---

## Equifax (2017)

**Scale:** 148 million Americans affected | **Cost:** $1.4B+

### What Happened
- An expired PKI certificate went undetected, disabling security monitoring
- A known Apache Struts vulnerability (CVE-2017-5638) was not patched
- Overly broad user permissions allowed lateral movement after initial compromise

### GRC Failures
| Pillar | Failure |
|---|---|
| **Governance** | No patch management governance; no certificate lifecycle tracking |
| **Risk** | Risk assessment failed to identify Apache Struts as a critical dependency |
| **Compliance** | Non-compliant with PCI DSS and NIST CSF patch management requirements |

---

## Capital One (2019)

**Scale:** 100M+ customer records exposed

### What Happened
- A former AWS employee exploited a misconfigured cloud firewall (SSRF vulnerability)
- The misconfiguration allowed access to AWS metadata and S3 bucket contents

### GRC Failures
| Pillar | Failure |
|---|---|
| **Governance** | Inadequate cloud configuration governance and change management |
| **Risk** | Insider/former-employee threat risk not formally assessed or controlled |
| **Compliance** | Insufficient access controls for cloud environments; no least-privilege enforcement |

---

## Key Takeaway

> All three breaches were **preventable** with proper GRC controls in place.

The common thread: organizations with mature GRC programs — including active patch management governance, role-based access control (RBAC), continuous monitoring, and formal vendor/cloud risk policies — significantly reduce both the likelihood and impact of incidents like these.

**Preventive controls that would have made a difference:**
- Patch management governance with SLA-based remediation timelines
- Role-Based Access Control (RBAC) enforcing least privilege
- Continuous security monitoring and anomaly detection
- Vendor and cloud environment risk policies with regular review

---

## Outcome

Published analysis connecting real-world breach consequences to specific GRC control gaps. Designed as a thought leadership piece demonstrating the business case for proactive GRC investment.
