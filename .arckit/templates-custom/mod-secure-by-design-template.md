# Australian Defence Secure by Design Assessment

> **Template Status**: Experimental | **Version**: [VERSION] | **Command**: `/arckit.mod-secure`

## Document Control

| Field | Value |
|-------|-------|
| **Document ID** | ARC-[PROJECT_ID]-SECD-MOD-v[VERSION] |
| **Document Type** | [DOCUMENT_TYPE_NAME] |
| **Project** | [PROJECT_NAME] (Project [PROJECT_ID]) |
| **Classification** | [PUBLIC / OFFICIAL / OFFICIAL: Sensitive / PROTECTED / SECRET] |
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

## Revision History

| Version | Date | Author | Changes | Approved By | Approval Date |
|---------|------|--------|---------|-------------|---------------|
| [VERSION] | [DATE] | ArcKit AI | Initial creation from `/arckit.[COMMAND]` command | [PENDING] | [PENDING] |

## Document Purpose

[Brief description of what this document is for and how it will be used. This assessment evaluates the security posture of a Department of Defence system against the Australian Defence security frameworks including the ISM, DSPF, DISP, and ASD Essential Eight.]

---

## Executive Summary

**Overall Security Posture**: [Strong / Adequate / Needs Improvement / Inadequate]

**Key Security Findings**:
- [Summary of critical security gaps]
- [Summary of security strengths]
- [Blocking security issues]

**ASD Certification Status**: [Not Started / In Progress / Certified / Conditional Certification]

**Essential Eight Maturity Level**: [Level 0 / Level 1 / Level 2 / Level 3]

**Risk Summary**: [Overall security risk level: Low / Medium / High / Very High]

---

## 1. Security Classification and Data Handling

### 1.1 Information Classification

**Highest Data Classification**: [OFFICIAL / OFFICIAL: Sensitive / PROTECTED / SECRET / TOP SECRET]

**Classification Justification**:
[Explain why this classification level is required, referencing the PSPF information classification system]

**Data Types Processed**:
- [ ] Personal data (Privacy Act 1988 and Australian Privacy Principles)
- [ ] Special category data (biometric, health, etc.)
- [ ] Classified Defence information
- [ ] Operational data
- [ ] Intelligence data
- [ ] Cryptographic material
- [ ] Protectively marked documents (per PSPF markings)
- [ ] National security information

**Data Classification Matrix**:

| Data Type | Classification | Volume | Storage Location | Access Controls |
|-----------|---------------|---------|------------------|-----------------|
| [e.g., Personnel records] | OFFICIAL: Sensitive | [High/Med/Low] | [Location] | [RBAC/MFA/etc] |
| [e.g., Operational plans] | PROTECTED | [High/Med/Low] | [Location] | [RBAC/MFA/etc] |
| [e.g., Strategic intelligence] | SECRET | [High/Med/Low] | [Location] | [RBAC/MFA/etc] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 2. Australian Defence Security Principles Compliance

### 2.1 Defence in Depth

**Principle**: Multiple layers of security controls so that if one fails, others continue to protect. Aligned with ISM guidelines on implementing layered security.

**Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**:
[Describe layered security controls implemented]

**Security Layers Implemented**:
- [ ] Physical security (data centre, building access per DSPF requirements)
- [ ] Network security (firewalls, segmentation, IDS/IPS)
- [ ] Host security (hardened OS per ASD hardening guides, endpoint protection)
- [ ] Application security (WAF, input validation, secure coding)
- [ ] Data security (encryption at rest and in transit per ISM cryptographic controls)
- [ ] Identity security (MFA, privileged access management)
- [ ] Monitoring and detection (SIEM, SOC, integration with ASD/ACSC threat intelligence)

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 2.2 Secure by Default

**Principle**: Systems are secure out-of-the-box with minimal configuration required. Aligned with ISM secure configuration guidelines.

**Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**:
[Describe default security configurations]

**Default Security Configurations**:
- [ ] Strong authentication required by default
- [ ] ASD-approved encryption enabled by default
- [ ] Least privilege access model
- [ ] Secure protocols only (TLS 1.2+ per ISM, SSH v2)
- [ ] Security headers configured
- [ ] Default accounts disabled/removed
- [ ] Logging enabled by default (per ISM event logging requirements)

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 2.3 Least Privilege

**Principle**: Users and systems have only the minimum access required to perform their functions. Aligned with ISM access control guidelines and PSPF need-to-know principles.

**Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**:
[Describe access control implementation]

**Access Controls**:
- [ ] Role-Based Access Control (RBAC) implemented
- [ ] Principle of least privilege enforced
- [ ] Privileged access management (PAM) in place
- [ ] Just-in-time (JIT) access for elevated privileges
- [ ] Regular access reviews conducted
- [ ] Separation of duties enforced
- [ ] Need-to-know access restrictions applied per PSPF

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 2.4 Assume Breach

**Principle**: Design and operate as if compromise has already occurred. Aligned with ASD/ACSC cyber resilience guidance.

**Status**: [Compliant | Partially Compliant | Non-Compliant]

**Evidence**:
[Describe breach detection and response capabilities]

**Breach Readiness**:
- [ ] Security monitoring and alerting (integrated with ACSC threat feeds)
- [ ] Incident response plan documented and tested
- [ ] Forensic capabilities available
- [ ] Network segmentation to limit blast radius
- [ ] Zero-trust architecture principles applied
- [ ] Regular red team/penetration testing (IRAP-assessed where required)

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 3. Australian Defence Certification and Accreditation

### 3.1 Security Certification Status

**Certification Authority**: [ASD / Department of Defence CISO / Defence Digital]

**Certification Type**: [Full Certification / Interim Certification / Risk Managed Certification]

**Certification Progress**:
- [ ] System security risk assessment completed
- [ ] System Security Plan (SSP) documented
- [ ] Security Assessment Report (SAR) completed
- [ ] IRAP assessment engaged (where required)
- [ ] ISM controls assessment completed
- [ ] Essential Eight maturity assessment completed
- [ ] Residual risks accepted by Authorising Officer
- [ ] ASD certification granted

**System Owner / Authorising Officer**: [Name/Role]
**Chief Information Security Officer (CISO)**: [Name/Role]
**Information Technology Security Adviser (ITSA)**: [Name/Role]

**Target Certification Date**: [Date]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 3.2 ISM Controls Compliance

**ISM (Information Security Manual)**: ASD's cybersecurity framework for Australian Government systems.

**ISM Compliance Target**: [All applicable controls at [OFFICIAL / PROTECTED / SECRET] classification]

**ISM Control Assessment**:

| ISM Control Group | Applicable Controls | Implemented | Partially Implemented | Not Implemented | Gap Summary |
|-------------------|--------------------:|------------:|----------------------:|----------------:|-------------|
| Guidelines for Cyber Security Roles | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Cyber Security Incidents | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Outsourcing | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Security Documentation | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Physical Security | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Personnel Security | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Communications Infrastructure | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Communications Systems | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Enterprise Mobility | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for System Hardening | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for System Management | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for System Monitoring | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Software Development | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Database Systems | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Email | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Networking | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Cryptography | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Gateways | [Count] | [Count] | [Count] | [Count] | [Gap description] |
| Guidelines for Data Transfers | [Count] | [Count] | [Count] | [Count] | [Gap description] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 3.3 ASD Essential Eight Maturity Assessment

**Essential Eight Maturity Model**: ASD's prioritised mitigation strategies for cyber security.

**Target Maturity Level**: [Level 1 / Level 2 / Level 3]

**Essential Eight Assessment**:

| Mitigation Strategy | Current Maturity Level | Target Maturity Level | Gap |
|---------------------|----------------------:|----------------------:|-----|
| Application Control | [0/1/2/3] | [1/2/3] | [Gap description] |
| Patch Applications | [0/1/2/3] | [1/2/3] | [Gap description] |
| Configure Microsoft Office Macro Settings | [0/1/2/3] | [1/2/3] | [Gap description] |
| User Application Hardening | [0/1/2/3] | [1/2/3] | [Gap description] |
| Restrict Administrative Privileges | [0/1/2/3] | [1/2/3] | [Gap description] |
| Patch Operating Systems | [0/1/2/3] | [1/2/3] | [Gap description] |
| Multi-Factor Authentication | [0/1/2/3] | [1/2/3] | [Gap description] |
| Regular Backups | [0/1/2/3] | [1/2/3] | [Gap description] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 3.4 DSPF Compliance

**DSPF (Defence Security Principles Framework)**: Defence's overarching security governance framework.

**DSPF Governance Areas**:

| DSPF Principle | Status | Evidence | Gap |
|----------------|--------|----------|-----|
| Security governance | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |
| Personnel security | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |
| Physical security | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |
| Information security | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |
| Cyber security | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |
| Security awareness | [Compliant / Partial / Non-Compliant] | [Evidence] | [Gap description] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 4. Threat Modeling and Risk Assessment

### 4.1 Threat Model

**Threat Modeling Method**: [STRIDE / PASTA / Attack Trees / Other]

**Threat Model Completed**: [Yes / No / In Progress]

**Identified Threat Actors**:
- [ ] Nation state actors (per ASD threat landscape assessments)
- [ ] Terrorist organisations
- [ ] Organised crime
- [ ] Hacktivists
- [ ] Insider threats
- [ ] Supply chain threats
- [ ] Foreign intelligence services

**Key Threats Identified**:

| Threat | Likelihood | Impact | Risk Level | Mitigation |
|--------|------------|--------|------------|------------|
| [e.g., Data exfiltration] | [H/M/L] | [H/M/L] | [Critical/High/Med/Low] | [Control description] |
| [e.g., Ransomware] | [H/M/L] | [H/M/L] | [Critical/High/Med/Low] | [Control description] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 4.2 Security Risk Assessment

**Risk Assessment Method**: [ISM risk management framework / ISO 27005 / AS/NZS ISO 31000 / Other]

**Risk Register Maintained**: [Yes / No]

**Critical/High Risks**:

| Risk ID | Risk Description | Likelihood | Impact | Risk Level | Owner | Mitigation Plan |
|---------|------------------|------------|--------|------------|-------|-----------------|
| [R-001] | [Description] | [H/M/L] | [H/M/L] | [C/H/M/L] | [Name] | [Plan] |
| [R-002] | [Description] | [H/M/L] | [H/M/L] | [C/H/M/L] | [Name] | [Plan] |

**Residual Risks**: [Number of risks accepted by Authorising Officer]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 5. Technical Security Controls

### 5.1 Cryptography

**Cryptographic Standards**: [ASD-approved algorithms per ISM cryptographic guidelines]

**Encryption Implementation**:
- [ ] Data at rest encrypted (AES-256 minimum per ISM)
- [ ] Data in transit encrypted (TLS 1.2+ per ISM)
- [ ] Database encryption enabled
- [ ] Backup encryption enabled
- [ ] Key management system implemented
- [ ] ASD-approved cryptography used for classified data (PROTECTED and above)
- [ ] Crypto key lifecycle managed per ISM guidelines
- [ ] High Assurance cryptographic equipment for SECRET and above (where required)

**Key Management**:
- Key storage: [HSM / Cloud KMS / Other]
- Key rotation frequency: [e.g., 90 days]
- Key backup and recovery: [Yes / No]
- Compliance with ISM key management controls: [Yes / No]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 5.2 Authentication and Identity

**Authentication Method**: [Smart card / Biometric / MFA / SSO]

**Identity Provider**: [Defence Active Directory / Azure AD / myGov Digital Identity / Other]

**Authentication Controls**:
- [ ] Multi-factor authentication (MFA) enforced (Essential Eight requirement)
- [ ] Password complexity requirements (per ISM — 14+ chars for privileged, complexity rules)
- [ ] Smart card / hardware token authentication for classified systems
- [ ] Session timeout configured
- [ ] Account lockout after failed attempts
- [ ] Single Sign-On (SSO) where appropriate
- [ ] Privileged access management (PAM) per ISM and Essential Eight
- [ ] Phishing-resistant MFA for privileged users (Essential Eight Level 3)

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 5.3 Network Security

**Network Architecture**: [Segmented / Flat / DMZ / Zero Trust]

**Network Security Controls**:
- [ ] Network segmentation by security zone per ISM gateway guidelines
- [ ] Firewalls at zone boundaries
- [ ] Intrusion Detection/Prevention Systems (IDS/IPS)
- [ ] DDoS protection
- [ ] Web Application Firewall (WAF)
- [ ] VPN for remote access (ASD-approved where required)
- [ ] Network Access Control (NAC)
- [ ] Air-gapped networks for SECRET and above (if applicable)
- [ ] Cross Domain Solutions (CDS) assessed per ISM for data transfers between classifications

**Network Zones**:
- [ ] Public zone (internet-facing)
- [ ] DMZ (semi-trusted)
- [ ] Internal zone (trusted)
- [ ] Management zone (privileged access)
- [ ] Classified zone (PROTECTED and above)
- [ ] Restricted zone (SECRET and above)

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 5.4 Vulnerability Management

**Vulnerability Scanning**: [Frequency: Weekly / Monthly / Continuous]

**Scanning Tools**: [Nessus / Qualys / Rapid7 / Other]

**Vulnerability Management Process**:
- [ ] Automated vulnerability scanning
- [ ] Manual penetration testing (annual minimum, IRAP-assessed where required)
- [ ] Patch management process defined (aligned with Essential Eight patching requirements)
- [ ] Extreme risk patches applied within 48 hours (Essential Eight Level 3)
- [ ] Critical patches for internet-facing services applied within 2 weeks (Essential Eight Level 2)
- [ ] All patches applied within 1 month of release (Essential Eight Level 1)
- [ ] Vulnerability remediation tracking
- [ ] Exception process for unfixable vulnerabilities

**Recent Penetration Test**: [Date / Not Yet Conducted]
**Penetration Test Findings**: [Critical: X, High: Y, Medium: Z]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 5.5 Security Monitoring and Logging

**Security Operations Centre (SOC)**: [24/7 Defence SOC / ACSC partnership / 3rd party / None]

**SIEM Solution**: [Splunk / ArcSight / Sentinel / Other]

**Logging and Monitoring**:
- [ ] Centralised log collection (SIEM) per ISM event logging guidelines
- [ ] Real-time security alerting
- [ ] Log retention (minimum 7 years for Defence systems per ISM)
- [ ] Security event correlation
- [ ] User behaviour analytics (UBA)
- [ ] Automated incident response playbooks
- [ ] Integration with ASD/ACSC Cyber Threat Intelligence (CTI) feeds
- [ ] Reporting to ACSC for significant cyber security incidents

**Security Alerts**:
- Failed authentication attempts: [Monitored / Not monitored]
- Privilege escalation: [Monitored / Not monitored]
- Data exfiltration attempts: [Monitored / Not monitored]
- Malware detection: [Monitored / Not monitored]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 6. Secure Development Lifecycle

### 6.1 Secure Coding Practices

**Secure Coding Standards**: [OWASP / CERT / ASD Secure Development Guidelines / ISM Software Development Guidelines]

**Secure Development Practices**:
- [ ] Secure coding training for developers
- [ ] Code review process includes security review
- [ ] Static Application Security Testing (SAST)
- [ ] Dynamic Application Security Testing (DAST)
- [ ] Software Composition Analysis (SCA) for dependencies
- [ ] Threat modeling during design phase
- [ ] Security testing in CI/CD pipeline
- [ ] Application control whitelisting per Essential Eight

**OWASP Top 10 Mitigation**:
- [ ] Injection flaws prevented (SQLi, XSS, etc.)
- [ ] Broken authentication prevented
- [ ] Sensitive data exposure prevented
- [ ] XML External Entities (XXE) prevented
- [ ] Broken access control prevented
- [ ] Security misconfiguration prevented
- [ ] Cross-Site Scripting (XSS) prevented
- [ ] Insecure deserialization prevented
- [ ] Using components with known vulnerabilities prevented
- [ ] Insufficient logging and monitoring addressed

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 6.2 DevSecOps Integration

**CI/CD Security Gates**:
- [ ] Automated security scanning in pipeline
- [ ] Secrets scanning (no hardcoded credentials)
- [ ] Dependency vulnerability scanning
- [ ] Container image scanning (per ISM virtualisation and containerisation controls)
- [ ] Infrastructure as Code (IaC) security scanning
- [ ] Build artifact signing and verification
- [ ] Application control enforcement per Essential Eight

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 7. Supply Chain Security

### 7.1 Third-Party Risk Management

**Vendor Security Assessment**:
- [ ] Vendor security questionnaires completed
- [ ] Vendor security certifications verified (ISO 27001, IRAP assessment, Essential Eight maturity)
- [ ] Vendor access controls defined and enforced
- [ ] Third-party code review conducted
- [ ] Supply chain risk assessment completed
- [ ] DISP (Defence Industry Security Program) membership verified for Defence suppliers
- [ ] Vendor compliance with PSPF requirements confirmed

**Third-Party Components**:

| Component | Vendor | Security Rating | DISP Member | Risk Level | Mitigations |
|-----------|--------|-----------------|-------------|------------|-------------|
| [e.g., Cloud provider] | [Vendor] | [High/Med/Low] | [Yes/No] | [H/M/L] | [Controls] |
| [e.g., Software library] | [Vendor] | [High/Med/Low] | [N/A] | [H/M/L] | [Controls] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 7.2 Open Source Software Security

**Open Source Components**: [Number of OSS dependencies]

**OSS Security Controls**:
- [ ] Software Bill of Materials (SBOM) generated
- [ ] Known vulnerabilities scanned (CVE database, ASD advisories)
- [ ] License compliance verified
- [ ] OSS component lifecycle managed
- [ ] Alternative components evaluated for high-risk OSS
- [ ] Application control enforcement for approved software per Essential Eight

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 7.3 DISP Compliance

**Defence Industry Security Program (DISP)**: Obligations for organisations accessing Defence information and assets.

**DISP Membership Level**: [Not Required / Member / Compliant / Not Yet Applied]

**DISP Obligations**:
- [ ] Security governance obligations met
- [ ] Personnel security obligations met (clearance sponsorship, foreign national management)
- [ ] Physical security obligations met
- [ ] Information and cyber security obligations met
- [ ] DISP annual compliance reporting completed

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 8. Operational Security

### 8.1 Backup and Recovery

**Backup Strategy**: [3-2-1 rule / Continuous replication / Other]

**Backup Controls** (aligned with Essential Eight Regular Backups):
- [ ] Regular backups scheduled (RPO: [X hours])
- [ ] Backup encryption enabled
- [ ] Offsite/offline backups stored
- [ ] Backup restoration tested (RTO: [X hours])
- [ ] Backup integrity verified
- [ ] Immutable backups for ransomware protection
- [ ] Backups of important data, software, and configuration settings performed and retained per Essential Eight
- [ ] Backup access restricted to authorised personnel with break-glass procedures

**Recovery Time Objective (RTO)**: [X hours]
**Recovery Point Objective (RPO)**: [X hours]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 8.2 Incident Response

**Incident Response Plan**: [Documented / In Development / Not Started]

**Incident Response Team**: [24/7 / Business Hours / Ad-hoc]

**Incident Response Capabilities**:
- [ ] Incident response plan documented and tested
- [ ] Incident response team trained
- [ ] Incident detection capabilities
- [ ] Forensic investigation capabilities
- [ ] Communication plan for incidents
- [ ] Mandatory reporting to ACSC for significant cyber security incidents
- [ ] Reporting to OAIC for notifiable data breaches (Privacy Act 1988)
- [ ] Defence-specific incident reporting to Defence CISO
- [ ] Lessons learned process

**Recent Incident Response Exercise**: [Date / Not Conducted]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 8.3 Disaster Recovery and Business Continuity

**Disaster Recovery Plan**: [Documented / In Development / Not Started]

**Business Continuity Plan**: [Documented / In Development / Not Started]

**DR/BC Capabilities**:
- [ ] DR plan documented and tested
- [ ] Alternative processing site identified (compliant with Hosting Certification Framework)
- [ ] Critical system identification completed
- [ ] Failover procedures documented
- [ ] Regular DR testing conducted
- [ ] Business impact analysis (BIA) completed

**Last DR Test**: [Date / Not Conducted]
**DR Test Results**: [Successful / Issues identified]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 9. Personnel Security

### 9.1 Security Clearances

**Clearance Levels Required**:

| Role | Clearance Level | Current Clearance Status |
|------|-----------------|-------------------------|
| [System Administrator] | [NV1 / NV2 / PV] | [Active / Pending / Expired] |
| [Developer] | [NV1 / NV2 / PV] | [Active / Pending / Expired] |
| [End User] | [Baseline Vetting / NV1 / NV2] | [Active / Pending / Expired] |

**Australian Government Security Clearance Levels**:
- **Baseline Vetting** — Access to OFFICIAL and OFFICIAL: Sensitive information
- **Negative Vetting Level 1 (NV1)** — Access to PROTECTED information
- **Negative Vetting Level 2 (NV2)** — Access to SECRET information
- **Positive Vetting (PV)** — Access to TOP SECRET information

**Security Vetting Compliance**:
- [ ] All personnel appropriately vetted per AGSVA requirements
- [ ] Clearance levels match data classification per PSPF
- [ ] Clearance renewal process managed
- [ ] Foreign nationals risk assessed per DSPF obligations
- [ ] Contractor clearances verified (DISP membership confirmed for Defence industry personnel)
- [ ] Compliance with Crimes Act 1914 (Part VII) obligations

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 9.2 Security Awareness

**Security Training**:
- [ ] Mandatory security awareness training completed (per PSPF and DSPF)
- [ ] Role-based security training provided
- [ ] Phishing awareness training
- [ ] Insider threat awareness
- [ ] Data handling and classification training (PSPF markings)
- [ ] Annual security refresher training
- [ ] Defence-specific security awareness (DSPF obligations)

**Training Completion Rate**: [X%]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## 10. Compliance and Governance

### 10.1 Regulatory Compliance

**Applicable Regulations and Frameworks**:
- [ ] ISM (Information Security Manual) — ASD cybersecurity controls
- [ ] PSPF (Protective Security Policy Framework) — Whole-of-government security
- [ ] DSPF (Defence Security Principles Framework) — Defence security governance
- [ ] DISP (Defence Industry Security Program) — Industry security obligations
- [ ] Privacy Act 1988 and Australian Privacy Principles (APPs)
- [ ] Crimes Act 1914 (Part VII) — Protection of official information
- [ ] ASD Essential Eight — Prioritised mitigation strategies
- [ ] Hosting Certification Framework (HCF) — Cloud hosting classification
- [ ] IRAP (Information Security Registered Assessors Program) — Security assessment
- [ ] Digital Service Standard (DTA) — Digital service delivery

**Compliance Status**:

| Framework | Compliance Status | Last Assessment | Next Assessment |
|-----------|------------------|-----------------|-----------------|
| ISM | [Compliant / Partial / Non-Compliant] | [Date] | [Date] |
| PSPF | [Compliant / Partial / Non-Compliant] | [Date] | [Date] |
| DSPF | [Compliant / Partial / Non-Compliant] | [Date] | [Date] |
| DISP | [Compliant / Partial / N/A] | [Date] | [Date] |
| Essential Eight | [Level 0 / Level 1 / Level 2 / Level 3] | [Date] | [Date] |
| Privacy Act 1988 (APPs) | [Compliant / Partial / Non-Compliant] | [Date] | [Date] |
| Crimes Act 1914 (Part VII) | [Compliant / Partial / Non-Compliant] | [Date] | [Date] |
| IRAP Assessment | [Completed / In Progress / Not Started] | [Date] | [Date] |

**Gaps/Actions**:
- [Action 1]
- [Action 2]

### 10.2 Security Policies and Procedures

**Security Documentation**:
- [ ] Information Security Policy (aligned with ISM)
- [ ] Acceptable Use Policy
- [ ] Access Control Policy (aligned with ISM and Essential Eight)
- [ ] Incident Response Procedure (aligned with ACSC reporting requirements)
- [ ] Business Continuity Plan
- [ ] Disaster Recovery Plan
- [ ] Change Management Procedure
- [ ] Data Classification and Handling Guide (aligned with PSPF)
- [ ] System Security Plan (SSP)

**Documentation Review Frequency**: [Annual / Biennial]
**Last Documentation Review**: [Date]

**Gaps/Actions**:
- [Action 1]
- [Action 2]

---

## Overall Security Assessment Summary

### Security Scorecard

| Security Domain | Status | Critical Issues | Priority |
|-----------------|--------|-----------------|----------|
| Data Classification (PSPF) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Defence in Depth | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Secure by Default | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Least Privilege | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Assume Breach | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| ASD Certification | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| ISM Controls | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Essential Eight | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| DSPF Governance | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Threat Modeling | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Cryptography (ISM) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Authentication (E8 MFA) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Network Security | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Vulnerability Management | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Security Monitoring | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Secure Development | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Supply Chain / DISP | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Backup and Recovery (E8) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Incident Response | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Personnel Security (AGSVA) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |
| Compliance (PSPF/DSPF/ISM) | [Compliant/Partial/Non-Compliant] | [Yes/No] | [High/Med/Low] |

### Critical Security Issues Requiring Immediate Action

1. [Issue 1 with domain reference — must be resolved before ASD certification]
2. [Issue 2 with domain reference — blocks progression to next phase]
3. [Issue 3 with domain reference — unacceptable risk level]

### Recommendations

**Critical Priority** (0-30 days):
- [Recommendation 1]
- [Recommendation 2]

**High Priority** (1-3 months):
- [Recommendation 1]
- [Recommendation 2]

**Medium Priority** (3-6 months):
- [Recommendation 1]
- [Recommendation 2]

---

## Next Steps and Action Plan

**Immediate Actions** (0-30 days):
- [ ] [Action 1 - Owner - Due date]
- [ ] [Action 2 - Owner - Due date]

**Short-term Actions** (1-3 months):
- [ ] [Action 1 - Owner - Due date]
- [ ] [Action 2 - Owner - Due date]

**Long-term Actions** (3-12 months):
- [ ] [Action 1 - Owner - Due date]
- [ ] [Action 2 - Owner - Due date]

**Next Assessment Date**: [Date — recommend quarterly during development, annually in Live]

---

## Approval and Sign-Off

| Role | Name | Date | Signature |
|------|------|------|-----------|
| Project Lead | [Name] | | |
| Security Architect | [Name] | | |
| Authorising Officer | [Name] | | |
| Information Technology Security Adviser (ITSA) | [Name] | | |
| Chief Information Security Officer (CISO) | [Name] | | |
| IRAP Assessor (where applicable) | [Name] | | |

---

**Document Control**:
- **Version**: 1.0
- **Classification**: [OFFICIAL / OFFICIAL: Sensitive / PROTECTED]
- **Last Reviewed**: [Date]
- **Next Review**: [Date — recommend quarterly]
- **Document Owner**: [Name/Role]

## External References

| Document | Type | Source | Key Extractions | Path |
|----------|------|--------|-----------------|------|
| *None provided* | — | — | — | — |

## Reference Frameworks

| Framework | Full Name | Issuing Authority | Relevance |
|-----------|-----------|-------------------|-----------|
| ISM | Information Security Manual | Australian Signals Directorate (ASD) | Primary cybersecurity control framework |
| PSPF | Protective Security Policy Framework | Attorney-General's Department | Whole-of-government security policy |
| DSPF | Defence Security Principles Framework | Department of Defence | Defence-specific security governance |
| DISP | Defence Industry Security Program | Department of Defence | Industry security obligations |
| Essential Eight | Essential Eight Maturity Model | ASD/ACSC | Prioritised mitigation strategies |
| IRAP | Information Security Registered Assessors Program | ASD | Independent security assessment |
| HCF | Hosting Certification Framework | DTA | Cloud hosting classification |
| APPs | Australian Privacy Principles | OAIC | Privacy Act 1988 obligations |

---

**Generated by**: ArcKit `/arckit.mod-secure` command
**Generated on**: [DATE]
**ArcKit Version**: [VERSION]
**Project**: [PROJECT_NAME]
**Model**: [AI_MODEL]
