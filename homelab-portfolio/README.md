# Homelab Portfolio — [Your Name]

Security-focused homelab where I build detection infrastructure, simulate attacks, and write up the findings the way I would in a SOC shift handoff. This repo is a working log of that lab, not a polished résumé — expect it to grow as I add more.

**Target role:** SOC Analyst / Security Operations
**Background:** [1-2 sentences — e.g. "Transitioning from IT support into security, Sec+ certified, building hands-on detection experience."]

## What's in here

| Folder | What it is |
|---|---|
| [`writeups/`](writeups/) | Incident-style write-ups: attack simulated → what the SIEM caught → analysis → lessons learned |
| [`labs/siem-lab/`](labs/siem-lab/) | How my SIEM/log pipeline is built (architecture, log sources, config) |
| [`labs/pentest-lab/`](labs/pentest-lab/) | The attacker-side environment I use to generate real traffic/logs to detect |
| [`detections/`](detections/) | Sigma rules / correlation rules / detection logic I've written |
| [`tools/`](tools/) | Small scripts — log parsers, enrichment tools, automation |

## Lab architecture (high-level)

*(Add a diagram here once you have one — even a simple draw.io export or ASCII diagram helps. Example:)*

```
[Kali attacker VM] --> [Target VMs: Windows/Linux] --> [Wazuh/Splunk/ELK] --> [Dashboards + Alerts]
```

## Featured write-ups

- [Detecting X via Y](writeups/TEMPLATE.md) *(replace with your real entries as you add them)*

## Skills demonstrated

`SIEM (Wazuh/Splunk/ELK)` `Log analysis` `Sigma rules` `Network traffic analysis` `Windows/Linux event logs` `Incident documentation` `Attack simulation (MITRE ATT&CK mapped)`

## Contact

[LinkedIn] · [Email] · [Resume link, optional]
