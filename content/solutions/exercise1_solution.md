# Solution for Exercise 1: Banking Sector

## Expected findings
- Complete inventory of critical assets (core banking, digital channels, SWIFT, customer databases).
- Map of dependencies between applications and third parties, including cloud service providers and payment processors.
- Identification of relevant threats based on MITRE ATT&CK for financial environments (e.g. targeted phishing, credential abuse, data exfiltration).
- Assessment of existing controls (multi-factor authentication, fraud monitoring, segregation of duties) and gaps.

## Identified risks
- Compromise of privileged credentials that enables fraudulent transfers or manipulation of accounting records.
- Ransomware attacks against payment servers with a direct impact on service availability and regulatory compliance.
- Exfiltration of sensitive customer data with regulatory (PSD2, GDPR) and reputational consequences.
- Critical dependency on an external supplier without robust continuity plans.

## Recommended mitigations
- Implement privileged access management (PAM) with continuous monitoring and automatic credential rotation.
- Strengthen phishing detection with awareness campaigns, advanced filtering, and reinforced authentication.
- Establish network segmentation and regularly tested immutable backups to mitigate ransomware.
- Formalise service level agreements (SLAs) and contingency plans with key third parties; conduct recovery tests.
- Integrate anomalous behaviour alerts into the SIEM and define incident response procedures coordinated with business areas.
