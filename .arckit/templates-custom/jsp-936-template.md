# Australian Defence AI Assurance Assessment

> **Template Status**: Experimental | **Version**: [VERSION] | **Command**: `/arckit.jsp-936`

## Document Control

| Field | Value |
|-------|-------|
| **Document ID** | ARC-[PROJECT_ID]-DEFAI-v[VERSION] |
| **Document Type** | Australian Defence AI Assurance Assessment |
| **Project** | [PROJECT_NAME] (Project [PROJECT_ID]) |
| **Classification** | [UNOFFICIAL / OFFICIAL / OFFICIAL: Sensitive / PROTECTED / SECRET / TOP SECRET] |
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

## Revision History

| Version | Date | Author | Changes | Approved By | Approval Date |
|---------|------|--------|---------|-------------|---------------|
| [VERSION] | [DATE] | ArcKit AI | Initial creation from `/arckit.jsp-936` command | PENDING | PENDING |

---

## Executive Summary

**AI System Purpose**: [2-3 sentence description of what the AI system does and why it is needed within the Australian Defence context]

**Overall Risk Classification**: [Critical / Severe / Major / Moderate / Minor]

**Key AI Components**: [Number of AI/ML components identified]

**Ethical Risk Assessment**:
- **Likelihood**: [1-5 - Rare to Almost Certain]
- **Impact**: [1-5 - Insignificant to Catastrophic]
- **Risk Score**: [Likelihood x Impact = X]

**Key Findings**:
- [Summary of critical ethical considerations against Australia's AI Ethics Framework]
- [Summary of AI-specific security risks per ISM controls]
- [Summary of human-AI teaming approach]

**Approval Status**: [Not Started / In Progress / Approved / Conditional Approval]

**Critical Issues**: [Any blocking issues for approval]

---

## 1. AI System Inventory

### 1.1 AI Component Catalogue

#### AI Component 1: [Name]

**Component Details**:
- **Type**: [ML Model / AI Algorithm / Autonomous System / Decision Support / NLP / Computer Vision / Generative AI]
- **Sub-type**: [e.g., Deep Learning CNN / Random Forest / LLM / etc.]
- **Purpose**: [What problem does it solve?]
- **Criticality**: [Critical / High / Medium / Low]

**Input Data**:
- **Data Sources**: [Where does data come from?]
- **Data Types**: [Structured/Unstructured, Image/Text/Sensor, etc.]
- **Data Volume**: [Scale of data processed]
- **Data Classification**: [UNOFFICIAL / OFFICIAL / OFFICIAL: Sensitive / PROTECTED / SECRET / TOP SECRET]

**Output/Decisions**:
- **Output Type**: [Classification / Prediction / Recommendation / Autonomous Action]
- **Decision Authority**: [Informational / Advisory / Semi-Autonomous / Fully Autonomous]
- **Impact of Output**: [What happens based on this output?]

**Human Involvement**:
- **Teaming Model**: [Human-in-loop / Human-on-loop / Human-out-of-loop]
- **Human Control Points**: [Where do humans interact?]
- **Override Capability**: [Yes / No / Partial]

**Training Data**:
- **Dataset Source**: [Where did training data come from?]
- **Dataset Size**: [Number of samples]
- **Dataset Timeframe**: [When was data collected?]
- **Labeling Method**: [Manual / Automated / Semi-automated]
- **Data Quality Assessment**: [High / Medium / Low]

**Model Details**:
- **Algorithm/Architecture**: [Specific model architecture]
- **Model Size**: [Number of parameters / Model complexity]
- **Training Method**: [Supervised / Unsupervised / Reinforcement Learning]
- **Performance Metrics**: [Accuracy, F1-score, etc.]
- **Technology Readiness Level (TRL)**: [1-9]

**Deployment Context**:
- **Deployment Environment**: [Cloud (ASD-certified) / On-premise / Edge / Operational system]
- **Operational Tempo**: [Real-time / Batch / On-demand]
- **Availability Requirements**: [24/7 / Business hours / Mission-critical]
- **User Base**: [Who uses this system?]

#### AI Component 2: [Name]
[Repeat structure above for each AI component]

### 1.2 AI System Architecture

**High-Level Architecture**:
[Diagram or description of how AI components integrate into overall system]

**Data Flow**:
[Description of data flow through AI components]

**Integration Points**:
- [Integration 1: AI component <-> System component]
- [Integration 2: AI component <-> Human operator]

---

## 2. Ethical Risk Assessment

### 2.1 Risk Matrix for AI Component 1: [Name]

#### Impact Assessment (Scale: 1-5)

**Human Safety and Wellbeing**: [Score 1-5]
- [Assessment rationale]
- Potential harms: [Description]

**Operational Effectiveness**: [Score 1-5]
- [Assessment rationale]
- Mission impact: [Description]

**Legal and Ethical Compliance**: [Score 1-5]
- [Assessment rationale]
- Compliance risks: [Description]

**Public Trust and Reputation**: [Score 1-5]
- [Assessment rationale]
- Reputational impact: [Description]

**International Obligations**: [Score 1-5]
- [Assessment rationale]
- International Humanitarian Law (IHL) considerations: [Description]
- AUKUS obligations: [Description]
- Five Eyes intelligence sharing considerations: [Description]

**Overall Impact Score**: [Highest score from above = X]

#### Likelihood Assessment (Scale: 1-5)

**Technology Maturity (TRL)**: [Score 1-5]
- Current TRL: [1-9]
- Maturity risks: [Description]

**Data Quality and Availability**: [Score 1-5]
- Data quality assessment: [Description]
- Data availability: [Description]

**Algorithm Complexity**: [Score 1-5]
- Complexity level: [High / Medium / Low]
- Complexity risks: [Description]

**Operational Environment**: [Score 1-5]
- Environment variability: [Description]
- Environmental risks: [Description]

**Human Factors and Training**: [Score 1-5]
- Training adequacy: [Description]
- Human error potential: [Description]

**Overall Likelihood Score**: [Highest score from above = Y]

#### Risk Classification

**Risk Score**: [Likelihood (Y) x Impact (X) = Z]

**Classification**: [Based on score Z]
- 20-25: **Critical** -> Secretary / Ministerial approval
- 15-19: **Severe** -> Defence-Level (Defence Committee / CIOG) approval
- 10-14: **Major** -> Defence-Level (Defence Committee / CIOG) approval
- 5-9: **Moderate** -> Group-Level approval (delegated)
- 1-4: **Minor** -> Group-Level approval (delegated)

**Approval Pathway**: [Secretary/Ministerial / Defence-Level / Group-Level]

#### Unacceptable Risk Check

**Unacceptable Risk Criteria**:
- [ ] Significant negative impacts are imminent
- [ ] Severe harms are occurring
- [ ] Catastrophic risks present
- [ ] System behaving outside acceptable bounds
- [ ] International Humanitarian Law (IHL) violations possible

**Status**: [ACCEPTABLE / STOP - UNACCEPTABLE RISK]

**Justification**: [If unacceptable, explain why work cannot proceed]

### 2.2 Risk Matrix for AI Component 2: [Name]
[Repeat structure above for each AI component]

### 2.3 Overall Project Risk Classification

**Highest Individual Risk Score**: [Maximum score from all AI components]
**Overall Project Classification**: [Critical / Severe / Major / Moderate / Minor]
**Required Approval Authority**: [Secretary/Ministerial / Defence-Level / Group-Level]

---

## 3. Eight AI Ethics Principles Compliance

> Based on Australia's AI Ethics Framework (Department of Industry, Science and Resources) applied within the Australian Defence context.

### 3.1 Principle 1: Human, Societal and Environmental Wellbeing

**Principle**: AI systems should benefit individuals, society and the environment. Throughout their lifecycle, AI systems should be used in ways that are beneficial, including generating positive outcomes for individuals, communities, groups, society, the planet, and the environment.

#### For AI Component 1: [Name]

**Impact on People and Environment**:
- **Affected Stakeholders**: [Who is impacted by this AI?]
- **Positive Impacts**: [Benefits to humans, society, and environment]
- **Negative Impacts**: [Potential harms to humans, society, and environment]
- **Environmental Considerations**: [Energy consumption, carbon footprint, ecological impact]

**Societal Impact**:
- **Community Impact**: [How the AI system affects wider Australian communities]
- **Defence Personnel Impact**: [Impact on ADF members and Defence civilians]
- **National Security Benefit**: [How the system contributes to national security]

**Stakeholder Engagement**:
- **Stakeholders Consulted**: [List of stakeholder groups]
- **Consultation Method**: [Workshops / Surveys / Interviews]
- **Feedback Incorporated**: [How stakeholder input shaped design]
- **Ongoing Engagement Plan**: [How to maintain stakeholder involvement]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Documentation references, design documents, impact assessments]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.2 Principle 2: Human-Centred Values

**Principle**: AI systems should respect human rights, diversity, and the autonomy of individuals. Throughout their lifecycle, AI systems should respect human rights, including freedom, dignity, and privacy.

#### For AI Component 1: [Name]

**Human Rights Assessment**:
- **Rights Considered**: [Privacy, dignity, freedom, non-discrimination]
- **Rights Impact**: [How the AI system affects human rights]
- **Human Autonomy**: [How the AI system respects individual autonomy]
- **Diversity Considerations**: [How the system accounts for diversity in the Australian context]

**Human-AI Interaction**:
- **Interaction Model**: [Human-in-loop / Human-on-loop / Human-out-of-loop]
- **Control Mechanisms**: [How humans maintain control]
- **Override Capability**: [Yes / No / Partial - describe]
- **Transparency to Users**: [What users see/understand about AI decisions]

**Meaningful Human Control**:
- **Control Level**: [Full / Substantial / Limited / None]
- **Decision Authority**: [Human decides / Human approves / Human monitors / Fully autonomous]
- **Time to Intervene**: [Time available for human to intervene if needed]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Documentation references, design documents, user research]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.3 Principle 3: Fairness

**Principle**: AI systems should be inclusive and accessible, and should not involve or result in unfair discrimination against individuals, communities or groups.

#### For AI Component 1: [Name]

**Fairness Assessment**:
- **Bias Testing Conducted**: [Yes / No / In Progress]
- **Bias Testing Method**: [Fairness metrics, demographic parity, equal opportunity, etc.]
- **Protected Characteristics Tested**: [Age, gender, race, ethnicity, disability, etc.]
- **Bias Identified**: [Description of any bias found]
- **Bias Severity**: [High / Medium / Low / None detected]

**Inclusion and Accessibility**:
- **Accessibility Standards**: [WCAG 2.1 compliance, assistive technology support]
- **Inclusion Assessment**: [How the system serves diverse populations]
- **Cultural Sensitivity**: [Consideration of Aboriginal and Torres Strait Islander peoples and culturally diverse communities]
- **Language Considerations**: [Support for diverse linguistic backgrounds]

**Bias Sources**:
- **Data Bias**: [Historical bias in training data?]
- **Algorithmic Bias**: [Algorithm inherently biased?]
- **Deployment Bias**: [Different performance in deployment vs. training?]
- **Feedback Loop Bias**: [System decisions creating biased future data?]

**Mitigation Strategies**:
- **Data Mitigation**: [Diverse training data, bias detection in data, rebalancing]
- **Algorithmic Mitigation**: [Fairness constraints, debiasing techniques, adversarial debiasing]
- **Operational Mitigation**: [Human oversight, decision review, performance monitoring by demographic]
- **Ongoing Monitoring**: [Continuous bias monitoring in production]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Bias test reports, fairness metrics, mitigation documentation]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.4 Principle 4: Privacy Protection and Security

**Principle**: AI systems should respect and uphold privacy rights and data protection, and ensure the security of data. Throughout their lifecycle, AI systems should ensure privacy is protected and data is secure.

#### For AI Component 1: [Name]

**Privacy Assessment**:
- **Australian Privacy Principles (APPs) Compliance**: [Assessment against all 13 APPs]
- **Privacy Impact Assessment (PIA)**: [Completed / In Progress / Not Started]
- **Personal Information Collected**: [Types of personal information]
- **Purpose Limitation**: [Data used only for stated purposes?]
- **Data Minimisation**: [Minimum data collected?]
- **Consent Mechanisms**: [How consent is obtained]

**Data Protection**:
- **Data Classification**: [Per PSPF classification]
- **Encryption at Rest**: [AES-256 / Other - per ISM controls]
- **Encryption in Transit**: [TLS 1.2+ / Other - per ISM controls]
- **Access Controls**: [Role-based / Attribute-based]
- **Data Retention**: [Retention period and disposal method]

**Security Controls (per ISM)**:
- **ISM Controls Applied**: [List relevant ISM control identifiers]
- **ASD Essential Eight Maturity Level**: [Level 0 / 1 / 2 / 3]
- **IRAP Assessment Status**: [Completed / In Progress / Not Required]
- **ASD Certification Status**: [Certified / Pending / Not Required]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [PIA, ISM compliance matrix, IRAP assessment, ASD certification]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.5 Principle 5: Reliability and Safety

**Principle**: AI systems should reliably operate in accordance with their intended purpose. Throughout their lifecycle, AI systems should operate reliably and their safety should be assured.

#### For AI Component 1: [Name]

**Performance Boundaries**:
- **Performance Metrics**: [Accuracy, precision, recall, F1, etc.]
- **Minimum Acceptable Performance**: [Threshold for each metric]
- **Current Performance**: [Measured performance]
- **Performance Variability**: [How much does performance vary?]
- **Out-of-Distribution Detection**: [How system handles novel inputs]

**Robustness**:
- **Adversarial Robustness**: [Tested against adversarial examples? Results?]
- **Environmental Robustness**: [Performance across different conditions]
- **Degradation Handling**: [How system handles degraded inputs]
- **Edge Case Handling**: [How system handles unusual inputs]

**Australian Defence Safety Compliance**:
- **Defence Safety Management System**: [Compliance status]
- **HAZOP Analysis**: [Hazard and Operability Study completed?]
- **Safety Case**: [Safety case documented?]
- **Failure Mode Effects Analysis (FMEA)**: [Completed?]
- **Safe Operating Envelope**: [Defined and documented?]

**Reliability Evidence**:
- **Test Coverage**: [% of operational scenarios tested]
- **Verification and Validation**: [V&V report completed?]
- **Operational Testing**: [Real-world performance data]
- **Failure Rate**: [Mean time between failures]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Test reports, V&V documentation, safety case, FMEA]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.6 Principle 6: Transparency and Explainability

**Principle**: There should be transparency and responsible disclosure so people can understand when they are being significantly impacted by AI, and can find out when an AI system is engaging with them.

#### For AI Component 1: [Name]

**Explainability**:
- **Explainability Method**: [LIME / SHAP / Attention maps / Rule extraction / Other]
- **Explanation Target Audience**: [Operators / Commanders / Oversight / Public]
- **Explanation Content**: [What is explained - feature importance, decision rationale, etc.]
- **Explanation Accuracy**: [How faithful are explanations to actual model behaviour?]

**Transparency**:
- **AI Disclosure**: [How users are informed they are interacting with AI]
- **Decision Transparency**: [How AI decisions are communicated]
- **Limitation Disclosure**: [How limitations are communicated to users]
- **Source Code / Model Access**: [Level of access provided for audit purposes]

**Documentation**:
- **Model Card**: [Yes / No - document model details]
- **Technical Documentation**: [Architecture, training, performance]
- **Operational Documentation**: [User guides, SOPs]
- **Ethics Documentation**: [This Australian Defence AI Assurance Assessment]

**Training Programme**:
- **Operator Training**: [Duration, content, competency assessment]
- **Commander Training**: [Understanding AI capabilities and limitations]
- **Technical Training**: [For maintainers and developers]
- **Training Completion**: [% of required personnel trained]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Model card, training materials, documentation library]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.7 Principle 7: Contestability

**Principle**: When an AI system significantly impacts a person, community, group or environment, there should be a timely process to allow people to challenge the use or outcomes of the AI system.

#### For AI Component 1: [Name]

**Challenge Mechanisms**:
- **Appeal Process**: [How affected parties can challenge AI decisions]
- **Review Process**: [Who reviews challenged decisions]
- **Timelines**: [Response time for challenges]
- **Escalation Path**: [How unresolved challenges are escalated]

**Redress**:
- **Remediation Process**: [How incorrect decisions are corrected]
- **Compensation**: [Process for addressing harm caused by incorrect decisions]
- **Record Keeping**: [How challenges and outcomes are documented]

**Accessibility of Challenge**:
- **Awareness**: [How affected parties are informed of their right to challenge]
- **Ease of Access**: [How easy is it to initiate a challenge?]
- **Support Provided**: [Assistance available for those challenging decisions]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [Challenge process documentation, complaint records, remediation logs]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

### 3.8 Principle 8: Accountability

**Principle**: People responsible for the different phases of the AI system lifecycle should be identifiable and accountable for the outcomes of the AI systems, and human oversight of AI systems should be enabled.

#### For AI Component 1: [Name]

**Accountability Mapping**:
- **System Owner**: [Name/Role] - Overall accountability
- **Responsible AI Officer**: [Name/Role] - AI governance
- **Ethics Adviser**: [Name/Role] - Ethical oversight
- **Technical Lead**: [Name/Role] - Technical implementation
- **Operational Commander**: [Name/Role] - Operational use
- **Data Owner**: [Name/Role] - Training data governance
- **Security Officer**: [Name/Role] - Security compliance (ISM)

**Accountability Framework**:
- **Governance Structure**: [How accountability is structured within Defence]
- **Reporting Lines**: [Chain of accountability]
- **Decision Logging**: [Yes / No - what is logged?]
- **Audit Trail**: [Yes / No - can decisions be traced?]

**Human Oversight**:
- **Oversight Mechanisms**: [How humans oversee AI system operation]
- **Monitoring Frequency**: [Continuous / Periodic / Event-driven]
- **Intervention Authority**: [Who can intervene and under what circumstances]

**Compliance Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**: [RACI matrix, governance documents, decision logs, audit trails]

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

#### For AI Component 2: [Name]
[Repeat structure for each AI component]

---

## 4. AI Lifecycle Phase Documentation

### Phase 1: Planning

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] AI Use Case Justification
- [ ] Alternative approaches considered (AI vs. non-AI)
- [ ] Initial ethical risk screening against AI Ethics Framework
- [ ] Stakeholder identification
- [ ] Resource requirements
- [ ] Success criteria
- [ ] AUKUS and Five Eyes implications assessment (if applicable)

**Documentation Location**: [File path or reference]

**Key Decisions**:
- [Decision 1: Why AI is appropriate for this problem]
- [Decision 2: Initial risk classification]
- [Decision 3: International sharing and collaboration considerations]

**Assurance Activities**:
- [ ] Ethics Adviser review
- [ ] Responsible AI Officer consultation
- [ ] Stakeholder engagement plan
- [ ] Defence Science and Technology Group (DSTG) consultation (if applicable)

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 2: Requirements

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] Functional Requirements (FR)
- [ ] Non-Functional Requirements (NFR)
- [ ] Ethical Requirements (ETH) - aligned to 8 AI Ethics Principles
- [ ] Safety Requirements (SAF)
- [ ] Security Requirements (SEC) - aligned to ISM
- [ ] HAZOP analysis (Hazard and Operability Study)
- [ ] Requirements traceability matrix
- [ ] IHL compliance requirements (if applicable for autonomous systems)

**Documentation Location**: [File path or reference]

**Key Requirements**:
- [FR-01: Functional requirement example]
- [NFR-01: Performance requirement example]
- [ETH-01: Ethical requirement example]
- [SAF-01: Safety requirement example]
- [SEC-01: Security requirement example (per ISM)]

**Assurance Activities**:
- [ ] Requirements review with stakeholders
- [ ] HAZOP workshop conducted
- [ ] Ethics requirements validated against 8 Principles
- [ ] Requirements completeness check

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 3: Architecture

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] System architecture design
- [ ] AI component integration design
- [ ] Data architecture and flow
- [ ] Human-AI interaction design
- [ ] Requirements traceability to architecture
- [ ] Failure mode analysis
- [ ] Security architecture (per ISM)
- [ ] Hosting certification (per Hosting Certification Framework)

**Documentation Location**: [File path or reference]

**Key Architectural Decisions**:
- [Decision 1: Model architecture selection and rationale]
- [Decision 2: Human-in-loop placement]
- [Decision 3: Data pipeline design]
- [Decision 4: Cloud hosting decision (ASD-certified provider)]

**Assurance Activities**:
- [ ] Architecture review
- [ ] Failure mode effects analysis (FMEA)
- [ ] Security architecture review (per ISM)
- [ ] Human factors review

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 4: Algorithm Design

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] Algorithm selection justification
- [ ] Alternative algorithms considered
- [ ] Algorithm limitations documented
- [ ] Bias mitigation strategy
- [ ] Explainability approach
- [ ] Verification methods defined

**Documentation Location**: [File path or reference]

**Algorithm Details**:
- **Selected Algorithm**: [e.g., Convolutional Neural Network]
- **Selection Rationale**: [Why this algorithm?]
- **Alternatives Considered**: [Other algorithms evaluated]
- **Trade-offs**: [Performance vs. explainability, etc.]

**Assurance Activities**:
- [ ] Algorithm design review
- [ ] Explainability assessment
- [ ] Bias mitigation plan review
- [ ] DSTG technical review (if applicable)

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 5: Model Development

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] Training data documentation
- [ ] Data preprocessing pipeline
- [ ] Model training methodology
- [ ] Model card
- [ ] Performance evaluation report
- [ ] Bias analysis report
- [ ] Hyperparameter tuning log
- [ ] Version control and model registry

**Documentation Location**: [File path or reference]

**Training Data**:
- **Dataset Name/Version**: [Name v1.0]
- **Dataset Size**: [X samples]
- **Data Collection Method**: [How collected]
- **Data Labeling**: [Manual / Automated - quality checks]
- **Data Quality**: [Assessment results]
- **Data Bias**: [Bias assessment results]

**Model Performance**:
- **Training Performance**: [Metrics on training set]
- **Validation Performance**: [Metrics on validation set]
- **Test Performance**: [Metrics on held-out test set]
- **Cross-validation Results**: [If applicable]

**Assurance Activities**:
- [ ] Training data review
- [ ] Model performance review
- [ ] Bias testing completed
- [ ] Model card review

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 6: Verification and Validation (V&V)

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] V&V plan
- [ ] Test cases and scenarios
- [ ] V&V report
- [ ] Performance against requirements
- [ ] Robustness testing results
- [ ] Adversarial testing results
- [ ] User acceptance testing (UAT)
- [ ] Independent V&V report (for Critical/Severe)

**Documentation Location**: [File path or reference]

**Testing Coverage**:
- **Functional Testing**: [% scenarios covered]
- **Performance Testing**: [Results vs. requirements]
- **Robustness Testing**: [Edge cases, adversarial examples]
- **Security Testing**: [Penetration test results per ISM]
- **User Acceptance Testing**: [UAT completion status]

**V&V Results**:
- **Requirements Met**: [X / Y requirements passed]
- **Test Pass Rate**: [% of tests passed]
- **Critical Failures**: [Any critical issues found]
- **Performance vs. Baseline**: [Better / Same / Worse]

**Assurance Activities**:
- [ ] Independent V&V conducted (if Critical/Severe)
- [ ] Test results review
- [ ] Requirements traceability verified
- [ ] UAT sign-off

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 7: Integration and Use

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] Deployment plan
- [ ] Operational procedures (SOPs)
- [ ] User training materials
- [ ] Monitoring and alerting setup
- [ ] Incident response procedures
- [ ] Maintenance procedures
- [ ] Release notes

**Documentation Location**: [File path or reference]

**Deployment**:
- **Deployment Environment**: [Production / Staging / Pilot]
- **Deployment Date**: [Date]
- **Deployment Method**: [Blue-green / Canary / Rolling / Big bang]
- **Rollback Plan**: [Yes / No - describe]

**Operational Procedures**:
- **Standard Operating Procedures**: [SOPs documented]
- **User Guides**: [User documentation available]
- **Troubleshooting Guide**: [Common issues documented]
- **Escalation Procedures**: [Who to contact for issues]

**Training**:
- **Operator Training**: [Completion status]
- **Commander Training**: [Completion status]
- **Maintenance Training**: [Completion status]

**Assurance Activities**:
- [ ] Deployment review
- [ ] Operational readiness review
- [ ] Training completion verified
- [ ] Monitoring verified operational

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

### Phase 8: Quality Assurance

**Status**: [Not Started / In Progress / Completed]

**Documentation Required**:
- [ ] Compliance matrix (all AI Ethics Framework requirements)
- [ ] Quality assurance report
- [ ] Data integrity assessment
- [ ] Model performance monitoring report
- [ ] Ethical review report
- [ ] Security audit report (per ISM)
- [ ] Lessons learned

**Documentation Location**: [File path or reference]

**Compliance Matrix**:

| AI Ethics Framework Requirement | Status | Evidence | Comments |
|--------------------------------|--------|----------|----------|
| AI ethical risk classification | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Eight principles assessment | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Lifecycle documentation | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Governance structure | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Human-AI teaming | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Bias mitigation | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Explainability | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| ISM security controls | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| Continuous monitoring | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |
| IHL compliance (if applicable) | [Compliant/Partial/Non-Compliant] | [Reference] | [Comments] |

**Quality Metrics**:
- **Documentation Completeness**: [% complete]
- **Requirements Traceability**: [% traceable]
- **Test Coverage**: [% covered]
- **Defect Density**: [Defects per KLOC]

**Assurance Activities**:
- [ ] Independent ethical review
- [ ] Security audit conducted (per ISM)
- [ ] Compliance verification
- [ ] Final approval obtained

**Gaps/Actions**:
- [ ] [Action 1]
- [ ] [Action 2]

---

## 5. Governance and Approval

### 5.1 AI Governance Structure

**Responsible AI Officer**:
- **Name**: [Name]
- **Role**: [Role/Position]
- **Responsibilities**: [Overall AI governance, policy compliance, strategic oversight]

**Ethics Adviser**:
- **Name**: [Name]
- **Role**: [Role/Position]
- **Responsibilities**: [Day-to-day ethical oversight, ethics reviews, stakeholder engagement]

**Independent Ethics Assurance**:
- **Required**: [Yes / No - Required for Critical classification]
- **Assurance Provider**: [Name/Organisation]
- **Assurance Status**: [Not Started / In Progress / Completed]

**Defence Science and Technology Group (DSTG) Engagement**:
- **DSTG Consultation**: [Yes / No]
- **Technical Review Status**: [Not Started / In Progress / Completed]
- **Key Recommendations**: [Summary of DSTG input]

**Governance Board**:
- **Board Name**: [AI Ethics Board / Project Board / etc.]
- **Meeting Frequency**: [Monthly / Quarterly / As needed]
- **Last Meeting**: [Date]
- **Next Meeting**: [Date]

### 5.2 Approval Pathway

**Risk Classification**: [Critical / Severe / Major / Moderate / Minor]

**Approval Authority**: [Based on classification]
- **Critical (20-25)**: Secretary of Defence or Minister for Defence
- **Severe (15-19)**: Defence-Level - Defence Committee / CIOG
- **Major (10-14)**: Defence-Level - Defence Committee / CIOG
- **Moderate (5-9)**: Group-Level (delegated)
- **Minor (1-4)**: Group-Level (delegated)

**Approval Process**:
- [ ] Initial ethical screening (Ethics Adviser)
- [ ] Detailed AI Assurance Assessment (this document)
- [ ] Responsible AI Officer review and endorsement
- [ ] Independent assurance (if Critical)
- [ ] Ethics Board review
- [ ] Submission to approval authority
- [ ] Approval granted / Conditional approval / Rejected

**Approval History**:

| Date | Milestone | Approver | Decision | Conditions |
|------|-----------|----------|----------|------------|
| [Date] | Initial Screening | [Name] | [Approved/Conditional/Rejected] | [Any conditions] |
| [Date] | Responsible AI Officer Review | [Name] | [Approved/Conditional/Rejected] | [Any conditions] |
| [Date] | Ethics Board | [Name] | [Approved/Conditional/Rejected] | [Any conditions] |
| [Date] | Final Approval | [Authority] | [Approved/Conditional/Rejected] | [Any conditions] |

### 5.3 Escalation Criteria

**Escalation Triggers**:
- [ ] Risk classification increases
- [ ] Significant system changes
- [ ] Ethical concerns arise during deployment
- [ ] Performance degrades below acceptable bounds
- [ ] Serious incidents occur
- [ ] Bias or harm identified
- [ ] Security breach (per ISM incident response)
- [ ] IHL compliance concerns (for autonomous systems)
- [ ] AUKUS or Five Eyes information sharing incidents

**Escalation Process**: [Describe how and when to escalate]

**Escalation History**: [Log of any escalations]

---

## 6. Human-AI Teaming Strategy

### 6.1 Teaming Model

**For AI Component 1: [Name]**

**Teaming Model**: [Human-in-loop / Human-on-loop / Human-out-of-loop]

**Model Definition**:
- **Human-in-loop**: Human reviews every AI decision before action
- **Human-on-loop**: Human monitors AI with ability to intervene
- **Human-out-of-loop**: AI operates autonomously, humans set constraints

**Rationale**: [Why this teaming model was selected]

**Time Criticality**: [Time available for human intervention]

**IHL Considerations** (if applicable):
- **Lethal Autonomous Weapon System (LAWS)**: [Yes / No]
- **Human Control over Use of Force**: [Description of controls per IHL]
- **Meaningful Human Control**: [How meaningful human control is maintained]

### 6.2 Training Requirements

**Operator Training Programme**:
- **Duration**: [X hours/days]
- **Content**: [AI capabilities, limitations, SOPs, ethical considerations]
- **Competency Assessment**: [Written test / Practical assessment / Both]
- **Refresher Training**: [Frequency]
- **Training Completion**: [X% of operators trained]

**Commander Training Programme**:
- **Duration**: [X hours/days]
- **Content**: [Strategic use of AI, ethical decision-making, accountability]
- **Competency Assessment**: [Method]
- **Training Completion**: [X% of commanders trained]

**Technical Staff Training**:
- **Duration**: [X hours/days]
- **Content**: [Model maintenance, monitoring, troubleshooting]
- **Training Completion**: [X% of technical staff trained]

### 6.3 Human Control Interface

**Dashboard Design**:
- **Key Information Displayed**: [AI confidence, decision rationale, alerts, performance metrics]
- **Visualisation**: [How AI outputs are presented]
- **Alert Mechanisms**: [How operators are alerted to issues]
- **Control Mechanisms**: [How operators can intervene]

**Trust Calibration**:
- **Trust Indicators**: [How to help users trust AI appropriately - not too much, not too little]
- **Confidence Display**: [How AI confidence is communicated]
- **Uncertainty Handling**: [How system handles and communicates uncertainty]
- **Performance Feedback**: [How users learn about AI performance]

**Decision Support Features**:
- **Explanation Interface**: [How AI explains its decisions]
- **Alternative Options**: [Does AI show alternative decisions?]
- **Confidence Scores**: [Numerical / Graphical / Colour-coded]
- **Supporting Evidence**: [What evidence is shown to support AI decision]

**Override Mechanisms**:
- **Override Capability**: [Yes / No / Partial]
- **Override Process**: [How operators override AI]
- **Override Logging**: [All overrides logged and reviewed]
- **Override Feedback**: [Overrides used to improve AI]

---

## 7. Secure by Design Evidence

### 7.1 AI-Specific Threat Landscape

> Security assessment aligned with ASD Information Security Manual (ISM) and ASD Essential Eight.

**Adversarial Examples**:
- **Threat**: Carefully crafted inputs that fool the AI
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Adversarial training, input validation, ensemble methods]

**Data Poisoning**:
- **Threat**: Malicious data injected into training set
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Data provenance, data validation, anomaly detection]

**Model Extraction**:
- **Threat**: Adversary steals model through queries
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Query limits, differential privacy, model obfuscation]

**Model Inversion**:
- **Threat**: Adversary reconstructs training data
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Differential privacy, aggregation, access controls]

**Backdoor Attacks**:
- **Threat**: Hidden triggers cause malicious behaviour
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Model inspection, trigger detection, diverse training data]

**Concept Drift**:
- **Threat**: Real-world data distribution changes over time
- **Likelihood**: [High / Medium / Low]
- **Impact**: [High / Medium / Low]
- **Risk**: [Critical / High / Medium / Low]
- **Mitigation**: [Continuous monitoring, drift detection, retraining]

### 7.2 AI-Specific Security Controls

> Controls aligned with ASD Information Security Manual (ISM) and Essential Eight Maturity Model.

**Input Validation**:
- [ ] Input bounds checking
- [ ] Anomaly detection on inputs
- [ ] Adversarial example detection
- [ ] Input sanitisation

**Adversarial Defences**:
- [ ] Adversarial training
- [ ] Input transformations
- [ ] Ensemble methods
- [ ] Certified defences

**Model Security**:
- [ ] Model access controls
- [ ] Query rate limiting
- [ ] Model versioning and integrity
- [ ] Secure model storage

**Data Security**:
- [ ] Training data access controls
- [ ] Data encryption (at rest and in transit per ISM)
- [ ] Data provenance tracking
- [ ] Differential privacy

**Monitoring and Detection**:
- [ ] Input monitoring for attacks
- [ ] Output monitoring for anomalies
- [ ] Performance monitoring for drift
- [ ] Security event logging (per ISM)

**ISM Compliance**:
- [ ] ISM controls mapped and implemented
- [ ] ASD Essential Eight controls at required maturity level
- [ ] PSPF compliance for information handling
- [ ] IRAP assessment completed (if cloud-hosted)

### 7.3 Security Testing

**Adversarial Testing**:
- **Testing Method**: [FGSM / PGD / C&W / Other]
- **Attack Success Rate**: [% of adversarial examples that fooled model]
- **Robust Accuracy**: [Accuracy under adversarial attack]
- **Mitigation Effectiveness**: [How well defences work]

**Penetration Testing**:
- **AI-Specific Pentest**: [Yes / No]
- **Pentest Date**: [Date]
- **Findings**: [Critical: X, High: Y, Medium: Z, Low: W]
- **Remediation Status**: [X% remediated]

**Red Teaming**:
- **Red Team Exercise**: [Yes / No]
- **Exercise Date**: [Date]
- **Scenarios Tested**: [Data poisoning, model extraction, adversarial attacks, etc.]
- **Findings**: [Summary of red team findings]

**ASD Certification**:
- **ASD Certification Required**: [Yes / No]
- **Certification Status**: [Certified / In Progress / Not Started]
- **Certification Date**: [Date]
- **Conditions**: [Any certification conditions]

---

## 8. Supplier Assurance (if applicable)

**Third-Party AI Components**: [Yes / No]

### 8.1 Supplier Details

**Supplier 1: [Name]**

**Component Provided**: [Pre-trained model / Dataset / AI service / etc.]

**Supplier Assessment**:
- [ ] Supplier competence verified (AI expertise)
- [ ] Data provenance documented
- [ ] Model transparency provided
- [ ] Security practices assessed
- [ ] AI Ethics Framework compliance verified
- [ ] Ethical AI practices verified
- [ ] Contract includes AI-specific clauses
- [ ] DISP membership verified (if Defence industry engagement)

**Data Provenance**:
- **Training Data Source**: [Where supplier obtained data]
- **Data Quality**: [Supplier's data quality processes]
- **Bias Assessment**: [Supplier's bias testing results]
- **Data Rights**: [Licensing and usage rights]

**Model Transparency**:
- **Model Card Provided**: [Yes / No]
- **Architecture Details**: [Level of detail provided]
- **Performance Metrics**: [Metrics provided by supplier]
- **Known Limitations**: [Documented by supplier]

**Security**:
- **Security Certifications**: [ISO 27001, ASD Essential Eight Maturity Level 3, IRAP assessed, etc.]
- **Vulnerability Disclosure**: [Supplier's process]
- **Incident Response**: [Supplier's IR process]
- **Supply Chain Security**: [Supplier's supply chain assurance]

**Australian Defence Compliance**:
- **AI Ethics Framework Compliance**: [Supplier assessed against 8 Principles]
- **ISM Compliance**: [Supplier meets ISM requirements]
- **Privacy Act 1988 and Australian Privacy Principles Compliance**: [Data protection]
- **PSPF Compliance**: [Protective security]
- **DISP Membership**: [Defence Industry Security Program status]
- **AUKUS Considerations**: [Technology sharing implications]
- **Five Eyes Considerations**: [Intelligence sharing implications]

**Personnel Security (if supplier personnel access classified information)**:
- **Baseline Vetting**: [Equivalent to UNOFFICIAL/OFFICIAL access]
- **NV1 Clearance**: [For PROTECTED information access]
- **NV2 Clearance**: [For SECRET information access]
- **PV Clearance**: [For TOP SECRET information access]
- **Crimes Act 1914 (Part VII)**: [Obligations acknowledged]

**Ongoing Assurance**:
- **Monitoring**: [How supplier performance is monitored]
- **Reviews**: [Frequency of supplier reviews]
- **SLAs**: [Service level agreements]
- **Exit Strategy**: [Plan if supplier relationship ends]

---

## 9. Continuous Monitoring and Re-Assessment Plan

### 9.1 Real-Time Monitoring

**Performance Monitoring**:
- **Metrics Tracked**: [Accuracy, latency, throughput, error rate]
- **Monitoring Frequency**: [Real-time / Hourly / Daily]
- **Alert Thresholds**: [When alerts triggered]
- **Monitoring Dashboard**: [URL or location]

**Bias Monitoring**:
- **Metrics Tracked**: [Fairness metrics by demographic group]
- **Monitoring Frequency**: [Real-time / Daily / Weekly]
- **Alert Thresholds**: [Bias threshold for alerts]

**Security Monitoring**:
- **Threats Monitored**: [Adversarial inputs, anomalies, attacks]
- **Monitoring Tools**: [SIEM, anomaly detection, per ISM requirements]
- **Alert Thresholds**: [Security alert triggers]

**Drift Detection**:
- **Data Drift Monitoring**: [Input distribution changes]
- **Concept Drift Monitoring**: [Model performance degradation]
- **Monitoring Method**: [Statistical tests, performance tracking]
- **Alert Thresholds**: [Drift alert triggers]

### 9.2 Periodic Reporting

**Daily Reports**:
- System uptime and availability
- Error rates and failures
- Security alerts

**Weekly Reports**:
- Performance metrics trends
- User feedback summary
- Incident summary

**Monthly Reports**:
- Detailed performance analysis
- Bias assessment results
- Security posture summary
- Drift analysis
- Incidents and resolutions

**Quarterly Reports**:
- Comprehensive AI Ethics Framework compliance review
- Ethics Adviser review
- Risk re-assessment
- Governance Board review

### 9.3 Retraining Triggers

**Automatic Retraining Triggers**:
- [ ] Performance drops below [X%] threshold
- [ ] Significant data drift detected
- [ ] Bias increases beyond acceptable threshold
- [ ] New data volume reaches [X] samples

**Manual Retraining Triggers**:
- [ ] Operational environment changes
- [ ] New requirements added
- [ ] Security vulnerabilities discovered
- [ ] Ethical concerns arise
- [ ] Scheduled retraining (every [X] months)

**Retraining Process**:
- [ ] Trigger detected and validated
- [ ] New training data collected and validated
- [ ] Model retrained following Phase 5 process
- [ ] Revalidated following Phase 6 process
- [ ] Ethics Adviser approval for redeployment
- [ ] Deployment following Phase 7 process

### 9.4 Annual AI Ethics Framework Compliance Review

**Annual Review Process**:
- [ ] Full re-assessment of all Eight Principles
- [ ] Risk re-classification
- [ ] Lifecycle documentation review
- [ ] Governance structure review
- [ ] Human-AI teaming effectiveness review
- [ ] Security audit (per ISM)
- [ ] Bias assessment
- [ ] Performance review
- [ ] Stakeholder consultation
- [ ] IHL compliance review (if applicable)
- [ ] AUKUS and Five Eyes obligations review (if applicable)

**Review Schedule**:
- **Last Annual Review**: [Date]
- **Next Annual Review**: [Date]

**Re-Approval Process**:
- [ ] Updated AI Assurance Assessment (this document)
- [ ] Ethics Adviser review
- [ ] Responsible AI Officer endorsement
- [ ] Submission to original approval authority
- [ ] Re-approval granted / Conditional / System decommissioned

### 9.5 System Retirement Criteria

**Retirement Triggers**:
- [ ] Risk classification increases to unacceptable level
- [ ] Performance degrades below minimum acceptable
- [ ] Ethical concerns cannot be mitigated
- [ ] Security vulnerabilities cannot be remediated
- [ ] Technology becomes obsolete
- [ ] Operational requirements change
- [ ] Cost-benefit analysis no longer favourable

**Retirement Process**:
- [ ] Retirement decision documented
- [ ] Stakeholder notification
- [ ] Alternative solution identified
- [ ] Graceful decommissioning plan
- [ ] Data archival or deletion (per PSPF and ISM)
- [ ] Lessons learned documentation
- [ ] Final report to governance

---

## 10. Australian Defence AI Assurance Compliance Matrix

### Compliance Summary

| AI Assurance Requirement | Status | Evidence Location | Comments |
|--------------------------|--------|-------------------|----------|
| **Ethical Risk Classification** | | | |
| Risk assessment completed | [Compliant/Partial/Non-Compliant] | Section 2 | [Comments] |
| Likelihood assessed (1-5) | [Compliant/Partial/Non-Compliant] | Section 2.1 | [Comments] |
| Impact assessed (1-5) | [Compliant/Partial/Non-Compliant] | Section 2.1 | [Comments] |
| Risk score calculated | [Compliant/Partial/Non-Compliant] | Section 2.1 | [Comments] |
| Classification assigned | [Compliant/Partial/Non-Compliant] | Section 2 | [Comments] |
| Unacceptable risk check | [Compliant/Partial/Non-Compliant] | Section 2.1 | [Comments] |
| **Eight AI Ethics Principles** | | | |
| Human, societal and environmental wellbeing | [Compliant/Partial/Non-Compliant] | Section 3.1 | [Comments] |
| Human-centred values | [Compliant/Partial/Non-Compliant] | Section 3.2 | [Comments] |
| Fairness assessed | [Compliant/Partial/Non-Compliant] | Section 3.3 | [Comments] |
| Privacy protection and security | [Compliant/Partial/Non-Compliant] | Section 3.4 | [Comments] |
| Reliability and safety | [Compliant/Partial/Non-Compliant] | Section 3.5 | [Comments] |
| Transparency and explainability | [Compliant/Partial/Non-Compliant] | Section 3.6 | [Comments] |
| Contestability mechanisms | [Compliant/Partial/Non-Compliant] | Section 3.7 | [Comments] |
| Accountability assigned | [Compliant/Partial/Non-Compliant] | Section 3.8 | [Comments] |
| **AI Lifecycle Documentation** | | | |
| Phase 1: Planning | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 2: Requirements | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 3: Architecture | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 4: Algorithm Design | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 5: Model Development | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 6: V&V | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 7: Integration and Use | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| Phase 8: Quality Assurance | [Compliant/Partial/Non-Compliant] | Section 4 | [Comments] |
| **Governance** | | | |
| Responsible AI Officer assigned | [Compliant/Partial/Non-Compliant] | Section 5.1 | [Comments] |
| Ethics Adviser assigned | [Compliant/Partial/Non-Compliant] | Section 5.1 | [Comments] |
| Independent assurance (if Critical) | [Compliant/Partial/Non-Compliant] | Section 5.1 | [Comments] |
| DSTG engagement (if applicable) | [Compliant/Partial/Non-Compliant] | Section 5.1 | [Comments] |
| Governance board established | [Compliant/Partial/Non-Compliant] | Section 5.1 | [Comments] |
| Approval pathway followed | [Compliant/Partial/Non-Compliant] | Section 5.2 | [Comments] |
| Escalation process defined | [Compliant/Partial/Non-Compliant] | Section 5.3 | [Comments] |
| **Human-AI Teaming** | | | |
| Teaming model defined | [Compliant/Partial/Non-Compliant] | Section 6.1 | [Comments] |
| IHL compliance (if applicable) | [Compliant/Partial/Non-Compliant] | Section 6.1 | [Comments] |
| Training programme delivered | [Compliant/Partial/Non-Compliant] | Section 6.2 | [Comments] |
| Human control interface designed | [Compliant/Partial/Non-Compliant] | Section 6.3 | [Comments] |
| Trust calibration addressed | [Compliant/Partial/Non-Compliant] | Section 6.3 | [Comments] |
| Override mechanisms provided | [Compliant/Partial/Non-Compliant] | Section 6.3 | [Comments] |
| **Secure by Design** | | | |
| AI threat landscape assessed | [Compliant/Partial/Non-Compliant] | Section 7.1 | [Comments] |
| AI-specific controls implemented | [Compliant/Partial/Non-Compliant] | Section 7.2 | [Comments] |
| ISM controls mapped | [Compliant/Partial/Non-Compliant] | Section 7.2 | [Comments] |
| Security testing completed | [Compliant/Partial/Non-Compliant] | Section 7.3 | [Comments] |
| ASD certification (if required) | [Compliant/Partial/Non-Compliant] | Section 7.3 | [Comments] |
| **Supplier Assurance** (if applicable) | | | |
| Supplier assessment completed | [Compliant/Partial/Non-Compliant] | Section 8 | [Comments] |
| Data provenance documented | [Compliant/Partial/Non-Compliant] | Section 8.1 | [Comments] |
| Model transparency provided | [Compliant/Partial/Non-Compliant] | Section 8.1 | [Comments] |
| Supplier Defence compliance verified | [Compliant/Partial/Non-Compliant] | Section 8.1 | [Comments] |
| DISP membership verified | [Compliant/Partial/Non-Compliant] | Section 8.1 | [Comments] |
| **Defence-Specific Requirements** | | | |
| AUKUS considerations addressed | [Compliant/Partial/Non-Compliant] | Various | [Comments] |
| Five Eyes considerations addressed | [Compliant/Partial/Non-Compliant] | Various | [Comments] |
| IHL compliance (autonomous systems) | [Compliant/Partial/Non-Compliant] | Sections 2, 6 | [Comments] |
| Personnel security clearances | [Compliant/Partial/Non-Compliant] | Section 8.1 | [Comments] |
| **Continuous Monitoring** | | | |
| Real-time monitoring implemented | [Compliant/Partial/Non-Compliant] | Section 9.1 | [Comments] |
| Periodic reporting established | [Compliant/Partial/Non-Compliant] | Section 9.2 | [Comments] |
| Drift detection operational | [Compliant/Partial/Non-Compliant] | Section 9.1 | [Comments] |
| Retraining triggers defined | [Compliant/Partial/Non-Compliant] | Section 9.3 | [Comments] |
| Annual review scheduled | [Compliant/Partial/Non-Compliant] | Section 9.4 | [Comments] |
| Retirement criteria defined | [Compliant/Partial/Non-Compliant] | Section 9.5 | [Comments] |

**Overall Compliance**: [X% Complete]

**Critical Gaps**: [Number of critical gaps requiring immediate attention]

**Approval Recommendation**: [Ready for Approval / Conditional Approval / Not Ready]

---

## Appendices

### Appendix A: Risk Assessment Methodology

[Detailed explanation of how risk assessment was conducted]

### Appendix B: Ethical Risk Checklist

[Complete checklist of all ethical risks considered against the 8 AI Ethics Principles]

### Appendix C: Approval Process Flowchart

[Flowchart showing approval pathway for this risk classification]

### Appendix D: Model Card

[Detailed model card following standard template]

### Appendix E: Data Card

[Detailed data card documenting training data]

### Appendix F: Bias Assessment Report

[Full bias assessment results]

### Appendix G: V&V Report

[Verification and validation report]

### Appendix H: Security Test Report

[Adversarial testing and penetration test results per ISM]

### Appendix I: Training Materials

[Links to or excerpts from training materials]

### Appendix J: Monitoring Dashboard Screenshots

[Visual examples of monitoring dashboards]

### Appendix K: ISM Controls Mapping

[Mapping of applicable ISM controls to AI system components]

### Appendix L: AUKUS and Five Eyes Compliance

[Assessment of technology sharing and intelligence sharing obligations]

### Appendix M: IHL Compliance Assessment

[International Humanitarian Law compliance assessment for autonomous systems, if applicable]

---

## Approval and Sign-Off

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Project Lead | [Name] | | |
| Technical Lead | [Name] | | |
| Ethics Adviser | [Name] | | |
| Responsible AI Officer | [Name] | | |
| DSTG Reviewer (if applicable) | [Name] | | |
| Independent Assurance (if Critical) | [Name/Org] | | |
| Approval Authority | [Name/Position] | | |

---

**Document Control**:
- **Version**: 1.0
- **Classification**: [OFFICIAL / OFFICIAL: Sensitive / PROTECTED]
- **Last Reviewed**: [Date]
- **Next Review**: [Date - annual minimum]
- **Document Owner**: [Name/Role]
- **Related Documents**:
  - Australia's AI Ethics Framework (Department of Industry, Science and Resources)
  - Australian Defence AI Strategy
  - ASD Information Security Manual (ISM)
  - Protective Security Policy Framework (PSPF)
  - Privacy Act 1988 and Australian Privacy Principles
  - Defence Industry Security Program (DISP) Guidelines
  - Hosting Certification Framework (HCF)
  - Project Architecture Documentation
  - Project Requirements Documentation
  - Risk Register
  - Security Assessment

## External References

| Document | Type | Source | Key Extractions | Path |
|----------|------|--------|-----------------|------|
| Australia's AI Ethics Framework | Framework | Dept of Industry, Science and Resources | 8 AI Ethics Principles | [URL/Path] |
| Information Security Manual (ISM) | Standard | ASD | Security controls | [URL/Path] |
| PSPF | Policy | Attorney-General's Dept | Protective security | [URL/Path] |
| Crimes Act 1914 (Part VII) | Legislation | Commonwealth | Secrecy obligations | [URL/Path] |
| *None additional provided* | -- | -- | -- | -- |

---

**Generated by**: ArcKit `/arckit.jsp-936` command
**Generated on**: [DATE]
**ArcKit Version**: [VERSION]
**Project**: [PROJECT_NAME]
**Model**: [AI_MODEL]
