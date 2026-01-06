# Cyber Threat Intelligence & IOC Hunting (OTX / LevelBlue)

## Overview
Threat intelligence project focused on hunting, enriching, and analyzing Indicators of Compromise (IOCs) using AlienVault OTX, LevelBlue Labs, and API-driven data collection to support SOC and CTI workflows.

## Why This Project Matters to SOC Teams
- Supports rapid identification of malicious infrastructure during investigations
- Enables enrichment of raw indicators for SIEM correlation and blocking decisions
- Demonstrates scalable IOC analysis across large datasets

## Environment
- OS: Linux / Windows
- Threat Intelligence Platforms: AlienVault OTX, LevelBlue Labs
- External Sources: Cisco Talos, VirusTotal
- Tools: curl, REST APIs, JSON parsing
- Frameworks: Threat Intelligence lifecycle, SOC triage workflow

## Data Collected / Artifacts
- IPv4 and IPv6 addresses
- Domains and URLs
- File hashes (SHA-256)
- Ransomware-related indicators
- IOC metadata (first seen, malware family, reputation)
- API JSON responses

## Analysis Steps
1. Queried AlienVault OTX for ransomware-related indicators
2. Filtered indicators by type (IP, domain, URL, hash)
3. Retrieved IOC metadata via OTX API
4. Correlated indicators with LevelBlue intelligence
5. Cross-validated reputation using Cisco Talos and VirusTotal
6. Documented findings with screenshots and structured notes

## Findings
- Identified clusters of ransomware-related infrastructure
- Observed repeated reuse of hosting providers and ASNs
- Confirmed malicious reputation across multiple intelligence sources
- Isolated high-confidence indicators suitable for detection and blocking

## Outcome
- Curated set of validated IOCs
- Indicators ready for SIEM ingestion and threat hunting
- Recommended continuous monitoring for related infrastructure

## Screenshots / Evidence

All evidence stored in `/screenshots/`.

## Repository Structure
```text
/screenshots   → investigation evidence  
/findings      → IOC data and analysis notes  
queries.txt    → API queries and filters  
README.md      → project documentation
---

## Skills Demonstrated
- Threat intelligence analysis
- IOC enrichment and validation
- API-driven data collection
- SOC triage support
- Ransomware infrastructure analysis


## Author
**Niknaz Sadehvandi**  
**Cybersecurity Analyst**  
LinkedIn: https://www.linkedin.com/in/niknaz-sadehvandi-a34179325/
