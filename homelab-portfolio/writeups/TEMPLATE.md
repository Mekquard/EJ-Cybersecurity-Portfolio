# [Title: e.g. "Detecting a Mimikatz Credential Dump via Sysmon + Wazuh"]

**Date:** YYYY-MM-DD
**Environment:** [e.g. Windows Server 2019 DC + Wazuh SIEM, Sysmon installed]
**MITRE ATT&CK:** [e.g. T1003 – OS Credential Dumping]

## Summary

One or two sentences: what attack did you simulate, and what did you catch or learn? (Write this like the top of an incident ticket — someone should understand the whole story from this alone.)

## Setup

- What's the environment (VMs, OS versions, tools installed)
- What log sources were feeding the SIEM (Sysmon, Windows Event Log, auth logs, etc.)
- Any relevant baseline config (what rules/alerts were active beforehand)

## Attack simulation

What you did, step by step, from the attacker side. Screenshots/commands welcome.

```
example command or tool output here
```

## Detection / Analysis

This is the core of the write-up. Walk through it like an analyst would:

1. **What alert fired (or didn't)?** Screenshot or paste the raw log/alert.
2. **What did you look at first?** (process tree, parent/child process, network connections, timestamps)
3. **What confirmed malicious activity vs. what could've been a false positive?**
4. **Any pivoting** — did you check other log sources, other hosts, related IOCs?

## Root cause / Finding

What actually happened, in plain terms.

## Remediation / Recommendation

What would you do next in a real SOC? (isolate host, reset creds, tune the detection rule, escalate, etc.)

## Detection rule (if applicable)

If you wrote a Sigma rule or SIEM correlation rule for this, link or paste it here.

```yaml
# Sigma rule example
```

## Lessons learned

What would you do differently, what gaps did this expose, what did you learn about the tooling.
