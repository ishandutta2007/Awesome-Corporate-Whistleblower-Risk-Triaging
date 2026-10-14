# Awesome-Corporate-Whistleblower-Risk-Triaging

# Top Corporate Whistleblower & Risk Triaging Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Anonymized Intake, Case Triage & Policy Breach Cataloging*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Corporate Whistleblower & Risk Triaging**. These tools enable ethics and compliance teams to receive anonymous reports, triage by severity and jurisdiction, catalog policy breaches, and manage investigations end-to-end—while protecting reporter anonymity and meeting regulatory deadlines.

**Examples** include Navex Global (EthicsPoint), Whispli, FaceUp, SpeakUp, EQS Integrity Line, Convercent, AllVoices, Canary, EthicsGlobal, and WhistleB (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Tor-based anonymity, and open case management—ideal for ethics teams, compliance officers, and developers seeking transparent, vendor-independent whistleblowing infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Navex Global (EthicsPoint)](https://www.navex.com/)**  
  Market-leading ethics and compliance platform with anonymous hotline, web intake, and case management. Features customizable intake forms, automated routing, investigation workflows, and analytics for misconduct trends.

- **[EQS Integrity Line (BKMS System)](https://www.eqs.com/)**  
  Secure reporting platform compliant with the Whistleblower Protection Act . Features alerts/notifications, document management, compliance tools, task management, audit trails, and configurable workflows. GDPR-certified for European operations. **Limitation**: Web-only—does not support mobile apps .

- **[FaceUp](https://www.faceup.com/)**  
  Secure whistleblowing and case management platform with web, mobile app, and hotline channels . **Microsoft Teams integration** delivers real-time notifications for new reports and case updates, enabling compliance and HR teams to collaborate directly within Teams .

- **[Resolver](https://www.resolver.com/)**  
  Whistleblower & case management software automating workflows and ensuring secure confidential reporting . Features dynamic intake forms, secure two-way communication, automated case routing by type/severity/jurisdiction, centralized investigation workspace, and cross-functional integration across HR, Risk, Security, and Investigations . Real-time dashboards surface trends for proactive misconduct prevention .

- **[Safecall](https://www.safecall.co.uk/)**  
  All-in-one whistleblowing software developed with client collaboration . Features custom intake forms, automated alerts, and an **Investigations Management Module** for assigning investigators, tracking progress, and remediation analysis. Combines technology with human empathy—independent investigations team available when needed. Royal Mail case study: 130,000+ employees, high-volume reports, robust platform with needed metrics .

- **[OASIS Notify](https://www.oasisgroup.com/)**  
  Purpose-built confidential and anonymous reporting platform with **end-to-end encryption** and **metadata removal**—even the technical team cannot identify anonymous submitters . Features anonymous tracking via unique access codes, two-way communication, dashboard analytics, and ISO 27001 certification. Trusted by police forces, NHS trusts, and government bodies .

- **[Whispli](https://www.whispli.com/)**  
  Whistleblowing and case management platform with anonymous reporting and secure investigation workflows.

- **[SpeakUp](https://speakup.com/)**  
  Whistleblowing platform for ethical reporting and compliance management.

- **[Convercent](https://convercent.com/)**  
  Ethics and compliance platform with whistleblowing intake and case management.

- **[AllVoices](https://www.allvoices.co/)**  
  Employee reporting platform for misconduct, discrimination, and ethics concerns with anonymous intake.

## Open-Source GitHub Projects

- **[GlobaLeaks](https://github.com/globaleaks/GlobaLeaks)**  
  **The leading open-source whistleblowing framework** (AGPL-3.0), recognized as a Digital Public Good by the Digital Public Goods Alliance . Launched in 2011, used by **30,000+ organizations worldwide** including Italy's National Anti-Corruption Authority (ANAC), Barcelona City Council, and government of Mexico . **Designed for ISO 37002:2021, EU Directive 2019/1937, GDPR, and ISO 27001:2022 compliance** . Features: multi-user system with customizable roles (whistleblower, recipient, administrator), **Tor integration for digital anonymity**, full data encryption (TLS 1.3), **no IP address logging**, unique 16-digit receipt for anonymous login, **bidirectional anonymous communication**, advanced questionnaire builder, **customizable case management workflow** (statuses/sub-statuses), **conflict of interest management**, **Custodian functionality** for authorizing access to whistleblower identity, **GDPR configurable retention policies**, audit log, and **70+ languages with RTL support** . Security reviews by iSecPartners, Cure53, LeastAuthority, Subgraph, Radically Open Security, and ISGroup—all reports published publicly . Deployable on web, Windows, macOS, Linux, iOS, and Android . **The most mature and widely deployed open-source whistleblowing platform available.**

- **[OpenWhistle](https://openwhistle.pt/)**  
  Open-source whistleblowing channel platform (AGPL-3.0) designed for ISO 37002:2021 and EU Directive 2019/1937 compliance . Features: **multi-tenant support** (multiple reporting sites for subsidiaries or third-party clients), **advanced questionnaire builder**, **customizable appearance** (logo, color, styles, font, text), **90+ languages with RTL support**, **case management with statuses/sub-statuses**, **custodian functionality** for identity authorization, **conflict of interest management**, **GDPR by design and by default**, **no IP address logging**, **audit log**, **2FA (TOTP RFC 6238)**, **Tor integration**, **TLS 1.3 with SSLabs A+**, **AppArmor sandboxing**, and **PGP support for email notifications** . **Process**: submission → registration with unique ID and timestamp → triage → anonymized summary to designated handler → investigation → deadline monitoring with alerts → secure archival with 5-year minimum retention . Designed for compliance with Portuguese Law 93/2021 and GDPR .

- **[OpenWhistle (npm library)](https://www.npmjs.com/package/openwhistle)**  
  Small library for collecting anonymous whistleblower submissions (MIT) . **Bring your own storage backend**—SQLite or Supabase adapters included, custom adapters via `WhistleAdapter` interface . **IP addresses SHA256-hashed with your salt before storage—raw IP never saved** . Minimal API: `submit()` and `list()`. **The most lightweight building block for custom whistleblowing intake.**

- **[Trusty Whistleblowing Solution](https://wordpress.org/plugins/trusty-whistleblowing-solution/)**  
  WordPress plugin connecting to Trusty's paid whistleblowing service hosted in Germany (ISO 27001 certified) . Features customizable front-end reporting pages, **secure inbox for two-way communication**, case management with status tracking, notes, file attachments, retention settings, follow-up activities, workflows, and reporting insights. Supports **anonymity or identified reporting** based on configuration. **NIS2 Directive cybersecurity vulnerability reporting** available on Advanced plan . Lite/Standard/Advanced plans with free 7-day trial. Case management tool available in 25+ languages .

- **[SAI360 Hotline & Case Management](https://www.strategicbcp.com/)**  
  Part of SAI360 GRC Platform—hotline and incident case management with **anonymous, multilingual reporting** via phone, web, mobile, and walk-up channels . Features **mobile-first intake forms** tailored by issue type and risk category, **automated routing** based on issue type/severity/business unit with role-based permissions, **secure audit trails**, **trend analysis dashboards**, and integration with HR systems and hotline providers . Links investigation outcomes to corrective actions, policies, and risk mitigation.

- **[PeopleForce Safe Speak](https://help.peopleforce.io/)**  
  Anonymous reporting (whistleblowing) feature within PeopleForce HR platform . Features **ticketing-style complaint list**, status tracking (New/In progress/On hold/Closed), **category assignment with default assignee**, priority and reassignment capabilities, **two-way communication** with reporter, and **audit log**—if an admin deletes a complaint, the submitter can track who deleted it and when . Access restricted to designated complaint managers .

### Additional Strong Open-Source Options

- **[Deloitte Conduct Watch](https://www2.deloitte.com/)** — Enterprise whistleblowing platform with structured case management, digital dashboards, and multiple reporting channels . **Note**: Gartner reviewers cite limited customization, slow loading, and potential data breach concerns .
- **[WhistleB](https://www.whistleb.com/)** — Whistleblowing and case management platform with GDPR compliance and anonymous reporting.
- Community **n8n** workflows for whistleblower report routing and compliance alerting.

**Frameworks for building custom systems**: Combine **GlobaLeaks** for Tor-integrated anonymous reporting with **OpenWhistle** for multi-tenant case management, **Trusty** for WordPress integration, and **SAI360** patterns for GRC platform integration—creating a fully self-hosted, enterprise-grade whistleblowing platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Whistleblowing systems handling misconduct reports must comply with whistleblower protection laws (EU Directive 2019/1937, national implementations), data protection regulations (GDPR, CCPA), and employment law.
- **Open-source whistleblowing is mature and production-ready.** GlobaLeaks is recognized as a Digital Public Good and used by 30,000+ organizations including national anti-corruption authorities . OpenWhistle provides ISO 37002 and GDPR compliance with Tor integration .
- **Anonymity must be enforced at the infrastructure level.** GlobaLeaks does not log IP addresses and supports Tor integration . OpenWhistle explicitly avoids metadata collection . The openwhistle npm library hashes IPs with a salt—raw IPs are never stored . **A system that logs IPs "for security" is not anonymous.**
- **Two-way communication is the standard.** Modern whistleblowing programs require follow-up mechanisms—employees who receive no feedback lose trust and may report externally or publicly . GlobaLeaks, OpenWhistle, Trusty, and SAI360 all support anonymous two-way dialogue .
- **Case management is not just intake.** Triage by severity, jurisdiction, and issue type; conflict of interest management; deadline tracking; and audit trails are essential for defensible investigations .
- Self-hosted open-source solutions require proper security hardening, Tor configuration where required, and ongoing maintenance. Whistleblower data is highly sensitive—access controls, encryption, and audit trails are non-negotiable.

---

**Made for ethics officers, compliance managers, HR professionals, and developers building transparent whistleblowing solutions.**  
Let's make Corporate Whistleblower & Risk Triaging more open, data-driven, and reporter-protective.
