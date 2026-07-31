# ICS/OT Attack Lab

## Overview
Hands-on lab exploring attack techniques against Industrial Control System (ICS) / 
Operational Technology (OT) environments. This work builds on my Electrical Engineering 
background and PLC programming experience, applying that industrial systems knowledge 
to understand real-world OT security risks.

## Video Walkthrough
🎥 Watch the walkthrough on Loom HERE:
## Objective
Demonstrate how an attacker could exploit the lack of authentication in the Modbus 
protocol to gain unauthorized read/write access to a simulated Programmable Logic 
Controller (PLC), highlighting the risks of unsecured industrial communication protocols.
## Methodology
1. Identified the target PLC/OT device on the lab network and confirmed the Modbus 
   service was exposed and unauthenticated.
2. Used network analysis tools to inspect Modbus traffic and identify readable/writable 
   register addresses.
3. Sent unauthorized read/write requests to the PLC's registers to demonstrate that an 
   attacker could alter device state without valid credentials.
4. Documented the impact this could have in a real industrial environment (e.g. 
   disrupting a process, causing equipment damage, or safety risk).

## Key Findings
- [What vulnerability/weakness did you demonstrate?]

## Mitigations
- Network segmentation (IT/OT separation)
- Protocol-level authentication where supported

## Disclaimer
Conducted in an isolated lab environment for educational purposes as part of a 
cybersecurity bootcamp. No production ICS/OT systems were involved.
