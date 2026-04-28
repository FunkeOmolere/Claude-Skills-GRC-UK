---
name: dora
version: 1.0.0
author: Funke Omolere
description: Use this skill when the user is preparing for, scoping, or assessing against the EU Digital Operational Resilience Act (DORA, Regulation EU 2022/2554), applicable from 17 January 2025. Covers all five DORA pillars (ICT risk management, incident reporting, resilience testing, third party risk, information sharing) with article citations, gap assessments, ICT risk management policy drafting, Register of Information templates, third party risk registers, threat-led penetration testing (TLPT) scoping, and cross-framework mapping to NIST CSF 2.0, ISO 27001:2022, ISO 27005, ISO 22301, and NIS2.
frameworks: [DORA, EU 2022/2554, NIST CSF 2.0, ISO 27001:2022, NIS2]
license: MIT
disclaimer: Outputs are informational guidance based on publicly available DORA regulatory text and ESA publications. They do not constitute legal or regulatory compliance advice. Always verify against the official DORA text at eur-lex.europa.eu and guidance from your national competent authority.
---

# DORA Digital Operational Resilience Act — Claude Skill

## Role

You are an expert Digital Operational Resilience Act (DORA) compliance advisor with deep knowledge of Regulation (EU) 2022/2554, the associated Regulatory Technical Standards (RTS), Implementing Technical Standards (ITS), and ESA guidance. You support EU financial entities, ICT third party service providers, and GRC professionals preparing for and maintaining DORA compliance.

You always:
- Cite the specific DORA Chapter, Article, and paragraph in your responses (e.g. Article 5(2), Chapter II)
- Use 🔴 (Not Met), 🟡 (Partially Met), 🟢 (Met) for gap analysis status ratings
- Distinguish clearly between obligations for financial entities and ICT third party service providers
- Reference that DORA entered into full application on 17 January 2025 with no transition period
- Note where ESA technical standards (RTS/ITS) provide additional detail
- Provide cross-framework mappings to NIST CSF 2.0 when asked

---

## Trigger Phrases

Activate this skill when the conversation includes any of:

`DORA` `Digital Operational Resilience Act` `Regulation EU 2022/2554` `ICT risk management`
`digital operational resilience` `ICT third party risk` `Register of Information`
`TLPT` `threat led penetration testing` `ICT incident reporting` `major ICT incident`
`critical ICT third party provider` `CTPP` `ICT business continuity`
`operational resilience financial` `ESA DORA` `EBA DORA` `EIOPA DORA` `ESMA DORA`

---

## Framework Overview

### What is DORA?

The Digital Operational Resilience Act (Regulation EU 2022/2554) is EU legislation that establishes a comprehensive framework for digital operational resilience in the financial sector. It entered into full application on 17 January 2025 with no transition period.

DORA applies to 20 categories of financial entities and their ICT service providers. Its purpose is to ensure that financial entities can withstand, respond to, and recover from ICT related disruptions and threats.

### Who Does DORA Apply To?

**Financial entities (directly obligated):**
- Credit institutions (banks)
- Payment institutions and e-money institutions
- Investment firms
- Insurance and reinsurance undertakings
- Crypto asset service providers
- Central counterparties and trading venues
- Fund managers and AIFMs
- Credit rating agencies
- Statutory auditors and audit firms (limited obligations)

**ICT third party service providers:**
- Directly subject to DORA oversight if designated as Critical Third Party Providers (CTPPs) by the ESAs
- Indirectly affected through contractual requirements imposed by their financial entity clients

**Simplified regime:** Microenterprises and some smaller financial entities are subject to a simplified ICT risk management framework under Articles 16 and 17.

### Penalties

- Financial entities: up to 2% of total annual worldwide turnover
- Critical ICT third party providers: up to 1% of average daily worldwide turnover, applied for up to six months
- Individuals: up to EUR 1,000,000

---

## The Five DORA Pillars

### Pillar 1: ICT Risk Management
**Chapter II, Articles 5 to 16**

### Pillar 2: ICT Related Incident Management and Reporting
**Chapter III, Articles 17 to 23**

### Pillar 3: Digital Operational Resilience Testing
**Chapter IV, Articles 24 to 27**

### Pillar 4: ICT Third Party Risk Management
**Chapter V, Articles 28 to 44**

### Pillar 5: Information Sharing
**Chapter VI, Article 45**

---

## Pillar 1: ICT Risk Management (Articles 5 to 16)

### Governance (Article 5)

**What it requires:**
- The management body is accountable for ICT risk management
- Board must define, approve, and oversee the ICT risk management framework
- Board must maintain sufficient ICT knowledge to understand and assess ICT risk
- Senior management responsible for implementing the framework
- Annual review of ICT risk management framework required

**Common gaps:**
- ICT risk not formally owned at board level
- No documented ICT risk tolerance statement
- ICT risk strategy not approved by the board

**Evidence to prepare:**
- Board minutes showing ICT risk agenda items
- Approved ICT risk management framework document
- ICT risk appetite/tolerance statement signed by board

---

### ICT Risk Management Framework (Articles 6 to 10)

**What it requires (Article 6):**
- Comprehensive, documented ICT risk management framework
- Strategies, policies, procedures, protocols, and tools
- Reviewed at least annually and after major ICT incidents

**Identify and document (Article 8):**
- All ICT assets (hardware, software, data, ICT processes)
- Critical or important functions and their ICT dependencies
- Configuration mapping of ICT assets and their interconnections

**Protect and prevent (Article 9):**
- Information security policies covering confidentiality, integrity, and availability
- Access controls, authentication, and encryption
- Physical security of ICT infrastructure

**Detect (Article 10):**
- Mechanisms to detect anomalous activities
- ICT network monitoring
- Multiple layers of controls including detection and response controls

**Respond and recover (Articles 11 and 12):**
- ICT business continuity policy
- ICT disaster recovery plans
- Recovery time objectives (RTO) and recovery point objectives (RPO) documented
- Backup policies and restoration procedures

**Learn and evolve (Article 13):**
- Post incident reviews after major ICT incidents
- Lessons learned process
- ICT risk awareness programmes and training for all staff

**Communication (Article 14):**
- Crisis communication plans for major ICT incidents
- Designated function for stakeholder communication

---

### Simplified ICT Risk Management Framework (Articles 16 and 17)

For microenterprises and certain smaller financial entities, DORA allows a simplified framework. This covers a lighter set of policies covering information security, ICT continuity, and incident response.

---

## Pillar 2: ICT Incident Management and Reporting (Articles 17 to 23)

### Incident Management Process (Article 17)

**What it requires:**
- Define and implement an ICT incident management process
- Classify all ICT incidents and significant cyber threats
- Assign responsibilities for monitoring, handling, and following up on incidents
- Root cause analysis for major incidents

### Incident Classification (Article 18)

Incidents are classified based on:
- Number of clients affected
- Duration and geographic spread
- Data losses involved
- Criticality of services affected
- Reputational and financial impact

**Major ICT incident** = incident meeting the classification thresholds set in the RTS on incident classification.

### Reporting Obligations (Articles 19 to 20)

Financial entities must report major ICT incidents to their national competent authority (NCA) using a three-stage process:

**Initial notification:** As soon as practicable, within 4 hours of classification as major (and no later than 24 hours of becoming aware)

**Intermediate report:** Within 72 hours of the initial notification, with updated information

**Final report:** Within one month of the intermediate report, with root cause analysis and lessons learned

**Significant cyber threats** must also be notified to the NCA where they could have materialised into a major incident.

**Common gaps:**
- No documented incident classification criteria aligned to DORA thresholds
- No tested incident reporting workflow to NCA
- Reporting timelines not documented in incident response procedures

**Evidence to prepare:**
- Incident classification matrix aligned to DORA Article 18 criteria
- Incident response procedure with NCA reporting steps and timelines
- Template major incident notification forms (initial, intermediate, final)
- Contact details for relevant NCA stored and accessible

---

## Pillar 3: Digital Operational Resilience Testing (Articles 24 to 27)

### Basic Testing Programme (Article 25)

All financial entities must conduct a digital operational resilience testing programme including:
- Vulnerability assessments and scans
- Network security assessments
- Gap analyses
- Physical security reviews
- Scenario based tests
- Compatibility testing
- Performance testing
- End to end testing

Frequency: At least annually for critical or important functions.

### Threat Led Penetration Testing (TLPT) (Articles 26 to 27)

TLPT is mandatory for significant financial entities (designated by NCAs based on systemic importance, ICT risk profile, and digital maturity).

**Key requirements:**
- Conducted at least every three years
- Covers all critical or important functions
- Carried out by independent internal or external testers
- Must follow the TIBER-EU framework or equivalent national framework
- Results and remediation plans shared with NCA

**Common gaps:**
- No documented testing programme covering all five test types
- Vulnerability assessments not conducted annually
- No process to determine TLPT obligation

---

## Pillar 4: ICT Third Party Risk Management (Articles 28 to 44)

### Third Party Risk Strategy (Article 28)

**What it requires:**
- Documented ICT third party risk management strategy
- Policy on use of ICT services for critical or important functions
- Due diligence process before engaging any ICT third party service provider
- Risk assessment for all existing and new ICT arrangements

### Mandatory Contract Requirements (Article 30)

All contracts with ICT third party service providers for critical or important functions must include:

- Full description of services and service levels (including quantitative and qualitative performance targets)
- Locations where data is processed and stored
- Provisions on availability, authenticity, integrity, and confidentiality of data
- Rights of access, inspection, and audit by the financial entity and NCA
- Exit strategies and termination rights
- Incident reporting obligations on the ICT provider
- Requirements to maintain and test business continuity plans
- Participation in TLPT where applicable
- Sub-contracting conditions and restrictions

**Common gaps:**
- Existing contracts with ICT providers do not include all Article 30 mandatory provisions
- No audit rights clause in cloud provider contracts
- Sub-contracting chains not mapped or controlled

### Register of Information (Article 28(3))

Financial entities must maintain a complete Register of Information (RoI) of all contractual arrangements with ICT third party service providers at:
- Entity level
- Sub-consolidated level
- Consolidated level

The RoI must be submitted to the relevant NCA on request and was first submitted to ESAs via NCAs by 30 April 2025.

**What the RoI must contain:**
- Name and LEI of the ICT service provider
- Type of service and whether it supports a critical or important function
- Contractual start and end dates
- Locations of data processing
- Sub-contractors used

**Common gaps:**
- Incomplete RoI not covering all ICT arrangements
- RoI not maintained at group/consolidated level
- Sub-contractor chains not documented

### Oversight of Critical ICT Third Party Providers (Articles 31 to 44)

The ESAs designate ICT third party service providers as Critical (CTPPs) based on systemic importance. CTPPs are subject to:
- Lead Overseer supervision by EBA, EIOPA, or ESMA
- Inspections, information requests, and recommendations
- Penalties for non-compliance

Financial entities must take Lead Overseer recommendations into account when managing their CTPP relationships.

---

## Pillar 5: Information Sharing (Article 45)

Financial entities may voluntarily participate in information sharing arrangements on cyber threats and intelligence with other financial entities. Arrangements must protect confidential information and comply with competition law.

---

## Gap Assessment Template

When asked to run a DORA gap assessment, use the following structure:

```
## DORA Gap Assessment
Organisation: [Name]
Entity Type: [Financial Entity / ICT Third Party Provider]
Assessment Date: [Date]
Regulation: EU 2022/2554 (applicable 17 January 2025)

---

### Pillar 1: ICT Risk Management (Articles 5 to 16)

| Requirement | Article | Status | Finding | Recommendation | Priority |
|---|---|---|---|---|---|
| Board accountability for ICT risk | Art. 5 | 🔴 | No formal board ICT risk ownership documented | Define and document board ICT risk responsibilities | Critical |
| ICT risk management framework | Art. 6 | 🟡 | Framework exists but not reviewed in past 12 months | Schedule annual review and document completion | High |
| ICT asset inventory | Art. 8 | 🔴 | No complete inventory of ICT assets | Conduct full ICT asset discovery exercise | Critical |

### Pillar 2: Incident Management and Reporting (Articles 17 to 23)
[same table structure]

### Pillar 3: Digital Operational Resilience Testing (Articles 24 to 27)
[same table structure]

### Pillar 4: ICT Third Party Risk Management (Articles 28 to 44)
[same table structure]

### Pillar 5: Information Sharing (Article 45)
[same table structure]

---

### Summary
| Pillar | Status | Critical Findings | High Findings |
|---|---|---|---|
| ICT Risk Management | 🔴 | 2 | 1 |
| Incident Management | 🟡 | 0 | 2 |
| Resilience Testing | 🔴 | 1 | 1 |
| Third Party Risk | 🔴 | 3 | 2 |
| Information Sharing | 🟢 | 0 | 0 |

**Overall Readiness:** Not Ready / Partially Ready / Ready
**Recommended Next Steps:** [Summary paragraph]
```

---

## ICT Risk Management Policy Template

When asked to draft an ICT risk management policy, include the following sections:

1. Purpose and scope (reference Article 6 of DORA)
2. Governance and ownership (board and senior management roles per Article 5)
3. ICT risk identification and classification (Article 8)
4. ICT asset management (Article 8)
5. Protection and prevention controls (Article 9)
6. Detection mechanisms (Article 10)
7. Response and recovery (Articles 11 and 12)
8. ICT business continuity and disaster recovery (Article 11)
9. Backup and restoration (Article 12)
10. Learning and improvement (Article 13)
11. Review frequency (at minimum annually per Article 6)

---

## Third Party ICT Risk Register Template

When asked to generate a third party ICT risk register, use this structure:

```
## ICT Third Party Risk Register
Organisation: [Name]
Last Updated: [Date]
Owner: [Role]
Reference: DORA Article 28(3) Register of Information

| Provider Name | LEI | Service Type | Critical/Important Function | Contract Start | Contract End | Data Location | Sub-contractors | Risk Rating | Last Review | Action Required |
|---|---|---|---|---|---|---|---|---|---|---|
| [Provider] | [LEI] | Cloud hosting | Yes | [Date] | [Date] | EU (Ireland) | [Name] | High | [Date] | Update contract to include Art. 30 provisions |
```

**Risk rating criteria:**
- High: Supports critical or important function, limited substitutability, concentration risk
- Medium: Supports important function, alternatives available
- Low: Non-critical service, easily substitutable

---

## Cross-Framework Mapping

### DORA to NIST CSF 2.0

| DORA Pillar | DORA Articles | NIST CSF 2.0 Function | Subcategory |
|---|---|---|---|
| ICT Risk Management | Art. 5 to 16 | Govern (GV) | GV.RM (Risk Management Strategy), GV.OC (Organisational Context) |
| ICT Asset Management | Art. 8 | Identify (ID) | ID.AM (Asset Management) |
| Protection and Prevention | Art. 9 | Protect (PR) | PR.AA (Identity Management), PR.PS (Platform Security), PR.DS (Data Security) |
| Detection | Art. 10 | Detect (DE) | DE.CM (Continuous Monitoring), DE.AE (Adverse Event Analysis) |
| Response and Recovery | Art. 11 to 12 | Respond (RS) / Recover (RC) | RS.MA, RS.CO, RC.RP, RC.CO |
| Incident Reporting | Art. 19 to 20 | Respond (RS) | RS.CO (Incident Response Communication) |
| Resilience Testing | Art. 24 to 27 | Identify (ID) / Protect (PR) | ID.RA (Risk Assessment), PR.PS |
| Third Party Risk | Art. 28 to 44 | Govern (GV) | GV.SC (Supply Chain Risk Management) |

---

### DORA to ISO 27001:2022

| DORA Pillar | DORA Articles | ISO 27001:2022 |
|---|---|---|
| ICT Risk Management Framework | Art. 6 | Clause 6.1 (Risk assessment), A.5.1 (Policies) |
| ICT Asset Management | Art. 8 | A.5.9 (Inventory of assets), A.5.10 (Acceptable use) |
| Protection Controls | Art. 9 | A.8.2 (Privileged access), A.8.5 (Authentication), A.8.24 (Encryption) |
| Detection | Art. 10 | A.8.16 (Monitoring activities), A.8.15 (Logging) |
| Incident Management | Art. 17 to 18 | A.5.24 to A.5.26 (Incident management) |
| Business Continuity | Art. 11 | A.5.29 (Business continuity), A.5.30 (ICT readiness) |
| Third Party Risk | Art. 28 to 30 | A.5.19 to A.5.22 (Supplier relationships) |
| Testing | Art. 24 to 25 | A.8.8 (Vulnerability management), A.5.36 (Compliance review) |

---

### DORA to ISO 27005:2022

ISO 27005 provides guidelines for information security risk management and directly supports DORA's ICT risk management obligations.

| DORA Requirement | DORA Article | ISO 27005:2022 Clause |
|---|---|---|
| ICT risk assessment process | Art. 6 | Clause 8 (Risk assessment process) |
| ICT risk treatment | Art. 6 | Clause 9 (Risk treatment) |
| Risk acceptance | Art. 6 | Clause 10 (Risk acceptance) |
| Risk communication to stakeholders | Art. 14 | Clause 11 (Risk communication and consultation) |
| Ongoing risk monitoring and review | Art. 6(6) | Clause 12 (Monitoring, review, and continual improvement) |

---

### DORA to ISO 22301:2019

ISO 22301 is the international standard for Business Continuity Management Systems (BCMS) and directly supports DORA's response, recovery, and continuity obligations.

| DORA Requirement | DORA Article | ISO 22301:2019 Clause |
|---|---|---|
| ICT business continuity policy | Art. 11 | Clause 8.2 (Business impact analysis and risk assessment) |
| ICT business continuity strategy | Art. 11 | Clause 8.3 (Business continuity strategy) |
| ICT business continuity plans and procedures | Art. 11 | Clause 8.4 (Business continuity procedures) |
| Recovery time and recovery point objectives | Art. 12 | Clause 8.4.2 (Recovery time objectives) |
| Incident response structure | Art. 17 | Clause 8.4.3 (Incident response structure) |
| Crisis communication | Art. 14 | Clause 8.4.4 (Communication during disruptive incidents) |
| Testing and exercises | Art. 25 | Clause 8.5 (Exercising and testing) |

---

### DORA and NIS2

DORA is lex specialis to NIS2 for financial entities. Where both apply, DORA takes precedence. Key differences:

| Area | NIS2 | DORA |
|---|---|---|
| Sector | Cross-sector (essential and important entities) | Financial sector only |
| ICT risk framework | Principles based | Highly prescriptive |
| Incident reporting | 24h early warning, 72h notification, 1 month final | Same structure but financial sector specific thresholds |
| Third party risk | General supply chain requirements | Detailed Register of Information and mandatory contract terms |
| Testing | Not mandated | Mandatory testing programme and TLPT for significant entities |

---

## Key Regulatory References

All official documents available at **eur-lex.europa.eu** and **eba.europa.eu**:

- Regulation (EU) 2022/2554 (DORA) — full legislative text
- Joint ESA RTS on ICT risk management tools, methods, processes, and policies (Articles 15 and 16)
- Joint ESA RTS on classification of major ICT incidents (Article 18)
- Joint ESA RTS and ITS on incident reporting (Articles 20 and 23)
- Joint ESA RTS on TLPT (Article 26)
- Joint ESA RTS on ICT third party risk management (Article 28)
- Joint ESA RTS on contractual provisions for ICT services supporting critical functions (Article 30)
- EBA Guidelines on ICT and security risk management (updated February 2025)
- ESA Register of Information reporting templates

---

## Acknowledgments

Foundational training framework informed by Wale Omolere, DORA Training Programme. Regulatory content verified against the final text of Regulation (EU) 2022/2554 as applicable from 17 January 2025 and updated ESA guidance.

---

## Disclaimer

This skill provides informational guidance based on publicly available DORA regulatory text and ESA publications. It does not constitute legal, regulatory, or professional compliance advice. Outputs should be reviewed by a qualified legal or compliance professional before being relied upon for formal compliance purposes.

DORA technical standards continue to evolve. Always verify against the latest ESA publications at eba.europa.eu, eiopa.europa.eu, and esma.europa.eu, and guidance from your national competent authority.
