# Browser Security & Log Analysis
This repository hosts a standalone, multi-part cybersecurity project designed to demonstrate **browser-focused threat detection**, **defensive engineering**, and **logfile analysis** from a SOC analyst perspective. It is independent of any prior coursework or labs and showcases practical skills used in real-world security operations to identify and investigate client-side threats, particularly from web browsers. The project was inspired by direct feedback from a hiring manager to highlight skills that matter for a junior-to-mid-level SOC analyst role.
Repository Structure:
browser-security-and-log-analysis/
├── README.md
├── part1-chrome-attack-surface/
│   ├── README.md
│   ├── attack-scenarios.md
│   └── screenshots/
├── part2-chrome-detection-and-defense/
│   ├── README.md
│   ├── wazuh-rules/
│   ├── detection-logic.md
│   └── dashboards/
└── part3-logfile-parsing-and-baselining/
    ├── README.md
    ├── baseline-analysis.md
    ├── anomaly-investigation.md
    └── sample-logs/
Project Sections:
**Part 1: Chrome Attack Surface** — Documents common methods attackers use to abuse Google Chrome, including extensions, process exploitation, and access to credential files. Focus is on understanding threat techniques rather than exploitation. Screenshots and documentation are included to illustrate each scenario.
**Part 2: Chrome Detection & Defense** — Demonstrates detection engineering by creating custom rules, alerts, and dashboards (e.g., Wazuh) to catch browser-based threats. Includes examples of alert tuning and visualization for SOC-style monitoring.
**Part 3: Logfile Parsing & Baseline Analysis** — Focuses on analyst-level log review skills: establishing normal behavioral baselines, detecting subtle anomalies, and investigating events that automated alerts may miss. Sample logs and analysis are provided for reference.
Tools & Technologies:
- Windows endpoints  
- Google Chrome  
- Wazuh (SIEM/HIDS)  
- Windows Event Logs  
- Sysmon (optional)  
- Manual log parsing techniques
Skills Highlighted:
- Threat modeling for client-side attacks  
- Detection engineering and alert creation  
- Logfile parsing and anomaly detection  
- Baseline creation and correlation  
- SOC-style investigative methodology
Disclaimer: All work is performed in a controlled lab environment for **educational and defensive purposes only**.
