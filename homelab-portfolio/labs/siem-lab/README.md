# SIEM Lab

## Overview
What SIEM you're running (Wazuh / Splunk Free / ELK / Security Onion) and why you chose it.

## Architecture
- Hypervisor: [Proxmox / ESXi / VirtualBox]
- SIEM host specs: [CPU/RAM/disk]
- Endpoints monitored: [list VMs, e.g. Windows 10, Windows Server 2019 DC, Ubuntu]
- Log sources: [Sysmon, Windows Event Forwarding, auth.log, firewall logs, etc.]

## Diagram
*(embed an image or draw.io/PNG export here once you have one)*

## Configuration notes
Anything non-default you configured — custom decoders, ingest pipelines, dashboards, alert thresholds.

## Log sources & why they matter
| Source | What it captures | Why it's useful for detection |
|---|---|---|
| Sysmon | Process creation, network conns | Catches most endpoint attacker activity |
| Windows Security Log | Logons, privilege use | Auth-based attacks, lateral movement |
| ... | ... | ... |

## What's next
Roadmap items — e.g. "add a Linux honeypot," "integrate Suricata for network IDS," "build a dashboard for failed logon spikes."
