# Oluwasegunfunmi Kazeem

Cybersecurity engineer focused on Python security automation, identity-centred defensive security and detection engineering.

## Featured project

### MISP Threat Intelligence Investigation Workflow

A practical threat-intelligence project showing how I would use MISP when a security question or suspected incident needs to be turned into defensive action.

The workflow demonstrates how to:

- start with a concrete intelligence requirement or incident question;
- search MISP for the most relevant event rather than simply collecting the largest volume of indicators;
- pivot through Events, Attributes, Tags, Galaxies, ATT&CK mappings and external references;
- validate and enrich technical findings with underlying threat research;
- translate IOCs into SIEM, DNS, proxy, firewall and EDR hunts;
- translate ATT&CK behaviours into detection and telemetry requirements;
- turn vulnerability intelligence into remediation plus compromise assessment;
- use context, relevance and analyst judgment to decide whether to hunt, detect, patch, block, investigate or report.

The investigation includes LockBit and Babuk ransomware intelligence, Turla ATT&CK behaviour, Rhombus DDoS botnet activity, and the exploitation of Mitel MiVoice infrastructure associated with Lorenz ransomware reporting.

[View the MISP Threat Intelligence project](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/misp-threat-intelligence-platform-lab)

## Security Engineering work

### hACL — Healthcare Access List Manager

A tested Python access-governance tool featuring:

- Strict IPv4 validation
- Atomic allow-list updates
- Recoverable audit transactions
- Structured JSONL audit records
- SHA-256 state verification
- Explicit failure and conflict handling
- Python 3.12/3.13 CI
- Ruff, mypy, pytest and CodeQL

[Review hACL](https://github.com/theluckydraco-stack/python-security-engineering-portfolio)

### hACL ITDR Detector

A separate detection-engineering project now featuring:

- Sliding-window password-spray detection mapped to MITRE ATT&CK T1110.003
- Strict representative Windows Security parsing for events 4624, 4625, 4663 and 4740
- Employee, unknown-account, privileged-account and directory-status correlation
- Successful-logon detection for non-active identities with contextual T1078 mapping
- Successful-logon and account-lockout correlation after spray activity
- Trusted SHA-256 baselines for protected IPv4 allow lists
- Added, removed, replaced, missing and malformed allow-list detection
- Windows file-access evidence and cross-alert investigation timelines
- Versioned JSONL alerts and deterministic JSONL/Markdown timelines
- Static Sigma and Microsoft Sentinel KQL field-contract validation
- Evidence hashing and automated Markdown investigation reports
- Python 3.12/3.13 CI, Ruff, strict mypy, coverage enforcement and CodeQL

[Review the detector](https://github.com/theluckydraco-stack/hacl-itdr-detector)

Next milestone: add further identity detections and validate the detection content in an environment-specific SIEM lab.

## Technical focus

Python · Identity Security · ITDR · Detection Engineering · Access Control · File Integrity · Windows Security Events · Linux · PowerShell · MITRE ATT&CK · Sigma · KQL

## Current credentials

- CompTIA Security+
- ISC2 Certified in Cybersecurity
- Google Cybersecurity Professional Certificate
- Blue Team Level 1 — in progress

## Links

- [LinkedIn](https://www.linkedin.com/in/kos09)
- [MISP Threat Intelligence Investigation Workflow](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/misp-threat-intelligence-platform-lab)
- [Security Engineering Portfolio](https://github.com/theluckydraco-stack/python-security-engineering-portfolio)
- [hACL ITDR Detector](https://github.com/theluckydraco-stack/hacl-itdr-detector)
- [Blue Team Portfolio](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-)
