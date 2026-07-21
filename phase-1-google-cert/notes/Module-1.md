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
