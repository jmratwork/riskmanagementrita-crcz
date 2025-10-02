# Solution for Exercise 2: ICS Energy Infrastructure

## Expected findings
- Inventory of critical OT components (SCADA, PLC, RTU, field networks) and their interdependencies with IT systems.
- Updated zones and conduits diagram in line with ISA/IEC 62443 with identified remote access points.
- Register of pertinent threats and tactics (MITRE ATT&CK for ICS), including remote engineering compromise and process manipulation.
- Assessment of current controls such as industrial firewalls, application whitelisting, and OT change policies.

## Identified risks
- Intrusion into the corporate network that pivots towards the industrial DMZ and affects SCADA operations.
- Malicious manipulation of PLC parameters causing interruptions to power generation or distribution.
- Denial-of-service attacks against communication links with insufficient redundancy across control centres.
- Use of shared credentials for remote maintenance access without supervision or logging.

## Recommended mitigations
- Implement continuous monitoring of OT networks with anomaly detection and visibility of industrial protocols.
- Apply role-based access control and multi-factor authentication for remote engineering access.
- Segment the network with next-generation firewalls between IT/OT and critical zones, using minimally necessary control lists.
- Establish patch and change management procedures validated in test environments before production.
- Design and test OT incident response plans, with exercises coordinated with operations teams and suppliers.
