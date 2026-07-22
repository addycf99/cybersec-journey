# Cybersecurity — Core Definition

The practice of ensuring:
- 🔒 **Confidentiality**
- ✅ **Integrity**  
- 🟢 **Availability**

...of information, by protecting **networks**, **devices**, **people**, and **data** from unauthorized access or criminal exploitation.


## Threat Actor — Core Definition
A person or group who presents a **security risk**.
- Internal Threat: current/former employees, external vendors, trusted partners.
- External Threat: gain access to private info, networks or devices by external entity or someone

## Security posture
- An organisations ability to manage its defense of critical assets and data, and react to change.

## Why Cybersecurity Matters

- 🛡️ Protects against threats
- 📋 Meets regulatory compliance
- 📈 Maintains and improves business productivity (ex. BCP)
- 💸 Reduces expense (ex. recovery, etc.)
- 🤝 Maintains brand trust


# Security Analyst 
**Security analysts are responsible for monitoring and protecting information and systems.**
## Responsibities
- 🛡️ **Protecting computer and network systems** — monitoring internal networks, first responder to threats, conducting pen testing/ethical hacking
- 💻 **Installing prevention software** — collaborating with IT teams to identify risks/vulnerabilities before exploitation
- 📝 **Conducting periodic security audits** — reviewing internal security records and activities for compliance

## Transferable Skills
**Soft skills that support technical work as a security analyst.**
- 🗣️ **Communication** — explaining threats/risks to technical & non-technical audiences
- 🤝 **Collaboration** — working with engineers, forensic investigators, project managers
- 🔍 **Analysis** — breaking down complex scenarios
- 🧩 **Problem solving** — diagnosing and solving security issues

## Technical Skills 
**Hands-on technical abilities needed to identify, analyze, and solve security problems.**
- 💻 **Programming Languages** — basic understanding of Python and SQL for automating tasks and identifying error messages
- 📊 **SIEM Tools** — proficiency in Security Information and Event Management tools for identifying/analyzing threats, risks, and vulnerabilities
- 🔬 **Computer Forensics** — identifying, analyzing, and preserving evidence within networks, computers, and electronic devices

# Digital Forensics — Core Definition
**The practice of collecting and preserving evidence from computers, networks, and devices in a way that's legally admissible.**
- 🔍 **Purpose** — identify, analyze, and preserve digital evidence related to a security incident or crime
- ⚖️ **Chain of custody** — documenting who accessed evidence, when, and how, so it holds up in court
- 💾 **Sources** — hard drives, mobile devices, logs, emails, cloud storage
- 🚫 **Key rule** — never alter the original data; work from copies/images

# PII vs SPII — Core Definitions
**PII (Personally Identifiable Information)**: Any info that can be used to identify a specific individual.
- 🪪 Examples: full name, address, phone number, email, date of birth
**SPII (Sensitive Personally Identifiable Information)**: A specific type of PII that falls under stricter handling rules because exposure could cause serious harm.
- 🔒 Examples: **SSN**, bank account/credit card numbers, medical records, biometric data (fingerprints, facial recognition), passwords
- ⚠️ **Key difference** — SPII requires extra layers of protection (encryption, restricted access) since a breach can lead to identity theft or financial/medical harm

# SIEM (Security Information and Event Management) — Core Definition
**A tool that collects and analyzes log data from across an organization's technology infrastructure to detect, monitor, and respond to security threats in real time.**

- 📡 **Collects** — aggregates logs from networks, servers, devices, and applications into one place
- 🔎 **Analyzes** — flags unusual patterns or anomalies that could indicate a threat
- 🚨 **Alerts** — notifies security analysts in real time so they can investigate and respond quickly
- 🧰 **Examples** — Splunk, Chronicle (Google), IBM QRadar

---

## Computer Virus — Core Definition
**Malicious code written to interfere with computer operations and cause damage to data & software.**

## Malware — Core Definition
**Software designed to harm devices & software.**

### 🕰️ 1986 — Brain Virus (Alvi Brothers)

- 👥 **Created by**: Alvi brothers
- 🎯 **Initial intent**: track illegal copies of medical software and prevent pirated licenses
- ⚠️ **Unexpected turn**: one person used a pirated copy of the software → the virus infected that computer → any disk inserted into that computer also got infected *(OMG!! Pandemic. But digital.)*

### 🕰️ 1988 — Morris Worm (Robert Morris)

- 👤 **Created by**: Robert Morris
- 🎯 **Initial intent**: assess the size of the internet — program crawled to other computers to tally their numbers
- ⚠️ **Unexpected turn**: the program had no way to track computers it had already compromised, so it reinstalled itself repeatedly until computers ran out of memory & crashed
- 📊 **Damage**: 6,000 computers → ~10% of the internet at the time
- 🏛️ **Aftermath**: CERTs (Computer Emergency Response Teams) were established


## Virus in the Digital Age

- 🌐 **Malware → internet**: no need for a physical disk anymore

### 🕰️ 2000 — ILOVEYOU / Love Letter Attack (Onel de Guzman)

- 👤 **Created by**: Onel de Guzman
- 🎯 **Intent**: malicious — steal credentials
- 📧 **MO**: email titled "I love you" → upon opening, would send itself to everyone in the recipient's address book & install a program to collect usernames and passwords
- 💥 **Damage**: 40 million computers


## Phishing — Core Definition

**The use of digital communications to trick people into revealing sensitive data or deploying malicious software.**

### 🕰️ 2017 — Equifax Breach

- ❓ **Attacker**: not mentioned/unknown
- 🎯 **What happened**: attackers successfully infiltrated the credit reporting agency Equifax
- 📊 **Affected**: 143 million customer records stolen (PII & SPII information)
- 🔓 **Possible cause**: vulnerabilities (unpatched systems)
- 💰 **Settlement**: $575 million

## Methods of Attack — 20th July

| # | Term | Definition | Category |
|---|------|------------|----------|
| 1 | **Physical Social Engineering** | An attack in which the threat actor impersonates an employee, customer, or vendor to obtain unauthorized access to a physical location | Social Engineering |
| 2 | **Spear Phishing** | A malicious email attack targeting a specific user or group of users that appears to originate from a trusted source | Phishing |
| 3 | **Worm** | Malware that self-replicates, spreading across the network and infecting computers | Malware |
| 4 | **Virus** | A malware program that modifies other computer programs by inserting its own code to damage and/or destroy data | Malware |
| 5 | **Vishing** | Exploitation of electronic voice communication to obtain sensitive info or to impersonate a known source | Phishing |
| 6 | **Watering Hole Attack** | An attack in which the attacker compromises a website frequented by the target | Social Engineering |
| 7 | **Phishing** | The use of digital communication to trick people into revealing sensitive data or deploying malicious software | Phishing |
| 8 | **Business Email Compromise (BEC)** | An attack in which a threat actor impersonates a known source to obtain a financial advantage | Phishing |
| 9 | **Social Media Phishing** | Attacker collects detailed information about their target on social media sites before initiating an attack | Social Engineering |
| 10 | **Ransomware** | A malicious attack during which the attacker encrypts an organisation's data and demands payment to restore access | Malware |
| 11 | **Malware** | Software designed to harm devices & software | Malware |
| 12 | **Spyware** | Installed without permission, used to spy & steal | Malware |
| 13 | **Whaling** | Form of spear phishing which targets executives | Phishing |
| 14 | **USB Baiting** | Strategically leaves a malware USB stick for an employee to find & unknowingly infect a network | Social Engineering / Malware |



## CISSP (Certified Information System Security Professional) — Core Definition

**An advanced-level security certification issued by (ISC)², covering 8 domains.**

### 8 Domains
- 🎯 **Security & Risk Management** → goals, mitigation, compliance (HIPAA), BCP
- 🔐 **Asset Security** → secure assets, storage, maintenance, retention & destruction
- 🏗️ **Security Architecture & Engineering** → tools, systems & processes in place
- 📡 **Communication & Network Security** → wired & wireless (user behavior)
- 🪪 **Identity & Access Management** → role-based, policy-based
- ✅ **Security Assessment & Testing** → control testing, risks, threats, vulnerability
- 🚨 **Security Operations** → investigations & implementing preventive measures
- 💻 **Software Development Security** → secure coding practices

## Attack Types

- 🔑 **Password attacks** — brute force, rainbow table
- 🎭 **Social engineering attack** — exploits human error
- 🏢 **Physical attack** — affects digital & physical environments
- 🤖 **Adversarial AI** — manipulates AI/ML to conduct attacks more efficiently
- 🔗 **Supply chain attack** — involves third parties, affects multiple organisations, costly
- 🔒 **Cryptographic attack** — targets secure communication between sender & intended recipient


## Threat Actor Types (Attacker Types)

### 1️⃣ Advanced Persistent Threats (APTs)
- Significant expertise accessing an organisation's network
- Research targets
- Intent to damage or gain access to IP

### 2️⃣ Insider Threats
- Abuse their authorized access
- Intent → espionage, sabotage, data leak

### 3️⃣ Hacktivists
- Driven by political agenda
- Intent → demos, propaganda, fame

**Hackers →** Authorized, Semi-Authorized, Unauthorized

## Security Frameworks & Controls

**Security frameworks are guidelines** → plans to mitigate risks & threats to data & privacy → structured approach to implementing security lifecycle.

- 🎯 **Purpose** → protecting PII & SPII, identifying weakness in security, org risks, security alignment with business goals

### Four Core Components
1. 📝 Identifying & documenting goals
2. 📋 Guidelines to achieve goals
3. ⚙️ Procedures
4. 👀 Monitoring & communication

*(eg. GDPR)*

**Controls** → specific security risk (mitigations put in place)

## Secure Design

### CIA Triad
**A foundational model that helps inform how organisations consider risks when setting up systems & security policies.**

- 🔒 **Confidentiality** → only authorized users
- ✅ **Integrity** → data is correct, authentic & reliable
- 🟢 **Available** → data is available to authorized users when required

### NIST CSF (Framework, Voluntary, RMF)
Consists of standards, guidelines & best practices to manage cybersecurity risks.

### FERC–NERC
**(Federal Energy Regulatory Commission – North American Electric Reliability Corporation)**
- Regulations that apply to orgs that work with electricity
- Prepare, mitigate, report security incidents that can negatively affect power grid
- Legally required to adhere to Critical Infrastructure Protection (CIP)

## Compliance & Regulatory Frameworks

### FedRAMP (Federal Risk & Authorization Management Program)
- US Fed gov program
- Standardizes security assessments, authorisation, monitoring & handling of cloud services & product offerings
- Consistency across government sector

### CIS (Center for Internet Security)
- Non-profit
- Better defense

### GDPR
- Right to privacy for EU nationals

### PCI DSS (Payment Card Industry Data Security Standard)
- Credit card info in secure env
- Compliance standard to reduce credit card fraud

### HIPAA (Health Insurance Portability & Accountability Act)
- US Fed law
- Protect patient health information
- 3 rules → Privacy, Security, Breach notification
- PHI → Protected Health Info

### ISO (International Organisation for Standardisation)

## System & Organisation Controls (SOC Type 1, SOC Type 2)

- **AICPA** → Certified Public Accountant
- SOC1 & SOC2 focus on org user access policies at different organisational levels: Associate, Supervisor, Manager, Executive, Vendor, etc.

## Ethics

- 🤐 **Confidentiality** → proprietary or private info; my ethical duty is to keep it confidential
- 🔐 **Privacy protection** → safeguarding personal info from unauthorized use, accessing & sharing employee's PII
- ⚖️ **Law** → rules

**Note:** The only individuals in the US who are allowed to counterattack are approved employees of the federal government or military personnel.

### ICJ (right to counterattack, if authorized)
- Will only affect the party that attacked
- Direct comm asking attacker to stop
- Does not escalate situation
- Can be reversed

### Logs & SIEM
- 📄 **Log** → record of events
- 🔎 **SIEM** → collects logs → analyses → filters
  - Splunk, Chronicle
  - Self-hosted / Cloud-native (SaaS)

### Playbook
- Manual of how-tos, different for each org
- Covers: security, compliance, access management
- Provides evidence/forensic help for insurance decisions

### Network Protocol Analyzer (Packet Sniffer)
- Designed to capture & analyze traffic within a network
- Tools: TCPdump, Wireshark

## Forensics — Playbook

### Chain of Custody
- Documenting evidence, possession & control during incident lifecycle
- Who, what, where, why
- Evidence logs

### Protecting & Preserving Evidence Playbook
- Fragile & volatile digital evidence
- Sequence of preservation
- Prioritizes volatile data → **Order of Volatility**


## Introduction to Linux, SQL & Python

- 🐧 **Linux** → OS, open source, CLI-based → examine logs, investigate system
- 🗄️ **SQL & Python** → create, interact with & request info from DB
  - Automates repetitive & time-consuming tasks
  - Tasks that require high level of accuracy & detail


## More Tools & Concepts

| # | Term | Definition |
|---|------|------------|
| 1 | **Programming** | Process/set of instructions for a computer to execute a task |
| 2 | **Automation** | Using tech to reduce human involvement (manual, common, repetitive) → reduces human error |
| 3 | **SQL** | Same explanation as Programming |
| 4 | **OS** | Interface between computer hardware & user |
| 5 | **Command** | Instruction |
| 6 | **CLI** | Text-based UI |
| 7 | **Web Vulnerability** | Flaw in web app |
| 8 | **Antivirus** | Prevent, detect & eliminate |
| 9 | **IDS** | Monitors system activity & then alerts upon intrusion |
| 10 | **Encoding** | Public conversion algo to share info |
