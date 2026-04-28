# GRC Compliance Skills · EMEA

Expert level compliance guidance for Cyber Essentials Plus, DORA, EU AI Act, TISAX, BSI C5, Spain ENS, and more. Built for UK and European GRC professionals and powered by Claude Skills.

![Release v1.1.0](https://img.shields.io/badge/Release-v1.1.0-brightgreen.svg)
![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)
![Skills 2 of 6](https://img.shields.io/badge/Skills-2%20of%206-green.svg)
![Built with Claude](https://img.shields.io/badge/Built%20with-Claude-orange.svg)
![Danzell Ready](https://img.shields.io/badge/Cyber%20Essentials-Danzell%20Ready-purple.svg)

---

## How It Works

Claude Skills are installable knowledge packages that extend Claude's capabilities for specific domains. A skill is a `.skill` file, a bundled archive containing a `SKILL.md` instruction file, that you upload to Claude once and use across all your conversations.

Once installed, a skill activates **automatically** when your conversation touches its topic area. You do not need to invoke it by name or use special commands. Claude simply becomes a deeper expert in that domain for the duration of your session.

**Skills are ideal when you need:**

- Consistent, expert level responses on a specialised topic
- Outputs formatted to professional or regulatory standards including audit ready control narratives, evidence checklists, and gap assessments
- Domain knowledge that goes beyond general AI training, such as knowing which specific CE+ control theme applies to a given scenario or which DORA article governs ICT third party risk

---

## Built For

These skills are built for professionals working in UK information security, privacy, and regulatory compliance. Whether at organisations seeking certification, security engineers building compliant systems, or GRC consultants supporting clients.

**Security and Compliance Teams** use these skills to accelerate gap assessments, generate first draft evidence checklists, map controls across frameworks, and prepare for certification. Compressing weeks of reference work into minutes.

**GRC Engineers and Analysts** use them to understand what controls their systems must implement, get NCSC cited answers to compliance questions, and produce audit ready documentation tied to specific requirements.

**Consultants and Advisors** use them to draft regulatory documents, answer client questions with precise citations, and stay current on framework changes like the Danzell update.

**Startups and SMBs** use these skills to understand what a given framework requires, scope their compliance programmes, and get expert quality output without a large in house team.

---

## The Problem We Are Solving

Most Claude Skills libraries focus on US frameworks like SOC 2, FedRAMP, and HIPAA. This library fills the gap for GRC professionals across EMEA, covering frameworks that matter to organisations operating across the UK, EU, and wider region:

- **Cyber Essentials / CE+** is the NCSC backed UK government certification scheme
- **DORA** is the EU Digital Operational Resilience Act for financial entities
- **EU AI Act** is the world's first comprehensive AI regulation
- **TISAX** is the automotive industry information security assessment standard used across the European automotive supply chain
- **BSI C5** is the German Federal Office for Information Security cloud compliance catalogue for providers serving regulated German markets
- **Spain ENS** (Esquema Nacional de Seguridad) is mandatory for public administrations in Spain and their technology suppliers

This is a living library. New skills will be added as frameworks evolve.

---

## The Toolkit

### 🛡️ Cyber Essentials Plus

**File:** `Cyber Essentials Plus - Claude Skill/cyber-essentials-plus.skill`

Turns Claude into an expert Cyber Essentials and Cyber Essentials Plus compliance advisor. Fully updated for **Danzell (v3.3)** effective 27 April 2026, replacing the previous Willow question set.

- Runs structured **gap assessments** across all 5 CE+ control themes with 🔴/🟡/🟢 RAG ratings
- Generates **audit evidence checklists** per control theme
- Drafts **remediation plans** with severity ratings, owners, and target dates
- Answers CE+ questions with **NCSC citations** and question number references
- Flags all **three automatic fail triggers** in Danzell: MFA on cloud services (A7.14 to A7.17), OS/firmware patching (A6.4), application patching (A6.5)
- Maps CE+ to ISO 27001:2022, NIST CSF 2.0, DORA, and the EU AI Act
- Covers the full Willow to Danzell transition including cloud service scoping, passwordless authentication guidance, and updated CE+ assessment process

**Trigger phrases:** `Cyber Essentials` `CE+` `Cyber Essentials Plus` `NCSC` `IASME` `Danzell` `Willow` `CE gap assessment` `CE+ audit readiness` `boundary firewall` `patch management` `MFA cloud services`

---

### 🏦 DORA

Turns Claude into an expert DORA compliance advisor for EU financial entities and ICT third party service providers. Covers all five pillars with Article citations, gap assessments, ICT risk management policy drafting, third party risk registers, and cross-framework mapping to NIST CSF 2.0, ISO 27001:2022, ISO 27005, ISO 22301, and NIS2.

**Trigger phrases:** `DORA` `Digital Operational Resilience Act` `ICT risk management` `ICT incident reporting` `TLPT` `Register of Information` `ICT third party risk` `critical ICT provider`

---

### 🤖 EU AI Act 

Full EU AI Act compliance advisor covering risk classification, conformity assessments, high risk AI obligations, and FRIA mapping.

---

### 🔗 TISAX

Expert TISAX compliance advisor for automotive suppliers and OEM service providers. Covers all three assessment levels, VDA ISA 6.0.3 controls, ENX registration, and cross-framework mapping to ISO 27001:2022 and NIS2.

**Trigger phrases:**        

---

### 🇩🇪 BSI C5 

German Federal Office for Information Security Cloud Computing Compliance Criteria Catalogue covering the 17 topic areas, basic and additional criteria, and audit requirements for cloud providers serving regulated German markets.

---

### 🇪🇸 Spain ENS

Expert Spain ENS compliance advisor covering Royal Decree 311/2022, all 73 security measures, three security categories, ENS certification process, and cross-framework mapping to ISO 27001:2022, NIST CSF 2.0, and NIS2.

**Trigger phrases:**        

---

## In Practice

| Scenario | Skill |
|---|---|
| Preparing for a CE+ assessment under the new Danzell question set | Cyber Essentials Plus |
| Running a gap assessment for a 50-person SaaS company seeking CE certification | Cyber Essentials Plus |
| Generating an evidence checklist before engaging a CE+ assessor | Cyber Essentials Plus |
| Checking whether your cloud services are in scope under Danzell | Cyber Essentials Plus |
| Drafting a remediation plan for CE+ findings | Cyber Essentials Plus |
| Mapping CE+ controls to ISO 27001:2022 Annex A | Cyber Essentials Plus |
| Answering a client question about MFA requirements under Danzell | Cyber Essentials Plus |
| Understanding how CE+ aligns to NIST CSF 2.0 | Cyber Essentials Plus |
| Running a DORA gap assessment for a financial entity | DORA |
| Drafting an ICT risk management policy aligned to DORA Article 6 | DORA |
| Generating a third party ICT risk register aligned to Article 28(3) | DORA |
| Mapping DORA obligations to ISO 27001:2022 and NIST CSF 2.0 | DORA |
| Answering a client question about major ICT incident reporting timelines | DORA |

---

## Get Started

1. Download the `.skill` file from the table below
2. Open Claude and go to **Customize then Skills**
3. Click **Upload Skill** and select the `.skill` file
4. Start a new conversation. Claude will automatically apply the skill when relevant topics come up

**Tip:** You can install multiple skills at once. Claude will activate whichever is most relevant to each question.

| Framework | Version | Download |
|---|---|---|
| 🛡️ Cyber Essentials Plus | v1.1.0 (Danzell) | [cyber-essentials-plus.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/Cyber%20Essentials%20Plus%20-Claude%20Skill/cyber-essentials-plus.skill) |
| 🏦 DORA | v1.0.0 | [dora.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/DORA%20-%20Claude%20Skill/dora.skill) |
| 🇩🇪 BSI C5 | v1.0.0 (C5:2026) | [bsi-c5.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/BSI%20C5%20-%20Claude%20Skill/bsi-c5.skill) |
| 🤖 EU AI Act | v1.0.0 | [eu-ai-act.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/EU%20AI%20Act%20-%20Claude%20Skill/eu-ai-act.skill) |
| 🔗 TISAX | v1.0.0 (ISA 6.0.3) | [tisax.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/TISAX%20-%20Claude%20Skill/tisax.skill) |
| 🇪🇸 Spain ENS | v1.0.0 (RD 311/2022) | [spain-ens.skill](https://github.com/FunkeOmolere/Claude-Skills-GRC-UK/raw/main/Spain%20ENS%20-%20Claude%20Skill/spain-ens.skill) |

---

## Danzell Update 27 April 2026

This library is updated for the **Danzell (v3.3)** scheme which comes into effect 27 April 2026. Key changes reflected in the CE+ skill:

- MFA on cloud services is now an **automatic fail** if not enabled where available
- 14 day patching for OS, firmware, and applications is now an **automatic fail** (questions A6.4 and A6.5)
- Cloud services are formally defined and explicitly in scope for the first time
- Social media accounts (LinkedIn, Facebook) are now classified as cloud services
- VSA must be finalised before CE+ testing begins. Answers cannot be changed after the fact.
- Passwordless authentication (passkeys, biometrics) now recognised as valid

---

## Who Built This

**Funke Omolere**
GRC Professional and Engineer | Adobe
BSides London 2025 Speaker | Most Inspiring Women in UK 2026

Building open source GRC tooling at the intersection of compliance, engineering, and AI.

[GitHub](https://github.com/FunkeOmolere) · [LinkedIn](https://www.linkedin.com/in/funkeomolere) · [Portfolio](https://funkeomolere.github.io)

---

## Feedback 🌱

Found this useful? Spotted something off? I'd love to hear from you.

- ⭐ **Star the repo** if it saved you time
- 🐛 **Open an issue** if something's unclear, broken, or out of date — include the skill name, the issue, and a source reference if you have one
- 💡 **Suggest a framework** by opening an issue with the tag `skill-request`
- 💬 **DM me on LinkedIn** if you want to share how you're using these

Building this in public and learning as I go. All feedback welcome.

---

## Disclaimer

The skills in this repository provide informational guidance based on publicly available regulatory and standards documentation. They do not constitute legal, audit, or professional compliance advice. Outputs should be reviewed by a qualified professional such as an IASME accredited CE+ assessor before being relied upon for formal certification purposes.

Requirements evolve. Always verify against the latest official publications from the NCSC at ncsc.gov.uk and IASME at iasme.co.uk.

---

*Licensed under the [MIT License](LICENSE) · Built by [Funke Omolere](https://github.com/FunkeOmolere)*
