# Data Protection Impact Assessment (DPIA)

> **Template Status**: Beta | **Version**: [VERSION] | **Command**: `/arckit.dpia`

## Document Control

| Field | Value |
|-------|-------|
| **Document ID** | {document_id} |
| **Document Type** | Data Protection Impact Assessment |
| **Project** | [PROJECT_NAME] (Project [PROJECT_ID]) |
| **Classification** | [PUBLIC / OFFICIAL / OFFICIAL: Sensitive / SECRET] |
| **Status** | [DRAFT / IN_REVIEW / APPROVED / PUBLISHED / SUPERSEDED / ARCHIVED] |
| **Version** | [VERSION] |
| **Created Date** | [YYYY-MM-DD] |
| **Last Modified** | [YYYY-MM-DD] |
| **Review Cycle** | [Monthly / Quarterly / Annual / On-Demand] |
| **Next Review Date** | [YYYY-MM-DD] |
| **Owner** | [OWNER_NAME_AND_ROLE] |
| **Reviewed By** | [REVIEWER_NAME] on [DATE] or [PENDING] |
| **Approved By** | [APPROVER_NAME] on [DATE] or [PENDING] |
| **Distribution** | [DISTRIBUTION_LIST] |
| **Project Name** | [PROJECT_NAME] |
| **Assessment Date** | [ASSESSMENT_DATE] |
| **Privacy Officer** | [DPO_NAME] |
| **Data Controller** | [CONTROLLER_NAME] |
| **Author** | Enterprise Architect |

## Revision History

| Version | Date | Author | Changes | Approved By | Approval Date |
|---------|------|--------|---------|-------------|---------------|
| [VERSION] | [DATE] | ArcKit AI | Initial creation from `/arckit.[COMMAND]` command | [PENDING] | [PENDING] |

## Executive Summary

**Processing Activity**: [ACTIVITY_NAME]

**DPIA Outcome**: [LOW/MEDIUM/HIGH] residual risk to data subjects

**Approval Status**: [APPROVED/APPROVED WITH CONDITIONS/REJECTED/PENDING]

**Key Findings**:
- [Finding 1]
- [Finding 2]
- [Finding 3]

**Recommendation**: [Proceed/Do not proceed/Proceed with conditions]

**OAIC Consultation Required**: [YES/NO]

---

## 1. DPIA Screening Assessment

### 1.1 Screening Criteria (OAIC Privacy Impact Assessment Guide)

| # | Criterion (mapped to APPs) | YES/NO | Evidence |
|---|-----------|--------|----------|
| 1 | **Evaluation or scoring** including profiling and predicting (e.g., credit scoring, marketing preferences, location data, loyalty programs) — APP 6 (Use or disclosure) | [YES/NO] | [Evidence from requirements/data model] |
| 2 | **Automated decision-making with legal or similarly significant effect** (e.g., automatic refusal of credit, e-recruiting without human intervention) — APP 1 (Open and transparent management) | [YES/NO] | [Evidence] |
| 3 | **Systematic monitoring** of data subjects (e.g., CCTV, tracking, monitoring employee productivity/health, location tracking) — APP 3 (Collection of solicited personal information) | [YES/NO] | [Evidence] |
| 4 | **Sensitive information** (as defined in Privacy Act 1988: race, health, biometric, genetic; criminal record; children's data) — APP 3.3 (Sensitive information) | [YES/NO] | [Evidence from data model PII analysis] |
| 5 | **Processing on a large scale** (consider: number of data subjects, volume of data, duration, geographical extent) — APP 11 (Security) | [YES/NO] | [Evidence - N data subjects, N records, N years] |
| 6 | **Matching or combining datasets** from different sources in ways data subjects wouldn't reasonably expect — APP 6 (Use or disclosure) | [YES/NO] | [Evidence - list data sources] |
| 7 | **Data concerning vulnerable data subjects** (children, elderly, patients, employees, asylum seekers, those lacking capacity) — APP 3.4 | [YES/NO] | [Evidence - list vulnerable groups] |
| 8 | **Innovative use or application of new technological or organisational solutions** (AI/ML, blockchain, IoT, biometrics, facial recognition) — APP 1 (Open and transparent management) | [YES/NO] | [Evidence - list technologies] |
| 9 | **Processing that prevents data subjects from exercising a right or using a service/contract** (e.g., cannot opt out, no access to data, blocking from service) — APP 12 (Access), APP 13 (Correction) | [YES/NO] | [Evidence] |

**Screening Score**: [N]/9 criteria met

### 1.2 DPIA Necessity Decision

**Decision**: [DPIA REQUIRED / DPIA RECOMMENDED / DPIA NOT REQUIRED]

**Rationale**:
- If ≥2 criteria met → DPIA REQUIRED
- If processing involves special category data at scale → DPIA REQUIRED
- If innovative technology with unknown risks → DPIA REQUIRED
- [Specific rationale based on screening results]

**Decision Authority**: [NAME, ROLE]

**Decision Date**: [DATE]

---

## 2. Description of Processing

### 2.1 Nature of Processing

**What operations are being performed?**
- [ ] Collection
- [ ] Recording
- [ ] Organisation
- [ ] Structuring
- [ ] Storage
- [ ] Adaptation/alteration
- [ ] Retrieval
- [ ] Consultation
- [ ] Use
- [ ] Disclosure by transmission
- [ ] Dissemination
- [ ] Alignment/combination
- [ ] Restriction
- [ ] Erasure/destruction

**Processing Method**:
- [ ] Automated processing
- [ ] Manual processing
- [ ] Combination of automated and manual

**Profiling Involved**: [YES/NO]
- If YES, describe profiling activities: [DESCRIPTION]

**Automated Decision-Making**: [YES/NO]
- If YES, describe: [DESCRIPTION]
- Human oversight: [YES/NO - describe how]

### 2.2 Scope of Processing

#### What data are we processing?

**Personal Data Categories** (from Data Model):

| Entity ID | Entity Name | Data Categories | Sensitive Information? | PII Level |
|-----------|-------------|-----------------|-------------------|-----------|
| E-001 | [Entity Name] | Name, email, address | NO | HIGH |
| E-002 | [Entity Name] | Health records | YES (APP 3.3 Sensitive Information) | VERY HIGH |
| ... | ... | ... | ... | ... |

**Total Data Items**: [N] personal data fields across [M] entities

**Special Category Data**: [YES/NO]
- If YES: Race/ethnicity, Political opinions, Religious beliefs, Trade union membership, Genetic data, Biometric data, Health data, Sex life/orientation, Criminal convictions

**Children's Data**: [YES/NO]
- If YES: Age range [AGE_RANGE], volume [N children]

#### Whose data are we processing?

**Data Subject Categories** (from Stakeholder Analysis):

| Data Subject Type | Description | Volume | Vulnerable? |
|-------------------|-------------|--------|-------------|
| [Type 1] | [Description] | [N individuals] | [YES/NO] |
| [Type 2] | [Description] | [N individuals] | [YES/NO] |
| ... | ... | ... | ... |

**Total Data Subjects**: Approximately [N] individuals

**Vulnerable Groups**: [List any vulnerable populations]

#### How much data?

**Volume Metrics**:
- **Records**: [N] records
- **Data subjects**: [N] individuals
- **Storage size**: [N GB/TB]
- **Transaction rate**: [N] per day/month
- **Geographic scope**: [Australia-wide / Regional / Local / International]

**Scale Classification**: [Small scale / Large scale]
- Small scale: Fewer than 10,000 data subjects, limited geographic area, low volume
- Large scale: ≥10,000 data subjects, or national/international scope, or high volume

#### How long are we keeping it?

**Retention Periods** (from Data Model):

| Data Type | Retention Period | Legal Basis for Retention | Deletion Method |
|-----------|------------------|---------------------------|-----------------|
| [Data Type 1] | [N years] | [Legal requirement / Business need] | [Secure deletion / Anonymization] |
| [Data Type 2] | [N years] | [Legal requirement / Business need] | [Secure deletion / Anonymization] |

**Maximum Retention**: [N] years

**Automated Deletion**: [YES/NO - describe mechanism]

### 2.3 Context of Processing

#### Why are we processing this data?

**Processing Purpose** (from Requirements):

| Requirement ID | Purpose | Stakeholder Goal |
|----------------|---------|------------------|
| BR-001 | [Purpose description] | [Goal from stakeholder analysis] |
| FR-005 | [Purpose description] | [Goal] |
| ... | ... | ... |

**Primary Purpose**: [SUMMARY]

**Secondary Purposes**: [List any secondary uses]

#### What is the relationship with data subjects?

**Relationship Type**:
- [ ] Customer/client
- [ ] Employee
- [ ] Citizen/public service user
- [ ] Patient
- [ ] Student
- [ ] Supplier/partner
- [ ] Website visitor
- [ ] Other: [SPECIFY]

**Power Balance**:
- [ ] Equal relationship (e.g., commercial transaction)
- [ ] Imbalanced relationship (e.g., employer-employee, government-citizen)
- If imbalanced: Describe safeguards to protect data subjects: [SAFEGUARDS]

#### How much control do data subjects have?

**Control Mechanisms**:
- [ ] Consent can be withdrawn
- [ ] Can opt out of processing
- [ ] Can access their data (Subject Access Request)
- [ ] Can correct inaccurate data (rectification)
- [ ] Can request deletion (right to erasure)
- [ ] Can object to processing
- [ ] Can request restriction of processing
- [ ] Can port data to another controller
- [ ] Can object to automated decisions

**Limitations on Control**: [Describe any limitations and legal basis]

#### Would data subjects expect this processing?

**Reasonable Expectation Assessment**:
- **Transparency**: Are data subjects informed about processing? [YES/NO]
- **Privacy Notice**: Is a clear privacy notice provided? [YES/NO]
- **Expectation**: Would an average person in this context expect this processing? [YES/MAYBE/NO]

**If unexpected processing**: Describe additional safeguards: [SAFEGUARDS]

### 2.4 Purpose and Benefits

#### What do we want to achieve?

**Intended Outcomes** (from Stakeholder Goals):

| Stakeholder Goal | Processing Contribution | Measurable Benefit |
|------------------|------------------------|-------------------|
| [Goal G-001] | [How processing supports this] | [Quantifiable benefit] |
| [Goal G-002] | [How processing supports this] | [Quantifiable benefit] |

**Primary Benefit**: [SUMMARY]

#### Who benefits?

- [ ] Data subjects (describe: [HOW])
- [ ] Organisation (describe: [HOW])
- [ ] Society/public (describe: [HOW])
- [ ] Third parties (describe: [WHO and HOW])

---

## 3. Consultation

### 3.1 Privacy Officer (DPO) Consultation

**DPO Name**: [DPO_NAME]

**Date Consulted**: [DATE]

**DPO Advice**:
- [Advice point 1]
- [Advice point 2]
- [Advice point 3]

**DPO Recommendations**:
- [Recommendation 1]
- [Recommendation 2]

**How DPO Advice Addressed**: [SUMMARY]

### 3.2 Data Subject Consultation

**Consultation Method**:
- [ ] Survey
- [ ] Focus groups
- [ ] Public consultation
- [ ] User testing
- [ ] Privacy notice + feedback mechanism
- [ ] Not consulted (explain why: [REASON])

**Date(s) Consulted**: [DATE_RANGE]

**Number of Respondents**: [N] data subjects

**Key Feedback Received**:
1. [Feedback theme 1] - [N responses]
2. [Feedback theme 2] - [N responses]
3. [Feedback theme 3] - [N responses]

**Concerns Raised**:
- [Concern 1]
- [Concern 2]

**How Feedback Addressed**:
- [Action taken for concern 1]
- [Action taken for concern 2]

### 3.3 Stakeholder Consultation

**Stakeholders Consulted** (from Stakeholder RACI):

| Stakeholder | Role | Date Consulted | Feedback Summary |
|-------------|------|----------------|------------------|
| [Stakeholder 1] | [Role from RACI] | [DATE] | [Feedback] |
| [Stakeholder 2] | [Role from RACI] | [DATE] | [Feedback] |

**Key Stakeholder Concerns**:
- [Concern 1]
- [Concern 2]

**Resolution**: [How concerns addressed]

---

## 4. Necessity and Proportionality Assessment

### 4.1 Lawful Basis Assessment

**Lawful Basis under Australian Privacy Principles (APPs)**:

- [ ] **APP 3 — Collection**: Personal information is collected only where reasonably necessary for agency functions or activities
  - Collection purpose: [DESCRIBE purpose]
  - Reasonable necessity: [EXPLAIN why collection is necessary]
  - Collection method: [DESCRIBE — lawful, fair, not unreasonably intrusive]

- [ ] **APP 3.3 — Sensitive Information**: Consent obtained for collection of sensitive information (or exception applies)
  - Consent mechanism: [DESCRIBE]
  - Exception (if no consent): [CITE — required by law, enforcement, health/safety emergency, etc.]

- [ ] **APP 5 — Notification**: Individuals notified of collection at or before the time of collection
  - Privacy notice provided: [YES/NO]
  - Contents: Purpose, who else will receive, access/correction rights, overseas disclosure

- [ ] **APP 6 — Use or Disclosure**: Information used/disclosed only for primary purpose or directly related secondary purpose
  - Primary purpose: [DESCRIBE]
  - Secondary purposes: [DESCRIBE and justify]

- [ ] **APP 8 — Cross-border Disclosure**: Reasonable steps taken before disclosing personal information overseas
  - Overseas recipients: [DESCRIBE countries/entities]
  - Safeguards: [DESCRIBE]

- [ ] **APP 11 — Security**: Reasonable steps taken to protect personal information from misuse, interference, loss, unauthorised access
  - Security measures: [DESCRIBE]

**Justification for Chosen Basis**: [DETAILED EXPLANATION]

### 4.2 Sensitive Information Basis (APP 3.3)

**Applicable**: [YES/NO]

If YES, select condition(s) permitting collection of sensitive information:

- [ ] **(a) Individual consents** and information is reasonably necessary for functions/activities
- [ ] **(b) Required or authorised by Australian law** or court/tribunal order
- [ ] **(c) Enforcement related activity** by enforcement body
- [ ] **(d) Non-profit organisation** collecting from members related to organisation's activities
- [ ] **(e) Necessary to prevent serious threat** to life, health or safety
- [ ] **(f) Necessary for establishment, exercise or defence** of legal claims
- [ ] **(g) Necessary for diplomatic or consular functions**
- [ ] **(h) Necessary for defence force activities** outside Australia

**Privacy Act 1988 s16A condition**: [CITE specific exception if relying on exception to consent]

**Justification**: [DETAILED EXPLANATION]

### 4.3 Necessity Assessment

**Is processing necessary to achieve the purpose?**

| Question | Answer | Justification |
|----------|--------|---------------|
| Can we achieve the purpose without processing personal data? | [YES/NO] | [If NO, explain why personal data is essential] |
| Can we achieve the purpose with less personal data? | [YES/NO] | [If NO, explain why all data items are necessary] |
| Can we achieve the purpose with less intrusive processing? | [YES/NO] | [If NO, explain why current methods are least intrusive] |
| Can we achieve the purpose by processing data for less time? | [YES/NO] | [If NO, explain retention necessity] |

**Necessity Conclusion**: Processing is [NECESSARY/NOT NECESSARY]

**Alternatives Considered**:
1. [Alternative approach 1] - Rejected because: [REASON]
2. [Alternative approach 2] - Rejected because: [REASON]

### 4.4 Proportionality Assessment

**Is the processing proportionate to the purpose?**

**Data Minimization**:
- [ ] We only collect data that is adequate for the purpose
- [ ] We only collect data that is relevant for the purpose
- [ ] We do not collect excessive data
- Evidence: [List data items and justify each]

**Proportionality Factors**:

| Factor | Assessment | Score (1-5) |
|--------|------------|-------------|
| Severity of intrusion into private life | [Low/Medium/High] | [Score] |
| Benefits to data subjects | [Low/Medium/High] | [Score] |
| Benefits to organisation | [Low/Medium/High] | [Score] |
| Benefits to society | [Low/Medium/High] | [Score] |
| Reasonable alternatives exist | [Yes/No] | [Score] |

**Proportionality Conclusion**: Processing is [PROPORTIONATE/NOT PROPORTIONATE]

**Justification**: [DETAILED BALANCING EXPLANATION]

---

## 5. Risk Assessment to Data Subjects

**CRITICAL**: Assess risks to **individuals' rights and freedoms**, NOT organisational risks.

### 5.1 Risk Identification

**Risk Categories to Consider**:
- Physical harm (safety, health risks)
- Material damage (financial loss, fraud, identity theft, discrimination affecting employment/services)
- Non-material damage (distress, anxiety, reputational damage, loss of confidentiality, loss of control over personal data, discrimination, disadvantage)

### 5.2 Inherent Risks (Before Mitigation)

| Risk ID | Risk Description | Impact on Data Subjects | Likelihood | Severity | Risk Level | Risk Source |
|---------|------------------|-------------------------|------------|----------|------------|-------------|
| DPIA-001 | Unauthorised access to [data type] | [Description of harm to individuals] | [Low/Medium/High] | [Low/Medium/High/Very High] | [LOW/MEDIUM/HIGH/VERY HIGH] | Security vulnerability |
| DPIA-002 | Data breach exposing [data type] | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | [Source] |
| DPIA-003 | Inaccurate data leading to wrong decisions | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | Data quality |
| DPIA-004 | Excessive data retention | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | Retention policy |
| DPIA-005 | Third party misuse of data | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | Third party failure |
| DPIA-006 | Algorithmic bias/discrimination (if AI/ML) | [Description of harm to protected groups] | [Likelihood] | [Severity] | [Risk Level] | Algorithm design |
| DPIA-007 | Re-identification of anonymized data | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | De-anonymization attack |
| DPIA-008 | Function creep (use for unintended purposes) | [Description of harm] | [Likelihood] | [Severity] | [Risk Level] | Mission creep |

**Likelihood Scale**:
- **Low**: Unlikely to occur (0-33% chance)
- **Medium**: May occur (34-66% chance)
- **High**: Likely to occur (67-100% chance)

**Severity Scale** (Impact on Individuals):
- **Low**: Minimal or no impact; temporary inconvenience
- **Medium**: Significant inconvenience or distress; some financial loss; minor reputational impact
- **High**: Serious consequences; significant financial loss; significant reputational damage; psychological harm
- **Very High**: Irreversible harm; severe financial loss; severe psychological trauma; physical safety risk

**Risk Level Matrix**:

|            | Low Severity | Medium Severity | High Severity | Very High Severity |
|------------|-------------|-----------------|---------------|-------------------|
| **Low Likelihood**    | LOW  | LOW  | MEDIUM | HIGH |
| **Medium Likelihood** | LOW  | MEDIUM | HIGH | VERY HIGH |
| **High Likelihood**   | MEDIUM | HIGH | VERY HIGH | VERY HIGH |

### 5.3 Detailed Risk Analysis

**DPIA-001: [Risk Title]**

**Description**: [Detailed description of what could go wrong]

**Data Subjects Affected**: [Which groups/how many individuals]

**Harm to Individuals**:
- Physical: [Describe physical harm, if any]
- Material: [Describe financial/material harm, if any]
- Non-material: [Describe distress/reputational/discrimination harm, if any]

**Likelihood Analysis**: [Why is this likely/unlikely to happen?]

**Severity Analysis**: [Why would the impact be low/medium/high/very high?]

**Existing Controls**: [What controls are already in place, if any?]

[Repeat for each identified risk]

---

## 6. Mitigation Measures

### 6.1 Technical Measures

**Data Security**:
- [ ] **Encryption at rest** - [Specify: AES-256, database encryption, disk encryption]
- [ ] **Encryption in transit** - [Specify: TLS 1.3, VPN, secure protocols]
- [ ] **Pseudonymization** - [Describe: tokenization, hashing, key management]
- [ ] **Anonymization** - [Describe: k-anonymity, differential privacy, aggregation]
- [ ] **Access controls** - [Specify: RBAC, least privilege, MFA, SSO]
- [ ] **Audit logging** - [Specify: what is logged, retention period, monitoring]
- [ ] **Data masking** - [Describe: field-level masking, dynamic masking]
- [ ] **Secure deletion** - [Describe: cryptographic erasure, overwriting, destruction]

**Data Minimization**:
- [ ] **Collection limitation** - Only collect necessary data fields
- [ ] **Storage limitation** - Automated deletion after retention period
- [ ] **Processing limitation** - Restrict processing to stated purposes
- [ ] **Disclosure limitation** - Share only with authorized parties

**Technical Safeguards for AI/ML** (if applicable):
- [ ] **Bias testing** - Regular testing for discriminatory outcomes
- [ ] **Model explainability** - LIME, SHAP, or other interpretability tools
- [ ] **Human oversight** - Human review of automated decisions
- [ ] **Fairness metrics** - Demographic parity, equal opportunity, calibration

**Privacy-Enhancing Technologies**:
- [ ] **Differential privacy** for statistical analysis
- [ ] **Homomorphic encryption** for computation on encrypted data
- [ ] **Secure multi-party computation** for collaborative analysis
- [ ] **Zero-knowledge proofs** for verification without disclosure

### 6.2 Organisational Measures

**Policies and Procedures**:
- [ ] **Privacy Policy** - Clear, accessible privacy notice for data subjects
- [ ] **Data Protection Policy** - Internal policy for staff
- [ ] **Retention and Disposal Policy** - Defined retention periods and deletion procedures
- [ ] **Data Breach Response Plan** - Notifiable Data Breaches (NDB) scheme notification to OAIC, data subject notification
- [ ] **Data Subject Rights Procedures** - SAR, rectification, erasure, portability processes

**Training and Awareness**:
- [ ] **Staff training** - Privacy Act 1988 awareness, privacy principles, secure handling
- [ ] **Role-specific training** - Additional training for those with data access
- [ ] **Regular refresher training** - Frequency: [SPECIFY]

**Vendor Management**:
- [ ] **Data Processing Agreements (DPAs)** - Contracts with all processors
- [ ] **Vendor due diligence** - Security and privacy assessments before engagement
- [ ] **Regular audits** - Annual audits of processor compliance
- [ ] **Data transfer safeguards** - SCCs for international transfers

**Governance**:
- [ ] **Privacy Officer (DPO)** - DPO appointed and accessible
- [ ] **Privacy by Design** - Privacy built into system design from the start
- [ ] **Privacy by Default** - Strictest privacy settings by default
- [ ] **Regular reviews** - DPIA reviewed every [N] months or on significant change

**Data Subject Rights Facilitation**:
- [ ] **Subject Access Request (SAR) process** - Response within 1 month
- [ ] **Rectification process** - Mechanism to correct inaccurate data
- [ ] **Erasure process** - "Right to be forgotten" implementation
- [ ] **Portability process** - Export data in machine-readable format
- [ ] **Objection process** - Mechanism to object to processing
- [ ] **Restriction process** - Mechanism to restrict processing

### 6.3 Mitigation Mapping

**Risk-by-Risk Mitigation**:

| Risk ID | Risk Title | Mitigations Applied | Responsibility | Implementation Date |
|---------|------------|---------------------|----------------|---------------------|
| DPIA-001 | Unauthorised access | Encryption (AES-256), MFA, RBAC, Audit logging | Security Team | [DATE] |
| DPIA-002 | Data breach | Encryption, DLP, Incident response plan, Staff training | Security + DPO | [DATE] |
| DPIA-003 | Inaccurate data | Data validation, Rectification process, Regular audits | Data Steward | [DATE] |
| DPIA-004 | Excessive retention | Automated deletion, Retention policy, Regular reviews | Data Governance | [DATE] |
| DPIA-005 | Third party misuse | DPAs, Vendor audits, Limited sharing, Contractual controls | Legal + Procurement | [DATE] |
| DPIA-006 | Algorithmic bias | Bias testing, Fairness metrics, Human oversight, Diverse training data | Data Science + Ethics Board | [DATE] |

### 6.4 Residual Risk Assessment

**Risks After Mitigation**:

| Risk ID | Risk Title | Mitigations | Residual Likelihood | Residual Severity | Residual Risk Level | Acceptable? | Justification |
|---------|------------|-------------|---------------------|-------------------|---------------------|-------------|---------------|
| DPIA-001 | Unauthorised access | Encryption + MFA + RBAC + Audit logs | Low | Medium | **MEDIUM** | YES | Risk reduced to tolerable level with strong controls |
| DPIA-002 | Data breach | Encryption + DLP + Incident plan + Training | Low | High | **MEDIUM** | YES | Cannot eliminate entirely; mitigations are industry best practice |
| DPIA-003 | Inaccurate data | Validation + Rectification + Audits | Medium | Low | **LOW** | YES | Low impact; regular audits catch issues |
| DPIA-004 | Excessive retention | Automated deletion + Policy | Low | Low | **LOW** | YES | Technical controls ensure compliance |
| DPIA-005 | Third party misuse | DPAs + Audits + Limited sharing | Low | Medium | **MEDIUM** | YES | Contractual and technical controls in place |
| DPIA-006 | Algorithmic bias | Bias testing + Fairness + Oversight | Medium | Medium | **MEDIUM** | YES (with monitoring) | Ongoing monitoring and human oversight required |

**Overall Residual Risk Level**: [LOW/MEDIUM/HIGH/VERY HIGH]

**Acceptability Assessment**:
- [ ] All residual risks are LOW or MEDIUM → ACCEPTABLE
- [ ] Some residual risks are HIGH → ACCEPTABLE WITH CONDITIONS (describe conditions)
- [ ] Any residual risks are VERY HIGH → NOT ACCEPTABLE (OAIC consultation required)

**Conditions for Acceptance** (if applicable):
1. [Condition 1]
2. [Condition 2]

---

## 7. OAIC Prior Consultation

**OAIC Consultation Required**: [YES/NO]

**Trigger**: OAIC prior consultation is required if:
- Residual risk remains **HIGH** or **VERY HIGH** after mitigation, AND
- Processing will go ahead despite the high residual risk

**OAIC Consultation Details** (if required):

| Field | Value |
|-------|-------|
| OAIC Reference Number | [REF-NUMBER] |
| Consultation Date | [DATE] |
| OAIC Case Officer | [NAME] |
| OAIC Advice Received | [DATE] |
| OAIC Recommendations | [SUMMARY] |
| OAIC Approval | [APPROVED/APPROVED WITH CONDITIONS/NOT APPROVED] |
| Conditions | [LIST CONDITIONS] |
| How Conditions Addressed | [SUMMARY] |

**OAIC Advice Summary**:
- [Advice point 1]
- [Advice point 2]
- [Advice point 3]

---

## 8. Sign-Off and Approval

### 8.1 DPIA Approval

| Role | Name | Decision | Date | Signature |
|------|------|----------|------|-----------|
| **Privacy Officer** | [DPO_NAME] | [Approved/Approved with conditions/Not approved] | [DATE] | [SIGNATURE] |
| **Data Controller** | [CONTROLLER_NAME] | [Approved/Approved with conditions/Not approved] | [DATE] | [SIGNATURE] |
| **Senior Responsible Owner** | [SRO_NAME] | [Approved/Approved with conditions/Not approved] | [DATE] | [SIGNATURE] |

### 8.2 Conditions of Approval

**Conditions** (if any):
1. [Condition 1]
2. [Condition 2]

**How Conditions Will Be Met**:
- [Action for condition 1] - Responsibility: [NAME] - Due: [DATE]
- [Action for condition 2] - Responsibility: [NAME] - Due: [DATE]

### 8.3 Final Decision

**Decision**: [PROCEED / DO NOT PROCEED / PROCEED WITH CONDITIONS]

**Rationale**: [JUSTIFICATION FOR DECISION]

**Effective Date**: [DATE processing can commence]

---

## 9. Integration with Information Security Management

### 9.1 Link to Security Controls

**Security Assessment Reference**: `projects/{project_id}/ARC-{PROJECT_ID}-SBD-v*.md`

**DPIA Mitigations → Security Controls Mapping**:

| DPIA Mitigation | Security Control | ACSC CAF Principle | Implementation Status |
|-----------------|------------------|--------------------|-----------------------|
| Encryption at rest | Data security (encryption) | A.3 Asset Management | [Implemented/Planned] |
| Access controls | Identity and access management | B.1 Identity and Access | [Implemented/Planned] |
| Audit logging | Monitoring and audit | A.1 Governance | [Implemented/Planned] |
| Staff training | Security awareness | C.1 People | [Implemented/Planned] |

**Security Controls Feed into DPIA**: Security controls reduce likelihood of unauthorized access, data breach, and misuse risks.

### 9.2 Link to Risk Register

**Risk Register Reference**: `projects/{project_id}/ARC-{PROJECT_ID}-RISK-v*.md`

**DPIA Risks to Add to Risk Register**:

| DPIA Risk ID | Risk Register ID | Risk Category | Owner | Treatment |
|--------------|------------------|---------------|-------|-----------|
| DPIA-001 | RISK-SEC-001 | Technology Risk | CISO | Treat (mitigate) |
| DPIA-002 | RISK-COMP-001 | Compliance Risk | DPO | Treat (mitigate) |
| DPIA-006 | RISK-REP-001 | Reputational Risk | CDO | Treat (mitigate) |

---

## 10. Review and Monitoring

### 10.1 Review Triggers

**DPIA must be reviewed when**:
- [ ] Significant change to processing (new data, new purpose, new systems)
- [ ] New technology introduced
- [ ] New risks identified (e.g., new attack vectors, regulatory changes)
- [ ] Data breach or security incident occurs
- [ ] OAIC guidance changes
- [ ] Data subjects raise concerns
- [ ] Periodic review date reached

**Periodic Review Frequency**: Every [6/12/24] months

### 10.2 Review Schedule

| Review Type | Frequency | Next Review Date | Responsibility |
|-------------|-----------|------------------|----------------|
| **Periodic review** | [N] months | [DATE] | DPO |
| **Post-implementation review** | 3 months after go-live | [DATE] | Enterprise Architect |
| **Annual review** | Annually | [DATE] | Data Controller |

### 10.3 Monitoring Activities

**Ongoing Monitoring**:
- [ ] Track number of SARs received and response times
- [ ] Track data breaches and near-misses
- [ ] Monitor audit logs for unauthorized access attempts
- [ ] Review algorithmic bias metrics (if AI/ML)
- [ ] Review data subject complaints
- [ ] Track compliance with retention periods

**Monitoring Metrics**:

| Metric | Target | Measurement Frequency | Responsibility |
|--------|--------|----------------------|----------------|
| SAR response time | <1 month | Monthly | DPO |
| Data breaches | 0 | Continuous | Security Team |
| Unauthorized access attempts | <10/month | Weekly | Security Team |
| Algorithmic bias metrics | Fairness ratio >0.8 | Quarterly | Data Science Team |

### 10.4 Change Management

**Change Control Process**:
1. Any change to processing must be assessed for DPIA impact
2. If change is significant (new data, new purpose, new risk), DPIA must be updated
3. Updated DPIA must be re-approved by DPO and Data Controller
4. Data subjects must be notified of significant changes

**Change Log**:

| Change Date | Change Description | DPIA Impact | Updated Sections | Approved By |
|-------------|-------------------|-------------|------------------|-------------|
| [DATE] | [Change] | [Significant/Minor/None] | [Sections] | [NAME] |

---

## 11. Traceability to ArcKit Artifacts

### 11.1 Source Artifacts

**This DPIA was generated from**:

| Artifact | Location | Information Extracted |
|----------|----------|----------------------|
| **Architecture Principles** | `projects/000-global/ARC-000-PRIN-v*.md` | Privacy by Design, Data Minimization principles |
| **Data Model** | `projects/{project_id}/ARC-{PROJECT_ID}-DATA-v*.md` | Entities, PII inventory, special category data, Privacy Act 1988 lawful basis, retention periods |
| **Requirements** | `projects/{project_id}/ARC-{PROJECT_ID}-REQ-v*.md` | Data requirements (DR-xxx), processing purposes |
| **Stakeholder Analysis** | `projects/{project_id}/ARC-{PROJECT_ID}-STKE-v*.md` | Data subject categories, vulnerable groups, RACI for data governance roles |
| **Risk Register** | `projects/{project_id}/ARC-{PROJECT_ID}-RISK-v*.md` | Existing data protection risks |
| **Secure by Design Assessment** | `projects/{project_id}/ARC-*-SECD-*.md` | Security controls used as DPIA mitigations |

### 11.2 Traceability Matrix: Data → Requirements → DPIA

| Data Model Entity | PII Level | DR Requirement | Processing Purpose | DPIA Risk(s) | Lawful Basis |
|-------------------|-----------|----------------|-------------------|-------------|--------------|
| E-001: [Entity] | HIGH | DR-001 | [Purpose from requirement] | DPIA-001, DPIA-002 | [APP 3 basis] |
| E-002: [Entity] | VERY HIGH (Sensitive) | DR-003 | [Purpose] | DPIA-002, DPIA-004 | [APP 3 + APP 3.3 basis] |

### 11.3 Traceability Matrix: Stakeholder → Data Subject → Rights

| Stakeholder | Data Subject Type | Volume | Rights Processes Implemented | Vulnerability Safeguards |
|-------------|-------------------|--------|------------------------------|--------------------------|
| [Stakeholder 1] | [Type] | [N] | SAR, Rectification, Erasure | [Safeguards if vulnerable] |
| [Stakeholder 2] | [Type] | [N] | SAR, Rectification, Erasure, Portability | [Safeguards] |

### 11.4 Downstream Artifacts Informed by DPIA

**This DPIA informs**:

| Artifact | How DPIA Informs It |
|----------|---------------------|
| **Risk Register** | DPIA risks (DPIA-001, etc.) added as data protection/compliance risks |
| **Secure by Design Assessment** | DPIA mitigations become security control requirements |
| **Vendor HLD Review** | Vendor design must address DPIA risks and implement mitigations |
| **Vendor DLD Review** | Detailed technical controls must match DPIA mitigation requirements |
| **AI Playbook Assessment** | DPIA algorithmic bias findings inform AI ethics assessment |
| **Service Assessment (DTA)** | DPIA demonstrates Point 5 (data and privacy) compliance |
| **Procurement (SOW)** | DPIA requirements flow into vendor RFP requirements |

---

## 12. Data Subject Rights Implementation

### 12.1 Rights Checklist

**Right of Access (APP 12 — Access to personal information)**:
- [ ] Process implemented: [Describe access request process]
- [ ] Response time: Within 30 days (as per OAIC guidance)
- [ ] Identity verification: [Describe verification method]
- [ ] Information provided: Copy of personal information held by the agency
- [ ] Free of charge or reasonable charge for access

**Right to Correction (APP 13 — Correction of personal information)**:
- [ ] Process implemented: [Describe correction process]
- [ ] Verification: [How accuracy is verified]
- [ ] Notification: Associated entities notified of corrections

**Right to Erasure / De-identification**:
- [ ] Process implemented: [Describe deletion/de-identification process]
- [ ] De-identification: Information de-identified when no longer needed for purpose (APP 11.2)
- [ ] Exceptions: [When erasure cannot be granted - legal obligation, public interest, etc.]

**Right to Opt-Out of Direct Marketing (APP 7)**:
- [ ] Process implemented: [Describe opt-out mechanism]
- [ ] Opt-out must be facilitated at no cost

**Right to Anonymity / Pseudonymity (APP 2)**:
- [ ] Applicable: [YES/NO - individuals have option of not identifying themselves where practicable]
- [ ] Process implemented: [Describe how anonymity/pseudonymity is offered]
- [ ] Exceptions: [Where required by law or impracticable]

**Right to Know About Cross-Border Disclosure (APP 8)**:
- [ ] Process implemented: [Describe notification of overseas disclosure]
- [ ] Countries listed in privacy notice: [YES/NO]

**Rights Related to Automated Decision-Making**:
- [ ] Applicable: [YES/NO - is there solely automated decision-making?]
- [ ] Safeguards: Human oversight, explanation, ability to challenge decision
- [ ] Process: [Describe how individuals can request human review]

### 12.2 Rights Fulfillment Procedures

**Standard Operating Procedures**:
1. **Receipt**: Rights requests received via [email/web form/postal address]
2. **Verification**: Identity verified using [method]
3. **Logging**: Request logged in [system] with unique reference number
4. **Acknowledgement**: Acknowledgement sent within [N] days
5. **Retrieval**: Data retrieved from [systems/databases]
6. **Review**: Legal/DPO review for exemptions or complexities
7. **Response**: Response provided within 1 month
8. **Escalation**: Complex requests escalated to DPO

**Training**: Staff trained on rights fulfillment - [Training frequency]

---

## 13. International Data Transfers

**Applicable**: [YES/NO]

If YES:

### 13.1 Transfer Details

| Recipient | Country | Data Transferred | Purpose | Volume | Adequacy Decision? |
|-----------|---------|------------------|---------|--------|-------------------|
| [Recipient 1] | [Country] | [Data types] | [Purpose] | [N records] | [YES/NO] |
| [Recipient 2] | [Country] | [Data types] | [Purpose] | [N records] | [YES/NO] |

### 13.2 Transfer Safeguards

**For countries WITH Australian bilateral data arrangement**:
- [ ] No additional safeguards required beyond standard DPIA measures

**For countries WITHOUT adequacy decision**:
- [ ] **Standard Contractual Clauses (SCCs)** - OAIC-approved transfer mechanisms signed with recipient
  - SCC version: [OAIC-approved transfer mechanisms]
  - Date signed: [DATE]
  - Recipient guarantees: [Summary of guarantees]

- [ ] **Binding Corporate Rules (BCRs)** - Approved BCRs in place
  - BCR approval date: [DATE]
  - OAIC reference: [REF]

- [ ] **Derogations** (only in exceptional circumstances)
  - Explicit consent obtained: [YES/NO]
  - Necessary for contract performance: [YES/NO]
  - Necessary for legal claims: [YES/NO]

### 13.3 Transfer Risk Assessment

**Additional risks from international transfer**:
- Foreign government access to data: [Assessment]
- Different legal protections: [Assessment]
- Enforcement challenges: [Assessment]

**Additional safeguards**:
- [Safeguard 1]
- [Safeguard 2]

---

## 14. Children's Data (if applicable)

**Processing Children's Data**: [YES/NO]

If YES:

### 14.1 Age Verification

**Age Threshold**: [13/16] years (online services)

**Age Verification Method**: [Describe verification mechanism]

**Parental Consent**: [Describe parental consent mechanism for children under threshold]

### 14.2 Additional Safeguards for Children

- [ ] **Privacy notice for children** - Age-appropriate language, simplified explanation
- [ ] **Minimization** - Only essential data collected from children
- [ ] **No profiling** - Children's data not used for profiling/marketing (unless consent + child's best interests)
- [ ] **No AI decision-making** - No solely automated decisions affecting children
- [ ] **Secure processing** - Enhanced security measures for children's data
- [ ] **Timely deletion** - Children's data deleted when no longer necessary
- [ ] **No sharing** - Children's data not shared without parental consent

### 14.3 Best Interests Assessment

**Assessment**: Is processing in the child's best interests? [YES/NO]

**Justification**: [Explain how processing benefits children and does not cause harm]

---

## 15. Algorithmic/AI Processing (if applicable)

**Algorithmic Processing**: [YES/NO]

If YES, also complete `/arckit.ai-playbook` and `/arckit.atrs` assessments.

### 15.1 Algorithm Description

**Algorithm Type**:
- [ ] Rule-based system
- [ ] Statistical model
- [ ] Machine learning (supervised/unsupervised/reinforcement)
- [ ] Deep learning
- [ ] Natural language processing
- [ ] Computer vision
- [ ] Other: [SPECIFY]

**Processing Type**:
- [ ] Profiling
- [ ] Prediction
- [ ] Classification
- [ ] Recommendation
- [ ] Automated decision-making
- [ ] Anomaly detection

**Human Oversight**:
- [ ] Fully automated (no human review)
- [ ] Human-in-the-loop (human can override)
- [ ] Human-on-the-loop (human monitors and can intervene)

### 15.2 Algorithmic Bias Assessment

**Protected Characteristics Considered**:
- [ ] Age
- [ ] Disability
- [ ] Gender reassignment
- [ ] Marriage and civil partnership
- [ ] Pregnancy and maternity
- [ ] Race
- [ ] Religion or belief
- [ ] Sex
- [ ] Sexual orientation

**Bias Testing**:
- [ ] Training data reviewed for bias
- [ ] Fairness metrics calculated (demographic parity, equal opportunity, equalized odds)
- [ ] Disparate impact analysis conducted
- [ ] Regular monitoring for bias in production

**Bias Mitigation**:
- [ ] Diverse training data
- [ ] Fairness constraints in model
- [ ] Human review of edge cases
- [ ] Regular retraining
- [ ] Explainability tools (LIME, SHAP)

### 15.3 Explainability and Transparency

**Explainability Level**:
- [ ] Black box (no explanation possible)
- [ ] Limited explainability (feature importance)
- [ ] Full explainability (decision path visible)

**Explanation Mechanism**:
- [Describe how decisions are explained to data subjects]

**ATRS Compliance**: [Link to ATRS record at `projects/{project_id}/ARC-{PROJECT_ID}-ATRS-v*.md`]

---

## 16. Summary and Conclusion

### 16.1 Key Findings

**Processing Summary**:
- Processing [N] categories of personal data
- Processing [N] special category data types
- Affecting [N] data subjects
- For purposes: [List primary purposes]
- Collection basis: [APP 3 basis]
- Sensitive information basis: [APP 3.3 basis, if applicable]

**Risk Summary**:
- [N] risks identified
- [N] HIGH risks before mitigation
- [N] MEDIUM risks after mitigation
- [N] HIGH risks after mitigation (if any)
- Overall residual risk: [LOW/MEDIUM/HIGH]

**Compliance Summary**:
- [ ] Necessity and proportionality demonstrated
- [ ] Lawful basis identified
- [ ] Data subjects consulted
- [ ] DPO consulted
- [ ] Risks identified and mitigated
- [ ] Data subject rights processes in place
- [ ] Security measures implemented
- [ ] Review schedule established

### 16.2 Recommendations

**Recommendations**:
1. [Recommendation 1]
2. [Recommendation 2]
3. [Recommendation 3]

**Actions Required Before Go-Live**:

| Action | Responsibility | Due Date | Status |
|--------|----------------|----------|--------|
| [Action 1] | [Role] | [DATE] | [Not Started/In Progress/Complete] |
| [Action 2] | [Role] | [DATE] | [Status] |

### 16.3 Final Conclusion

**Conclusion**: [PROCEED / DO NOT PROCEED / PROCEED WITH CONDITIONS]

**Rationale**: [Summary justification]

**Conditions** (if any):
- [Condition 1]
- [Condition 2]

**Sign-Off**: This DPIA has been completed and approved. Processing may commence subject to conditions above.

---

## External References

| Document | Type | Source | Key Extractions | Path |
|----------|------|--------|-----------------|------|
| *None provided* | — | — | — | — |

---

## Generation Metadata

**Generated by**: ArcKit `/arckit.dpia` command
**Generated on**: [DATE]
**ArcKit Version**: [VERSION]
**Project**: [PROJECT_NAME] (Project [PROJECT_ID])
**Model**: [AI_MODEL]

**Traceability**: This DPIA is traceable to architecture principles, data model, requirements, stakeholders, and risk register via the ArcKit governance framework.

---

## Appendix A: OAIC DPIA Screening Checklist

Full screening questionnaire (9 criteria) with detailed YES/NO/N/A responses:

1. ☐ Evaluation or scoring (including profiling)
2. ☐ Automated decision-making with legal/significant effect
3. ☐ Systematic monitoring
4. ☐ Sensitive data or highly personal data
5. ☐ Large scale processing
6. ☐ Matching or combining datasets
7. ☐ Vulnerable data subjects
8. ☐ Innovative technology
9. ☐ Processing prevents exercising rights

---

## Appendix B: OAIC PIA Requirements Checklist

| OAIC PIA Requirement | Addressed in Section | Complete? |
|------------------------|---------------------|-----------|
| Description of personal information flows | Section 2 | ✓ |
| Purposes of collection and use | Section 2.4 | ✓ |
| Assessment of necessity and proportionality | Section 4 | ✓ |
| Assessment of privacy risks to individuals | Section 5 | ✓ |
| Measures to address risks | Section 6 | ✓ |
| Security safeguards (APP 11) | Section 6 | ✓ |
| Demonstrate compliance with all 13 APPs | Throughout | ✓ |

---

## Appendix C: Australian Privacy Principles (APPs) Compliance

**Privacy Act 1988 — 13 Australian Privacy Principles**:

| APP | Principle | Assessment | Evidence |
|-----|-----------|------------|----------|
| **APP 1** | Open and transparent management | [COMPLIANT/NON-COMPLIANT/PARTIAL] | APP privacy policy maintained; DPIA completed |
| **APP 2** | Anonymity and pseudonymity | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Option for anonymity where practicable |
| **APP 3** | Collection of solicited personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Only reasonably necessary information collected (Section 4.3) |
| **APP 4** | Dealing with unsolicited personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Process to assess and destroy unsolicited information |
| **APP 5** | Notification of collection | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Privacy notice provided at collection (Section 2.3) |
| **APP 6** | Use or disclosure | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Purposes clearly defined in Section 2.4; no function creep |
| **APP 7** | Direct marketing | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Opt-out mechanism in place (Section 12.1) |
| **APP 8** | Cross-border disclosure | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Overseas transfers assessed in Section 13 |
| **APP 9** | Adoption, use or disclosure of government identifiers | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Government identifiers handled per requirements |
| **APP 10** | Quality of personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Data validation in Section 6.1; correction process in Section 12.1 |
| **APP 11** | Security of personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Security measures in Section 6.1; encryption, access controls |
| **APP 12** | Access to personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Access process in Section 12.1 |
| **APP 13** | Correction of personal information | [COMPLIANT/NON-COMPLIANT/PARTIAL] | Correction process in Section 12.1 |

---

## Appendix D: Glossary

| Term | Definition |
|------|------------|
| **Data Subject** | An identified or identifiable natural person whose personal data is being processed |
| **Data Controller** | The organisation that determines the purposes and means of processing personal data |
| **Data Processor** | An organisation that processes personal data on behalf of the controller |
| **Personal Data** | Any information relating to an identified or identifiable natural person |
| **Sensitive Information** | Sensitive personal information (race, health, biometric, etc.) requiring APP 3.3 basis |
| **Processing** | Any operation performed on personal data (collection, storage, use, disclosure, deletion) |
| **Profiling** | Automated processing to evaluate personal aspects (predict performance, behaviour, preferences) |
| **Pseudonymization** | Processing that prevents identification without additional information kept separately |
| **Anonymization** | Irreversibly removing identifying information so re-identification is not possible |
| **Collection Basis** | Legal ground for collection under APP 3 (reasonably necessary for functions/activities, required by law, consent for sensitive information) |
| **DPIA** | Data Protection Impact Assessment - required for high-risk processing |
| **OAIC** | Office of the Australian Information Commissioner - Australian data protection supervisory authority |
| **Privacy Act 1988** | Australian federal privacy legislation establishing the Australian Privacy Principles (APPs) |
| **APPs** | 13 Australian Privacy Principles governing the handling of personal information |
| **SCC** | Standard Contractual Clauses - mechanism for international data transfers |

---

**END OF DPIA**