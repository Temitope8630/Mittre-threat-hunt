# Mitre-threat-hunt

## Overview

This project presents a structured threat hunting and threat intelligence analysis conducted using the MITRE ATT&CK Framework and SOCRadar Threat Intelligence Platform.

The research focuses on identifying and analyzing Advanced Persistent Threat (APT) groups targeting critical infrastructure and high-value sectors. The project maps adversary Tactics, Techniques, and Procedures (TTPs) to the MITRE ATT&CK Enterprise Matrix and performs cross-APT overlap analysis to identify high-priority detection opportunities.

---

## Project Objectives

* Identify APT groups actively targeting critical infrastructure and strategic industries.
* Conduct threat intelligence collection using SOCRadar.
* Map adversary behaviors to the MITRE ATT&CK Enterprise Framework.
* Visualize attack techniques using MITRE ATT&CK Navigator.
* Analyze TTP overlaps across multiple nation-state threat actors.
* Generate actionable detection and threat hunting recommendations.

---

## Threat Actors Analyzed

The following nation-state threat actors were selected for deep-dive analysis:

| Threat Actor  | Origin      | Primary Motivation                |
| ------------- | ----------- | --------------------------------- |
| APT41         | China       | Espionage & Financial Gain        |
| KIMSUKY       | North Korea | Strategic Intelligence Collection |
| SANDWORM      | Russia      | Disruption & Sabotage             |
| LAZARUS GROUP | North Korea | Financial Theft & Espionage       |

---

## Methodology

### Phase 1: Threat Landscape Scoping

* Industry Selection
* Geographic Region Selection
* Threat Surface Definition

### Phase 2: Threat Actor Identification

* Intelligence collection via SOCRadar
* Filtering by industry, region, and threat actor type
* Identification of 1,138 relevant APT entities

### Phase 3: MITRE ATT&CK Mapping

* Research of adversary TTPs
* Mapping techniques to ATT&CK Enterprise v19
* Categorization across 15 ATT&CK tactics

### Phase 4: Overlap Analysis

* ATT&CK Navigator layer creation
* Composite technique overlap analysis
* Detection engineering prioritization

---

## Key Findings

### Full Kill Chain Coverage

All analyzed APT groups demonstrated capabilities across the entire MITRE ATT&CK lifecycle.

### Universal TTP Convergence

Significant overlap exists between nation-state actors despite differing geopolitical objectives.

### Credential Theft Dominance

Credential dumping, session hijacking, and MFA interception were common across all groups.

### Living-Off-The-Land Techniques

Adversaries heavily rely on legitimate system tools to evade detection.

### Encrypted Command & Control

HTTPS and encrypted communication channels remain the preferred C2 mechanisms.

---

## MITRE ATT&CK Tactics Covered

* Reconnaissance
* Resource Development
* Initial Access
* Execution
* Persistence
* Privilege Escalation
* Defense Evasion
* Defense Impairment
* Credential Access
* Discovery
* Lateral Movement
* Collection
* Command & Control
* Exfiltration
* Impact

---

## Tools Used

### Threat Intelligence

* SOCRadar

### Threat Framework

* MITRE ATT&CK Enterprise v19

### Visualization

* MITRE ATT&CK Navigator

### Analysis

* Threat Hunting
* Threat Intelligence Correlation
* TTP Mapping
* Adversary Emulation Research

---

## Project Deliverables

* Comprehensive Threat Hunting Report
* APT Intelligence Profiles
* MITRE ATT&CK Technique Mapping
* Cross-APT Overlap Analysis
* ATT&CK Navigator Layers
* Defensive Recommendations

---

## Skills Demonstrated

* Threat Hunting
* Threat Intelligence Analysis
* MITRE ATT&CK Mapping
* Detection Engineering
* OSINT Research
* Adversary Emulation
* Risk Assessment
* Security Operations (SOC)
* Cyber Threat Analysis

---

## References

* MITRE ATT&CK Framework
* MITRE ATT&CK Navigator
* SOCRadar Threat Intelligence Platform
* CISA Advisories
* US-CERT Threat Reports
* Mandiant Threat Intelligence Research

---

## Author

**Toheeb Adabanija**

Certified Cybersecurity Specialist

### Areas of Interest

* Threat Hunting
* Threat Intelligence
* Detection Engineering
* Security Operations
* Digital Forensics
* Adversary Emulation

---

## Disclaimer

This project was conducted strictly for cybersecurity research, threat intelligence analysis, defensive security education, and professional development purposes. All information was obtained from publicly available intelligence sources and the MITRE ATT&CK knowledge base.

