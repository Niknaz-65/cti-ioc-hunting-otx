🛡️ Cyber Threat Intelligence & IOC Hunting (OTX / LevelBlue)

A hands-on threat intelligence project focused on identifying, enriching, and analyzing Indicators of Compromise (IOCs) using AlienVault OTX, LevelBlue Labs, and API-driven data collection.
This project explores ransomware indicators, network infrastructure patterns, and IP/domain/file reputation to simulate real SOC & CTI workflows.

📊 Project Highlights
🔍 IOC Hunting & Filtering

Queried 30K+ OTX indicators using filters such as:

IPv4

IPv6

URL

Domain

Ransomware

FileHash (SHA-256)

🧬 Threat Intelligence Analysis

Mapped global threat infrastructure by country

Identified ransomware TTPs, indicator clustering, suspicious IP activity

Compared reputation across external sources (Talos, VirusTotal)

🖥️ API & Automation

Used curl + OTX API to retrieve IOC metadata in JSON:
curl -s -H "X-OTX-API-KEY: <API_KEY>" https://otx.alienvault.com/api/v1/pulses/indicators
Extracted:

hash

date first seen

malware family

sandbox detections

Cross-checked indicators using:

Cisco Talos

VirusTotal

IP geolocation tools

🧠 Methodology Summary

Searched OTX for ransomware-related indicators

Filtered by IPv4, URL, SHA256, Domain, Hostname

Analyzed Types of Indicators and Threat Infrastructure

Correlated suspicious hosts with malware families

git clone https://github.com/Niknaz-65/cti-ioc-hunting-otx.git

👩‍💻 Author

Niknaz Sadehvandi
Cybersecurity Student | SOC Analyst Learner | Threat Intelligence Enthusiast
🔗 LinkedIn: https://www.linkedin.com/in/niknaz-sadehvandi-a34179325/
