# Australian AI Ethics Framework Assessment

> **Template Status**: Alpha | **Version**: [VERSION] | **Command**: `/arckit.ai-playbook`

## Document Control

| Field | Value |
|-------|-------|
| **Document ID** | ARC-[PROJECT_ID]-AIPB-v[VERSION] |
| **Document Type** | Australian AI Ethics Framework Assessment |
| **Project** | [PROJECT_NAME] (Project [PROJECT_ID]) |
| **Classification** | [PUBLIC / OFFICIAL / OFFICIAL: Sensitive / SECRET] |
| **Status** | [DRAFT / IN_REVIEW / APPROVED / PUBLISHED / SUPERSEDED / ARCHIVED] |
| **Version** | [VERSION] |
| **Created Date** | [YYYY-MM-DD] |
| **Last Modified** | [YYYY-MM-DD] |
| **Review Cycle** | [Monthly / Quarterly / Annual / On-Demand] |
| **Next Review Date** | [YYYY-MM-DD] |
| **Owner** | [OWNER_NAME_AND_ROLE] |
| **Reviewed By** | [REVIEWER_NAME] ([YYYY-MM-DD]) or PENDING |
| **Approved By** | [APPROVER_NAME] ([YYYY-MM-DD]) or PENDING |
| **Distribution** | [DISTRIBUTION_LIST] |
| **Department/Agency** | [Department] |
| **AI System** | [Name/Description of AI System] |
| **Assessor** | [Name/Role] |
| **Risk Level** | [High-Risk / Medium-Risk / Low-Risk] |

## Revision History

| Version | Date | Author | Changes | Approved By | Approval Date |
|---------|------|--------|---------|-------------|---------------|
| [VERSION] | [DATE] | ArcKit AI | Initial creation from `/arckit.ai-playbook` command | PENDING | PENDING |

---

## Executive Summary

**Overall Compliance**: [Score/8] principles compliant

**Risk Assessment**:
- [ ] HIGH-RISK (fully automated decisions affecting rights, safety, health)
- [ ] MEDIUM-RISK (significant impact with human oversight)
- [ ] LOW-RISK (productivity tools, administrative tasks)

**Status**:
- COMPLIANT (7-8 principles met)
- PARTIALLY COMPLIANT (5-6 principles met)
- NON-COMPLIANT (< 5 principles met)

**Critical Issues**: [Number] blocking issues
**Go/No-Go Decision**: [ ] APPROVED / [ ] APPROVED WITH CONDITIONS / [ ] REJECTED

---

## AI System Overview

### What is the AI System?

**System Name**: [Name]

**Purpose**: [What problem does it solve?]

**Type of AI**:
- [ ] Generative AI (e.g., Large Language Models, image generation)
- [ ] Predictive AI (e.g., risk scoring, forecasting)
- [ ] Computer Vision (e.g., image recognition, object detection)
- [ ] Natural Language Processing (e.g., sentiment analysis, translation)
- [ ] Recommendation System
- [ ] Robotic Process Automation with AI
- [ ] Other: [Specify]

**Use Case**:
[Describe how the AI will be used in government operations]

**Users**:
- Internal users: [Who in government uses it?]
- External users: [Citizens, businesses affected?]
- Affected population: [Who is impacted by decisions?]

**Decision Authority**:
- [ ] AI makes recommendations, humans decide
- [ ] AI makes decisions with human review
- [ ] AI makes autonomous decisions (HIGH-RISK - justify carefully)

---

## The 8 Australian AI Ethics Principles Assessment

### Principle 1: Human, Societal and Environmental Wellbeing

**Principle**: AI systems should benefit individuals, society and the environment. Throughout their lifecycle, AI systems should be used in ways that are beneficial to individuals, society and the environment, including future generations.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Positive societal impact assessment completed
- [ ] Environmental impact considered (carbon footprint of AI compute and infrastructure)
- [ ] Benefits distributed fairly across society
- [ ] Negative impacts identified and mitigated
- [ ] Alignment with public values and community expectations
- [ ] Impact on future generations considered
- [ ] Contribution to public good documented

**Societal and Environmental Impact**:
| Impact | Positive/Negative | Magnitude | Mitigation/Enhancement |
|--------|-------------------|-----------|------------------------|
| [Improved service access] | Positive | High | [Proactively promote to underserved] |
| [Job displacement] | Negative | Medium | [Reskilling programs, redeployment] |
| [Environmental (compute)] | Negative | Low | [Efficient models, renewable energy] |

**Public Good Assessment**:
- [ ] Solves real problem for citizens
- [ ] Accessible to all (not just tech-savvy)
- [ ] Maintains human dignity and autonomy
- [ ] Strengthens democratic values
- [ ] Does not disproportionately harm vulnerable groups
- [ ] Environmental sustainability considered

**Findings**:
[Describe how the AI system benefits individuals, society and the environment]

**Gaps**:
[List areas where wellbeing impacts need further assessment or mitigation]

**Score**: ___/10

---

### Principle 2: Human-Centred Values

**Principle**: AI systems should respect human rights, diversity, and the autonomy of individuals. Throughout their lifecycle, AI systems should respect human rights, diversity, and the autonomy of individuals.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Human rights impact assessment completed
- [ ] Human autonomy preserved (people can override or opt out of AI decisions)
- [ ] Diversity and inclusion considerations documented
- [ ] Cultural sensitivity assessed (including First Nations perspectives)
- [ ] Meaningful human oversight implemented
- [ ] Users can choose to interact with a human instead
- [ ] AI limitations communicated to affected persons

**Human Oversight Model**:
- [ ] **Human-in-the-loop**: Human reviews EVERY decision before implementation
- [ ] **Human-on-the-loop**: Human reviews decisions periodically/randomly
- [ ] **Human-in-command**: Human can override AI decisions at any time
- [ ] **Fully automated**: AI acts autonomously (HIGH-RISK - justify!)

**Human Review Requirements**:
| Decision Type | Review Requirement | Reviewer Role | Escalation Path |
|---------------|-------------------|---------------|-----------------|
| [High-impact decisions] | Every decision | [Senior officer] | [SRO] |
| [Medium-impact] | Random sample (10%) | [Team lead] | [Senior officer] |
| [Low-impact] | Audit trail only | [Automated monitoring] | [Team lead] |

**For High-Risk AI** (affecting health, safety, fundamental rights):
- [ ] MUST have human-in-the-loop (review every decision)
- [ ] Humans trained on AI limitations and biases
- [ ] Override process tested and documented
- [ ] Decision rationale explainable to affected persons

**Findings**:
[Describe how the AI system respects human-centred values]

**Gaps**:
[List areas lacking sufficient respect for human rights, diversity, or autonomy]

**Score**: ___/10

---

### Principle 3: Fairness

**Principle**: AI systems should be inclusive and accessible, and should not involve or result in unfair discrimination against individuals, communities or groups. Throughout their lifecycle, AI systems should be inclusive and accessible, and should not involve or result in unfair discrimination against individuals, communities or groups.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Bias assessment completed
- [ ] Training data reviewed for bias
- [ ] Fairness metrics calculated across protected attributes
- [ ] Protected characteristics analysis (age, sex, race, disability, etc.)
- [ ] Bias mitigation techniques applied
- [ ] Ongoing monitoring for bias drift
- [ ] Disability Discrimination Act 1992 compliance verified
- [ ] Anti-discrimination obligations considered (Age Discrimination Act 2004, Racial Discrimination Act 1975, Sex Discrimination Act 1984)
- [ ] Accessibility standards met (WCAG 2.1 AA minimum)
- [ ] Inclusive design principles applied

**Fairness Testing**:
| Protected Characteristic | Metric | Baseline | Threshold | Current | Status |
|-------------------------|--------|----------|-----------|---------|--------|
| Gender | Demographic parity | +/-5% | +/-10% | [%] | PASS / WARN / FAIL |
| Ethnicity | Equal opportunity | +/-5% | +/-10% | [%] | PASS / WARN / FAIL |
| Age | Equalized odds | +/-5% | +/-10% | [%] | PASS / WARN / FAIL |
| Disability | Calibration | +/-5% | +/-10% | [%] | PASS / WARN / FAIL |
| Indigenous status | Demographic parity | +/-5% | +/-10% | [%] | PASS / WARN / FAIL |

**Bias Mitigation**:
- [ ] Diverse training data sourced
- [ ] Data augmentation for underrepresented groups
- [ ] Algorithmic fairness techniques applied
- [ ] Regular fairness audits scheduled
- [ ] First Nations and culturally diverse communities consulted

**Findings**:
[Describe fairness assessment outcomes]

**Gaps**:
[List fairness or discrimination risks]

**Score**: ___/10

---

### Principle 4: Privacy Protection and Security

**Principle**: AI systems should respect and uphold privacy rights and data protection, and ensure the security of data. Throughout their lifecycle, AI systems should respect and uphold privacy rights and data protection, and ensure the security of data.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence - Privacy**:
- [ ] Privacy Impact Assessment (PIA) completed
- [ ] Privacy Act 1988 compliance verified
- [ ] Australian Privacy Principles (APPs) compliance verified
- [ ] Data Protection Impact Assessment (DPIA) completed
- [ ] OAIC guidance followed
- [ ] Privacy notice includes AI use
- [ ] Data minimisation principle applied
- [ ] Data retention period defined
- [ ] Right of access and correction enabled
- [ ] Cross-border data transfer assessed (APP 8)

**Evidence - Security**:
- [ ] Cyber security assessment completed
- [ ] ACSC Essential Eight controls implemented
- [ ] Information Security Manual (ISM) guidance followed
- [ ] AI-specific threats assessed (prompt injection, data poisoning, model theft)
- [ ] Penetration testing completed
- [ ] Red teaming conducted (for high-risk AI)
- [ ] Incident response plan includes AI-specific scenarios
- [ ] Supply chain security verified (third-party AI services)
- [ ] IRAP assessment completed (if applicable)
- [ ] Protective Security Policy Framework (PSPF) compliance verified

**AI-Specific Security Threats**:
| Threat | Risk Level | Mitigation |
|--------|------------|------------|
| Prompt Injection | [H/M/L] | [Input sanitization, content filtering] |
| Data Poisoning | [H/M/L] | [Data validation, anomaly detection] |
| Model Theft | [H/M/L] | [Access controls, API rate limiting] |
| Adversarial Attacks | [H/M/L] | [Robustness testing, input validation] |
| Model Inversion | [H/M/L] | [Differential privacy, access controls] |

**Privacy and Data Protection**:
| Check | Status | Issues Found | Resolution |
|-------|--------|--------------|------------|
| PIA | DONE / IN PROGRESS / NOT STARTED | [Issues] | [Actions] |
| DPIA | DONE / IN PROGRESS / NOT STARTED | [Issues] | [Actions] |
| APP compliance | DONE / IN PROGRESS / NOT STARTED | [Issues] | [Actions] |
| ISM compliance | DONE / IN PROGRESS / NOT STARTED | [Issues] | [Actions] |
| IRAP assessment | DONE / IN PROGRESS / NOT STARTED / N/A | [Issues] | [Actions] |

**Data Protection**:
- Legal basis for collection/use: [APP 3 / APP 6 / Consent / Statutory authority / etc.]
- Sensitive information: [ ] Yes / [ ] No (if yes, justify under APP 3.3/3.4)
- Data retention period: [X months/years]
- Cross-border disclosure: [ ] Yes (APP 8 compliance required) / [ ] No

**Security Controls**:
- [ ] Input validation and sanitization
- [ ] Output content filtering (for generative AI)
- [ ] Rate limiting on API endpoints
- [ ] Access controls (RBAC/ABAC)
- [ ] Audit logging of all AI interactions
- [ ] Encryption at rest and in transit
- [ ] Secure model storage and versioning
- [ ] Regular security updates and patching

**Findings**:
[Describe privacy and security implementation]

**Gaps**:
[List privacy or security vulnerabilities]

**Score**: ___/10

---

### Principle 5: Reliability and Safety

**Principle**: AI systems should reliably operate in accordance with their intended purpose. Throughout their lifecycle, AI systems should reliably operate in accordance with their intended purpose.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Safety testing completed (no harmful outputs)
- [ ] Robustness testing (handles edge cases)
- [ ] Fail-safe mechanisms in place
- [ ] System operates within defined parameters
- [ ] Performance benchmarks established and met
- [ ] Model drift detection implemented
- [ ] Incident response plan tested
- [ ] Lifecycle management plan documented
- [ ] Retraining schedule defined
- [ ] Decommissioning plan in place

**Safety Measures**:
| Risk | Safeguard | Testing | Status |
|------|-----------|---------|--------|
| [Harmful content generation] | [Content filtering] | [Red team testing] | PASS / WARN / FAIL |
| [Biased outcomes] | [Fairness testing] | [Demographic analysis] | PASS / WARN / FAIL |
| [System failures] | [Graceful degradation] | [Chaos engineering] | PASS / WARN / FAIL |

**Lifecycle Stages**:

**1. Selection and Procurement**:
- [ ] Requirements defined (see ARC-{PROJECT_ID}-REQ-v*.md)
- [ ] Build vs buy decision documented
- [ ] Supplier evaluation completed (see ARC-*-EVAL-*.md)
- [ ] Contract includes AI-specific terms (performance, bias, retraining)

**2. Development and Testing**:
- [ ] Training data provenance documented
- [ ] Bias testing completed
- [ ] Performance benchmarks established
- [ ] User acceptance testing (UAT) with real users
- [ ] Accessibility testing completed

**3. Deployment**:
- [ ] Phased rollout plan (pilot, beta, full deployment)
- [ ] Monitoring dashboards configured
- [ ] Alert thresholds defined
- [ ] Incident response procedures ready

**4. Operation and Maintenance**:
- [ ] Ongoing performance monitoring
- [ ] Model drift detection (monthly checks)
- [ ] Retraining schedule (e.g., quarterly with new data)
- [ ] User feedback collection mechanism
- [ ] Regular fairness and bias audits

**5. Decommissioning**:
- [ ] Data deletion procedure defined
- [ ] Model archive or deletion
- [ ] User notification plan
- [ ] Alternative process for affected users
- [ ] Lessons learned documentation

**Model Monitoring Metrics**:
| Metric | Baseline | Threshold | Current | Action if Exceeded |
|--------|----------|-----------|---------|-------------------|
| Accuracy | [%] | [%] | [%] | [Retrain model] |
| False Positive Rate | [%] | [%] | [%] | [Tune threshold] |
| Fairness (demographic parity) | [+/-%] | [+/-%] | [+/-%] | [Bias mitigation] |
| Latency | [ms] | [ms] | [ms] | [Scale infrastructure] |

**Findings**:
[Describe reliability and safety implementation]

**Gaps**:
[List reliability or safety concerns]

**Score**: ___/10

---

### Principle 6: Transparency and Explainability

**Principle**: There should be transparency and responsible disclosure so people can understand when they are being significantly impacted by AI, and can find out when an AI system is engaging with them. Throughout their lifecycle, AI systems should be transparent and explainable.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] System documented publicly (where appropriate)
- [ ] Decision explanations available to affected persons
- [ ] Model card or factsheet published
- [ ] Privacy notice includes AI use
- [ ] Citizens informed AI is being used
- [ ] How to request human review explained
- [ ] AI limitations documented (hallucinations, biases, edge cases)
- [ ] Team understands AI capabilities and constraints
- [ ] Realistic expectations set with stakeholders
- [ ] Technical constraints understood (data quality, compute, latency)
- [ ] Complaint mechanism published

**AI Limitations Documented**:
| Limitation | Impact | Mitigation |
|------------|--------|------------|
| [e.g., Hallucinations in LLM] | [May generate false information] | [Human review of all outputs] |
| [e.g., Bias in training data] | [May discriminate against groups] | [Fairness testing, bias mitigation] |

**Explainability Level**:
- [ ] **Full explainability**: Can explain why each decision was made
- [ ] **Partial explainability**: Can explain general logic, not individual decisions
- [ ] **Black box**: Cannot explain decisions (must justify if high-risk)

**Public Communication**:
- [ ] Citizens informed AI is being used
- [ ] How to request human review explained
- [ ] Complaint mechanism published
- [ ] Plain language explanations provided (no unnecessary jargon)

**Findings**:
[Describe transparency and explainability implementation]

**Gaps**:
[List areas where transparency or explainability is insufficient]

**Score**: ___/10

---

### Principle 7: Contestability

**Principle**: When an AI system significantly impacts a person, community, group or environment, there should be a timely process to allow people to challenge the use or outcomes of the AI system. Throughout their lifecycle, people should be able to challenge the use or output of an AI system.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Right to contest AI decisions enabled
- [ ] Human review process for contested decisions
- [ ] Appeal mechanism documented and accessible
- [ ] Redress process for those harmed
- [ ] Response times defined (e.g., 28 days)
- [ ] Process accessible to all affected persons (including those with disability, limited English, low digital literacy)
- [ ] Multiple channels available for lodging challenges

**Contestability Process**:
1. **How users can contest**: [Email form, online portal, phone, in-person]
2. **Information required**: [What users must provide]
3. **Review timeline**: [X working days]
4. **Human reviewer**: [Role/team]
5. **Appeal if unsatisfied**: [Next level escalation]
6. **Redress options**: [Correction, compensation, apology]

**Testing**:
- [ ] Contestability process tested with real users
- [ ] Response times meet targets
- [ ] Users satisfied with process
- [ ] Process accessible to people with diverse needs

**Findings**:
[Describe contestability mechanisms]

**Gaps**:
[List areas where contestability is insufficient]

**Score**: ___/10

---

### Principle 8: Accountability

**Principle**: People responsible for the different phases of the AI system lifecycle should be identifiable and accountable for the outcomes of the AI systems, and human oversight of AI systems should be enabled. Throughout their lifecycle, those responsible for AI systems should be identifiable and accountable.

**Compliance Status**: [ ] COMPLIANT / [ ] PARTIAL / [ ] NON-COMPLIANT

**Evidence**:
- [ ] Clear ownership assigned (SRO, Product Owner)
- [ ] Decision-making process documented
- [ ] Audit trail of all AI decisions maintained
- [ ] Incident response procedures in place
- [ ] Accountability for errors defined
- [ ] AI governance board approval obtained
- [ ] AI strategy alignment documented
- [ ] Organisational AI principles followed
- [ ] Risk management process followed
- [ ] Regular governance reviews scheduled

**Accountability Structure**:
- **Senior Responsible Owner**: [Name] - Strategic oversight
- **Product Owner**: [Name] - Day-to-day operation
- **Technical Lead**: [Name] - Technical implementation
- **Ethics Lead**: [Name] - Ethical oversight
- **AI Governance Board**: [Name of board]

**Governance Checkpoints**:
| Phase | Review Required | Status | Date | Outcome |
|-------|-----------------|--------|------|---------|
| Concept | AI Governance Board | DONE / IN PROGRESS / PENDING | [Date] | [Approved/Conditions] |
| Design | Technical Review | DONE / IN PROGRESS / PENDING | [Date] | [Approved/Conditions] |
| Pre-Deployment | Security & Ethics Review | DONE / IN PROGRESS / PENDING | [Date] | [Approved/Conditions] |
| Post-Deployment | Performance Review | DONE / IN PROGRESS / PENDING | [Date] | [Approved/Conditions] |

**Incident Response**:
- [ ] Process for reporting AI errors
- [ ] Root cause analysis procedure
- [ ] Corrective action tracking
- [ ] Learning and improvement loop

**Organisational Alignment**:
- [ ] Aligns with department's AI principles
- [ ] Aligns with Australian Government AI Ethics Framework
- [ ] No conflicts with organisational values
- [ ] Escalation process defined and followed

**Findings**:
[Describe accountability and governance implementation]

**Gaps**:
[List governance, accountability or alignment issues]

**Score**: ___/10

---

## Supporting Assessments

### Skills and Expertise

**Evidence**:
- [ ] AI/ML technical expertise on team
- [ ] Data science capability
- [ ] Ethical AI expertise or access
- [ ] Domain expertise (understanding of problem domain)
- [ ] User research capability
- [ ] Legal/compliance expertise
- [ ] Cyber security expertise
- [ ] Training provided to all team members

**Team Composition**:
| Role | Filled? | Name/Team | Expertise Level |
|------|---------|-----------|-----------------|
| AI/ML Specialist | Yes / No | [Name] | [Junior/Mid/Senior] |
| Data Scientist | Yes / No | [Name] | [Junior/Mid/Senior] |
| Ethics Advisor | Yes / No | [Name] | [Junior/Mid/Senior] |
| Domain Expert | Yes / No | [Name] | [Junior/Mid/Senior] |
| User Researcher | Yes / No | [Name] | [Junior/Mid/Senior] |
| Legal/Compliance | Yes / No | [Name] | [Junior/Mid/Senior] |
| Security Specialist | Yes / No | [Name] | [Junior/Mid/Senior] |
| Product Manager | Yes / No | [Name] | [Junior/Mid/Senior] |

**Training Provided**:
- [ ] AI fundamentals for all team members
- [ ] Ethical AI considerations (Australian AI Ethics Framework)
- [ ] Bias recognition and mitigation
- [ ] AI system limitations
- [ ] User research with AI systems
- [ ] Incident response for AI failures

---

### Collaboration

**Evidence**:
- [ ] Cross-government collaboration (DTA, CSIRO's Data61, Department of Industry, Science and Resources)
- [ ] Academia partnerships
- [ ] Industry engagement
- [ ] Civil society consultation
- [ ] User community involvement
- [ ] Sharing lessons learned
- [ ] Contributing to government AI community

**Collaboration Activities**:
| Stakeholder | Engagement Type | Purpose | Outcome |
|-------------|-----------------|---------|---------|
| [DTA] | [Workshop] | [Best practices] | [Adopted design patterns] |
| [CSIRO's Data61] | [Research partnership] | [Bias mitigation] | [Improved fairness metrics] |
| [Civil society org] | [Consultation] | [Rights impact] | [Enhanced safeguards] |
| [Other dept] | [Knowledge sharing] | [Similar use case] | [Reused components] |

---

### Commercial Partnership

**Evidence**:
- [ ] Procurement team engaged early
- [ ] AI requirements in contract (performance, explainability, bias)
- [ ] Supplier responsible AI commitments documented
- [ ] Audit rights included in contract
- [ ] Data rights and ownership clear
- [ ] Exit strategy defined (data portability, model ownership)
- [ ] Performance metrics and SLAs
- [ ] Liability and indemnity clauses for AI failures

**Contract Requirements for AI**:
- [ ] **Performance metrics**: Accuracy, latency, uptime SLAs
- [ ] **Explainability**: Supplier must explain how AI works
- [ ] **Bias audits**: Regular fairness testing required
- [ ] **Retraining**: Frequency and process for model updates
- [ ] **Data rights**: Government owns training data and outputs
- [ ] **Audit rights**: Government can audit AI system
- [ ] **Security**: Cyber security standards compliance (ISM, Essential Eight)
- [ ] **Liability**: Clear accountability for AI failures
- [ ] **Exit**: Data portability, model handover, decommissioning

**Supplier Responsible AI Commitments**:
| Commitment | Contractual? | Verification Method |
|------------|--------------|---------------------|
| [Bias testing quarterly] | Yes | [Audit reports] |
| [Explainability documentation] | Yes | [Technical docs] |
| [Data security standards] | Yes | [Essential Eight Maturity Level 3 cert] |
| [Human oversight capability] | Yes | [Override mechanism tested] |

---

### Right Tool Selection

**Evidence**:
- [ ] Problem clearly defined
- [ ] Alternative solutions considered (non-AI, simpler AI)
- [ ] Cost-benefit analysis completed
- [ ] AI adds genuine value over alternatives
- [ ] Use case appropriate for AI (not using AI for sake of it)
- [ ] Success metrics defined
- [ ] Pilot/proof-of-concept completed

**Alternatives Considered**:
| Solution | Pros | Cons | Why Not Chosen |
|----------|------|------|----------------|
| Manual process | [Accurate] | [Slow, expensive] | [Cannot scale to demand] |
| Rule-based system | [Explainable] | [Inflexible] | [Too many edge cases] |
| Simple ML (not AI) | [Faster] | [Less accurate] | [Accuracy critical for use case] |
| AI (selected) | [Accurate, scalable] | [Less explainable, bias risk] | [Best fit with mitigation] |

**Success Metrics**:
| Metric | Baseline | Target | Current | Status |
|--------|----------|--------|---------|--------|
| [Accuracy] | [%] | [%] | [%] | PASS / WARN / FAIL |
| [Processing time] | [X hours] | [X minutes] | [X minutes] | PASS / WARN / FAIL |
| [Cost per transaction] | [$AUD X] | [$AUD Y] | [$AUD Z] | PASS / WARN / FAIL |
| [User satisfaction] | [X/10] | [Y/10] | [Z/10] | PASS / WARN / FAIL |

---

## Overall Assessment Summary

### Compliance Scorecard

| Principle | Score /10 | Status |
|-----------|-----------|--------|
| **8 Australian AI Ethics Principles** | | |
| 1. Human, Societal and Environmental Wellbeing | __ | PASS / WARN / FAIL |
| 2. Human-Centred Values | __ | PASS / WARN / FAIL |
| 3. Fairness | __ | PASS / WARN / FAIL |
| 4. Privacy Protection and Security | __ | PASS / WARN / FAIL |
| 5. Reliability and Safety | __ | PASS / WARN / FAIL |
| 6. Transparency and Explainability | __ | PASS / WARN / FAIL |
| 7. Contestability | __ | PASS / WARN / FAIL |
| 8. Accountability | __ | PASS / WARN / FAIL |
| **TOTAL SCORE** | **__/80** | |

**Percentage Score**: ___%

### Compliance Levels

- **90-100%** (72-80 points): Excellent - Exemplary responsible AI
- **75-89%** (60-71 points): Good - Compliant with minor improvements needed
- **60-74%** (48-59 points): Adequate - Significant gaps to address
- **< 60%** (< 48 points): Poor - Major compliance issues

### Risk-Based Decision

**For HIGH-RISK AI** (fully automated decisions affecting rights/safety/health):
- [ ] MUST score >= 90% to proceed
- [ ] ALL 8 principles must be met (no FAIL allowed)
- [ ] Human-in-the-loop REQUIRED
- [ ] Regular audits (quarterly minimum)

**For MEDIUM-RISK AI**:
- [ ] SHOULD score >= 75% to proceed
- [ ] Critical principles must be met (2, 3, 4, 5)
- [ ] Human oversight required
- [ ] Annual audits

**For LOW-RISK AI**:
- [ ] SHOULD score >= 60% to proceed
- [ ] Basic safeguards in place
- [ ] Periodic review (annual)

### Critical Issues (Blocking)

1. [Issue description]
2. [Issue description]
3. [Issue description]

### Recommendations

#### High Priority (Address before deployment)

1. [Recommendation]
2. [Recommendation]

#### Medium Priority (Address within 3 months)

1. [Recommendation]
2. [Recommendation]

#### Low Priority (Continuous improvement)

1. [Recommendation]
2. [Recommendation]

---

## Action Plan

| Action | Principle | Owner | Due Date | Status |
|--------|-----------|-------|----------|--------|
| [Action item] | [Principle #] | [Name] | [Date] | IN PROGRESS / PENDING / DONE |

---

## Mandatory Documentation

### Required Assessments (attach or link)

- [ ] **PIA** (Privacy Impact Assessment): [Link]
- [ ] **DPIA** (Data Protection Impact Assessment): [Link]
- [ ] **Human Rights Assessment**: [Link]
- [ ] **Disability Discrimination Act 1992 Assessment**: [Link]
- [ ] **Security Risk Assessment**: [Link]
- [ ] **Bias Audit Report**: [Link]
- [ ] **User Research Report**: [Link]
- [ ] **IRAP Assessment** (if applicable): [Link]

### Governance Approvals

- [ ] AI Governance Board approval: [Date]
- [ ] Senior Responsible Owner sign-off: [Date]
- [ ] Legal review: [Date]
- [ ] Security review: [Date]
- [ ] Ethics review: [Date]

---

## Go/No-Go Decision

**Decision**: [ ] APPROVED / [ ] APPROVED WITH CONDITIONS / [ ] REJECTED

**Conditions for Approval** (if applicable):
1. [Condition 1]
2. [Condition 2]
3. [Condition 3]

**Deployment Approval**: [ ] Yes / [ ] No

**Ongoing Monitoring Required**:
- [ ] Weekly performance reviews (first month)
- [ ] Monthly bias audits
- [ ] Quarterly governance reviews
- [ ] Annual comprehensive reassessment

---

## Sign-Off

**Assessed By**: [Name, Role]
**Date**: [Date]

**Senior Responsible Owner**:
Name: ________________
Date: ________________
Signature: ________________

**AI Governance Board Chair**:
Name: ________________
Date: ________________
Signature: ________________

---

## Review Schedule

**Next Review**: [Date]
**Review Frequency**:
- [ ] Monthly (high-risk)
- [ ] Quarterly (medium-risk)
- [ ] Annually (low-risk)

---

**Template Version**: 2.0
**Last Updated**: 2026-02-13
**Source**: https://www.industry.gov.au/publications/australias-artificial-intelligence-ethics-framework

## External References

| Document | Type | Source | Key Extractions | Path |
|----------|------|--------|-----------------|------|
| Australia's AI Ethics Framework | Framework | Department of Industry, Science and Resources | 8 AI Ethics Principles | https://www.industry.gov.au/publications/australias-artificial-intelligence-ethics-framework |
| Privacy Act 1988 | Legislation | OAIC | Australian Privacy Principles (APPs) | https://www.oaic.gov.au/privacy/the-privacy-act |
| Information Security Manual (ISM) | Guidance | ACSC | Cybersecurity controls | https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism |
| *Project-specific documents* | -- | -- | -- | -- |

---

**Generated by**: ArcKit `/arckit.ai-playbook` command
**Generated on**: [DATE]
**ArcKit Version**: [VERSION]
**Project**: [PROJECT_NAME]
**Model**: [AI_MODEL]
