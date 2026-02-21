## UK Care Home – ISO/IEC 27001-Aligned Risk Assessment

This project simulates an enterprise-level information security risk assessment conducted for a UK-based care home, aligned with:
- ISO/IEC 27001:2022
- UK GDPR
- Data Protection Act 2018
- CQC expectations
- NHS Data Security and Protection Toolkit (DSPT) (where applicable)

The assessment demonstrates structured risk management in accordance with:
- ISO 27001 Clause 4 – Context of the Organisation
- Clause 6 – Planning (Risk Assessment & Treatment)
- Clause 8 – Operation
- Annex A Controls
  
# 1.0 Context of the Organisation (ISO 27001 Clause 4)
# Internal Context
- 45 employees
- Outsourced IT support (MSP)
- Cloud-dependent care management system
- Limited in-house cybersecurity capability
# External Context
- UK GDPR compliance requirements
- CQC safeguarding standards
- Increasing ransomware targeting healthcare
- Supplier reliance (SaaS platforms)
# Interested Parties
- Residents & Families
- Care Staff
- Care Quality Commission (CQC)
- Information Commissioner’s Office (ICO)
- Software Vendors
- Insurance Providers

## 2️.0 ISMS Scope (ISO 27001 Clause 4.3)

The scope of this simulated ISMS includes:
- Resident care records
- Medication management system
- Payroll system
- Microsoft 365 environment
- On-premise infrastructure
- Third-party SaaS services

**Exclusions: Physical building security beyond IT-controlled systems.**

# 3️.0 ISO 27001 Risk Assessment Methodology (Clause 6.1.2)

The risk assessment followed ISO requirements:

- 1. Asset identification
- 2. Threat identification
- 3. Vulnerability identification
- 4. Impact analysis (CIA)
- 5. Likelihood assessment
- 6. Risk evaluation
- 7. Risk treatment decision

# Risk Formula

Risk Score = Likelihood (1–5) × Impact (1–5)

Risk Levels:

- 16–25 = High
- 9–15 = Medium
- 1–8 = Low
  
Risk acceptance criteria were defined by management.

# 4️.0 Risk Register (Aligned to ISO 27001 Clause 6.1)

| Risk ID | Asset             | Risk                | Likelihood | Impact | Score | Level  | Treatment |
| ------- | ----------------- | ------------------- | ---------- | ------ | ----- | ------ | --------- |
| R1      | Resident Records  | Ransomware          | 4          | 5      | 20    | High   | Mitigate  |
| R2      | Microsoft 365     | Phishing compromise | 4          | 4      | 16    | High   | Mitigate  |
| R3      | File Server       | Hardware failure    | 3          | 4      | 12    | Medium | Mitigate  |
| R4      | Payroll           | Credential theft    | 3          | 4      | 12    | Medium | Mitigate  |
| R5      | Medication System | SaaS outage         | 2          | 5      | 10    | Medium | Transfer  |
| R6      | CCTV              | Default credentials | 3          | 3      | 9     | Medium | Mitigate  |
| R7      | HR Files          | Insider misuse      | 2          | 4      | 8     | Low    | Accept    |

# 5️.0 Annex A Control Mapping (ISO 27001:2022)
| Risk ID | Relevant Annex A Control | Control Title                                   |
| ------- | ------------------------ | ----------------------------------------------- |
| R1      | A.8.13                   | Backup                                          |
| R1      | A.8.23                   | Web Filtering                                   |
| R2      | A.5.17                   | Authentication Information                      |
| R2      | A.8.2                    | Privileged Access Rights                        |
| R3      | A.8.14                   | Redundancy of Information Processing Facilities |
| R4      | A.5.18                   | Access Rights                                   |
| R5      | A.5.19                   | Supplier Relationships                          |
| R6      | A.7.2                    | Physical Entry Controls                         |
| R7      | A.6.3                    | Information Security Awareness                  |

# 6️.0  Statement of Risk Treatment (ISO 27001 Clause 6.1.3)

Risk treatment decisions:
- High risks must be mitigated immediately
- Medium risks mitigated within 6 months
- Low risks monitored or accepted
- Supplier-related risks may be transferred via contractual controls

# 7️.0 Executive Summary (Board-Level View)
# ISMS Maturity Level: Developing
The care home demonstrates informal security controls but lacks:

- Documented ISMS governance
- Formalised risk acceptance criteria
- Structured internal audit process
- Defined business continuity testing

# Key Enterprise Risks

- 1. Ransomware disrupting resident care
- 2. Phishing compromising Microsoft 365
- 3. Over-reliance on third-party SaaS providers

# 8️.0 Remediation Roadmap (ISO-Aligned)
# Phase 1 – Immediate (0–3 Months)
- Implement MFA (Annex A A.5.17)
- Deploy automated backups (A.8.13)
- Conduct staff security awareness training (A.6.3)
   Disable default credentials (A.8.2)

# Phase 2 – Short Term (3–6 Months)
- Develop Incident Response Plan (A.5.24)
- Conduct access review process (A.5.18)
- Establish supplier risk review framework (A.5.19)

# Phase 3 – Medium Term (6–12 Months)
- Implement internal audit programme (Clause 9.2)
- Conduct management review (Clause 9.3)
- Prepare for ISO 27001 certification readiness
