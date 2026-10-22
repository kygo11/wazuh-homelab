# Wazuh SOC Home Lab

A small Security Operations Center (SOC) lab using UTM, Ubuntu 22.04, and Wazuh. One VM runs the Wazuh SIEM; a second runs a Wazuh agent as a monitored endpoint. Both VMs share a network; the agent ships logs to the SIEM; alerts are viewed from the browser. I generated real security events and investigated them in the dashboard.

## What I did
- Installed and configured a Wazuh all-in-one SIEM.
- Enrolled a Linux endpoint agent.
- Simulated and investigated four attack types: brute-force logins, privilege escalation, account creation, and file tampering.
- Wrote analyst notes mapping each alert to its meaning and severity.
- Tuned detection: enabled real-time File Integrity Monitoring on `/etc` (the default was a 12-hour scan).

## Skills
Log analysis · SIEM operations · alert triage · MITRE ATT&CK · Linux administration · detection tuning

