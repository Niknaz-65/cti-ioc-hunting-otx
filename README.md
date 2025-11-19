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

Identified ransomware TTPs, indicator clustering, and suspicious IP activity

Compared reputation across external sources (Talos, VirusTotal)

🖥️ API & Automation

Used curl + OTX API to retrieve IOC metadata in JSON

Parsed key indicators: hash, date first seen, malware family, sandbox detections

Demonstrated how CTI teams automate IOC enrichment

🧠 Methodology

Searched OTX for ransomware-related indicators

Filtered by indicator type (IPv4, URL, SHA256, Domain, Hostname)

Analyzed “Types of Indicators” & “Threat Infrastructure” heatmaps

Extracted full JSON using the OTX API:

curl -s -H "X-OTX-API-KEY: <API_KEY>" https://otx.alienvault.com/api/v1/pulses/indicators


Cross-checked suspicious indicators using:

Cisco Talos

VirusTotal

IP geolocation tools


🚀 How to Use

Clone the repository:

git clone https://github.com/Niknaz-65/cti-ioc-hunting-otx.git


Explore the /screenshots and /findings folders for detailed analysis.

👩‍💻 Author

Niknaz Sadehvandi
Cybersecurity Student | SOC Analyst Learner | Threat Intelligence Enthusiast
🔗 LinkedIn: www.linkedin.com/in/niknaz-sadehvandi-a34179325
