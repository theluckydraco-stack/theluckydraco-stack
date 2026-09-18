# Oluwasegunfunmi Kazeem

Cybersecurity engineer focused on Python security automation, identity-centred defensive security and detection engineering.

## Featured projects

### Digital Financial Services Threat Landscape

A threat-informed defensive research project focused on how attacks against banks, fintechs, payment platforms and cryptocurrency services move through trusted identities, cloud and SaaS access, third parties, software dependencies, support processes and payment workflows.

The project connects current and historical financial-sector threat activity to the evidence a defender would need to see it: identity and MFA records, endpoint and network telemetry, cloud and SaaS audit logs, developer activity, supplier access, customer-support records, payment events and fraud signals. It includes actor and campaign analysis, MITRE ATT&CK mapping, financial-SOC telemetry requirements and detection specifications designed around recurring attack paths rather than actor names alone.

[View the Digital Financial Services Threat Landscape](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/financial-sector-threat-landscape)

### MISP Threat Intelligence Investigation Workflow

A practical threat-intelligence project showing how I would use MISP when a security question or suspected incident needs to be turned into defensive action.

The workflow moves from an intelligence requirement to the most relevant MISP Event, then through Attributes, Tags, Galaxies, ATT&CK mappings and external research. The resulting intelligence is translated into SIEM, DNS, proxy, firewall and EDR hunts, detection requirements, vulnerability remediation and compromise assessment.

The investigation includes LockBit and Babuk ransomware intelligence, Turla ATT&CK behaviour, Rhombus DDoS botnet activity, and exploitation of Mitel MiVoice infrastructure associated with Lorenz ransomware reporting.

[View the MISP Threat Intelligence Investigation Workflow](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/misp-threat-intelligence-platform-lab)

### How the threat-intelligence work connects

```text
Financial-sector threat landscape
        ↓
Which attack paths and behaviours matter?
        ↓
MISP / threat-intelligence workflow
        ↓
What relevant intelligence can be located,
validated and operationalised?
        ↓
Detection validation — next hands-on phase
        ↓
Required telemetry → rule/query → alert
        ↓
Investigation → tuning → validated detection
```

The next implementation phase is to validate a small number of the financial-SOC detection specifications against controlled laboratory telemetry, beginning with Windows account and privilege-change correlation before moving into cloud identity, SaaS and payment-workflow scenarios.

### Forensic Evidence Acquisition and Recovery

A controlled digital-forensics workflow focused on acquiring evidence at the right scope, verifying acquisition integrity, identifying filesystem structures, extracting metadata, and recovering deleted content.

The project combines whole-memory capture, process-specific dumping, E01 physical-disk imaging and verification, targeted KAPE collection, filesystem identification, metadata analysis, file carving, and cryptographic hashing. It also records the evidentiary limits of the work rather than treating tool output as proof of a broader incident.

[View the Forensic Evidence Acquisition and Recovery project](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/digital-forensics/forensic-evidence-acquisition-and-recovery)

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

Python · Identity Security · ITDR · Detection Engineering · Threat Intelligence · Digital Forensics · Financial-Sector Security · Access Control · File Integrity · Windows Security Events · Linux · PowerShell · MITRE ATT&CK · Sigma · KQL

## Current credentials

- CompTIA Security+
- ISC2 Certified in Cybersecurity
- Google Cybersecurity Professional Certificate
- Blue Team Level 1 — in progress

## Links

- [LinkedIn](https://www.linkedin.com/in/kos09)
- [Digital Financial Services Threat Landscape](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/financial-sector-threat-landscape)
- [MISP Threat Intelligence Investigation Workflow](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/threat-intelligence/misp-threat-intelligence-platform-lab)
- [Forensic Evidence Acquisition and Recovery](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-/tree/main/digital-forensics/forensic-evidence-acquisition-and-recovery)
- [Security Engineering Portfolio](https://github.com/theluckydraco-stack/python-security-engineering-portfolio)
- [hACL ITDR Detector](https://github.com/theluckydraco-stack/hacl-itdr-detector)
- [Blue Team Portfolio](https://github.com/theluckydraco-stack/blue-team-level-1-portfolio-)
