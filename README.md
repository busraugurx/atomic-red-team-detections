# MITRE ATT&CK Detection Rules

This repository contains a growing collection of Sigma and YARA detection rules mapped to MITRE ATT&CK techniques.

The rules are designed to reflect real-world adversary behavior rather than lab-only indicators, with a focus on execution, defense evasion, persistence, and credential access.  
Each rule is written to be practical for SOC and detection engineering use cases and is tested against known atomic or real attack patterns where possible.


## Scope

- Sigma rules for Windows process, registry, and PowerShell-based techniques
- YARA rules for memory and file-based detection
- MITRE ATT&CK–mapped techniques (e.g. T1059, T1547, T1027)
- Emphasis on fileless and in-memory execution patterns


## Goals

- Build high-signal detection rules aligned with MITRE ATT&CK
- Avoid noisy, low-value indicators
- Provide reusable detection logic for blue teams and SOC analysts
- Serve as a personal detection engineering portfolio
