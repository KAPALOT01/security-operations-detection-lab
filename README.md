# Security Operations Detection Lab

**Windows security monitoring and detection engineering using Splunk, Sysmon, Python, and MITRE ATT&CK.**

## Project overview

This project describes a five-endpoint Windows security lab used to explore endpoint telemetry, SIEM analysis, detection engineering, and investigation workflows.

The supplied resume reports analysis of 50,000+ events and development of 14 detection use cases. The described use-case families include brute-force activity, suspicious PowerShell, privilege escalation, and persistence. Investigation playbooks were mapped to MITRE ATT&CK.

## Workflow

1. Collect Windows endpoint events with Sysmon.
2. Review and analyze event patterns in Splunk.
3. Develop detection logic and investigate suspicious activity.
4. Document investigation steps and map techniques to MITRE ATT&CK.
5. Use Python for supporting data or workflow automation.

## Tools

- Splunk
- Sysmon
- Python
- MITRE ATT&CK

## Repository contents and scope

This public repository currently contains this project overview. The underlying Splunk queries, Sysmon configuration, sample event data, Python scripts, and playbooks were not available in the supplied project files, so they are not included here. The event counts and detection totals are resume-reported project figures and cannot be reproduced from this repository as it stands.

This is a portfolio lab description, not a claim of client impact or production monitoring.
