# Homelab Cybersecurity Portfolio — Efrain Martinez III (EJ)

Security Operations focused homelab where I build detection rules, simulate attacks, conduct in-depth email header analysis, network security and write up the findings the way I would in a SOC shift handoff. This repo is a working log of my cyber lab projects — expect it to grow as I add more.

**Background:** Cybersecurity professional with 3 years of hands-on experience in Security Operations, threat detection, and incident response. Currently working as an IT Security Specialist | SOC Analyst supporting federal environments, where I analyze phishing threats, conduct compliance and vulnerability scans using Tenable, manage security incidents end-to-end, and coordinate remediation efforts with system administrators.

## What's in here

| Folder | What it is |
|---|---|
| [`writeups/`](writeups/) | Incident-style write-ups: attack simulated → what the SIEM caught → analysis → lessons learned |
| [`labs/siem-lab/`](labs/siem-lab/) | How my SIEM/log pipeline is built (architecture, log sources, config) |
| [`labs/pentest-lab/`](labs/pentest-lab/) | The attacker-side environment I use to generate real traffic/logs to detect |
| [`detections/`](detections/) | Sigma rules / correlation rules / detection logic I've written |
| [`tools/`](tools/) | Small scripts — log parsers, enrichment tools, automation |

## Lab architecture (high-level)

```
[Kali attacker VM] --> [Target VMs: Windows/Linux] --> [Wazuh/Splunk] --> [Dashboards + Alerts]
```

## Featured write-ups

- [Detecting X via Y](writeups/TEMPLATE.md) *(replace with your real entries as you add them)*

## Skills demonstrated

`Incident response` `SIEM (Wazuh/Splunk)` `Log analysis` `Sigma rules` `Network traffic analysis` `Windows/Linux event logs` `Incident documentation` `Attack simulation (MITRE ATT&CK mapped)` `Email header analysis` `Endpoint security` `DFIR` `Threat intelligence`

## Contact

www.linkedin.com/in/efrain-martinez-iii · efrainmartinez.0803@gmail.com
