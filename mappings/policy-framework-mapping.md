# Policy Framework Mapping Matrix

Maps every policy in this library to the frameworks it satisfies.
Use this as a quick reference during audits, gap assessments, or control mapping exercises.

**Frameworks covered:**
- NIST SP 800-53 Rev 5
- NIST Cybersecurity Framework (CSF) v1.1
- ISO/IEC 27001:2022
- CIS Controls v8
- PCI DSS v4.0
- HIPAA (where applicable)

> For the full mapping with all control references, download the
> [Excel version](./policy-framework-mapping.xlsx).

---

## Governance and core security

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Information Security Policy | PL-1, PL-2, PM-1 | GV.OC, GV.RM | 5.1, 5.2, 5.3 | CIS 1, 17 | 12.1, 12.3 | 164.308(a)(1) |
| Risk Assessment Policy | RA-1, RA-2, RA-3, RA-5 | GV.RM, ID.RA | 6.1.2, 8.2, 8.3 | CIS 18 | 12.2, 12.3.1 | 164.308(a)(1)(ii)(A) |
| Information Security Risk Management Standard | RA-1, RA-3, PM-9, PM-28 | GV.RM, ID.RA, ID.IM | 6.1, 8.2, 8.3, 8.4 | CIS 18 | 12.3 | 164.308(a)(1) |

---

## Identity and access management

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Access Control Policy | AC-1, AC-2, AC-3, AC-6, AC-17 | PR.AA, PR.AC | 9.1.1, 9.2.1, 9.4.1, 9.4.2 | CIS 5, 6 | 7.1, 7.2, 8.2, 8.3 | 164.308(a)(4), 164.312(a)(1) |
| Identification and Authentication Policy | IA-1, IA-2, IA-3, IA-5, IA-8 | PR.AA | 9.2.1, 9.3.1, 9.4.3 | CIS 5, 6 | 8.2, 8.3, 8.4, 8.5 | 164.312(d) |
| Account Management Access Control Standard | AC-2, AC-3, AC-5, AC-6, IA-4 | PR.AA, PR.AC | 9.2.1, 9.2.2, 9.2.3 | CIS 5, 6 | 7.2, 8.2, 8.6 | 164.308(a)(4) |
| Personnel Security Policy | PS-1, PS-2, PS-3, PS-4, PS-5 | GV.OC, PR.AT | 6.1.1, 7.1.1, 7.2.1, 7.3.1 | CIS 17 | 12.6 | 164.308(a)(3) |

---

## Incident response and threat handling

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Incident Response Policy | IR-1, IR-2, IR-4, IR-5, IR-6 | RS.MA, RS.AN, RC.RP | 16.1.1, 16.1.2, 16.1.5 | CIS 17 | 12.10, 12.10.1 | 164.308(a)(6) |
| Cyber Incident Response Standard | IR-4, IR-5, IR-6, IR-7, IR-8 | RS.MA, RS.AN, RS.CO, RC.RP | 16.1.3, 16.1.4, 16.1.5, 16.1.7 | CIS 17 | 12.10.2, 12.10.3, 12.10.6 | 164.308(a)(6)(ii) |
| Computer Security Threat Response Policy | IR-4, IR-6, SI-3, SI-4 | DE.CM, RS.MA | 16.1.2, 16.1.4 | CIS 13, 17 | 12.10.4 | 164.308(a)(6) |

---

## Endpoint and device security

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Mobile Device Security | AC-17, AC-19, AC-20, MP-5, SC-28 | PR.AC, PR.DS | 6.2.1, 6.2.2, 8.1.3 | CIS 4, 13 | 12.3.3 | 164.310(d) |
| Media Protection Policy | MP-1, MP-2, MP-3, MP-4, MP-6, MP-7 | PR.DS | 8.3.1, 7.5.3 | CIS 3 | 9.3, 9.4 | 164.310(d)(1) |
| Remote Access Standard | AC-17, IA-2, IA-3, SC-8 | PR.AA, PR.AC | 6.2.2, 9.1.2, 9.4.2 | CIS 4, 12 | 8.2.8, 12.3.3 | 164.312(a)(2)(ii) |
| Sanitization and Secure Disposal Standard | MP-6, SI-12 | PR.DS | 8.3.2, 7.5.3 | CIS 3 | 9.4.6, 9.4.7 | 164.310(d)(2)(i) |

---

## Operations and hardening

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Patch Management Standard | SI-2, SI-3, CM-7 | PR.PS, DE.CM | 8.8.1, 12.6.1 | CIS 7 | 6.3.3 | 164.308(a)(5)(ii)(B) |
| Maintenance Policy | MA-1, MA-2, MA-3, MA-4, MA-5 | PR.PS | 7.13.1, 8.8.1 | CIS 4 | 12.3 | 164.310(a)(2)(iv) |
| Configuration Management Policy | CM-1, CM-2, CM-3, CM-6, CM-7 | PR.PS, ID.AM | 8.9.1, 8.9.2 | CIS 4 | 2.2, 6.3 | 164.312(a)(2)(ii) |
| Secure Configuration Standard | CM-2, CM-6, CM-7, SI-2 | PR.PS | 8.9.1, 8.9.3 | CIS 4 | 2.2.1, 6.3.3 | 164.308(a)(5) |
| Secure SDLC Standard | SA-3, SA-8, SA-11, SA-15, SA-17 | PR.PS, DE.AE | 8.25, 8.26, 8.27, 8.28, 8.29 | CIS 16 | 6.2, 6.3, 6.4, 6.5 | 164.308(a)(1) |
| Planning Policy | PL-1, PL-2, PL-4, PL-8 | GV.OC, GV.RM | 5.1, 5.2, 6.1 | CIS 17, 18 | 12.1 | 164.308(a)(1) |

---

## Awareness and training

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Security Awareness and Training Policy | AT-1, AT-2, AT-3, AT-4 | PR.AT, GV.OC | 6.3.1, 7.2.2 | CIS 14 | 12.6, 12.6.1, 12.6.2 | 164.308(a)(5) |

---

## Procurement and physical controls

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| System and Services Acquisition Policy | SA-1, SA-2, SA-3, SA-4, SA-9 | GV.SC, ID.SC | 8.30.1, 5.19, 5.20, 5.21 | CIS 15 | 6.1, 6.3, 12.8 | 164.308(b) |
| Physical and Environmental Protection Policy | PE-1, PE-2, PE-3, PE-6, PE-12, PE-13 | PR.AC, PR.PS | 7.1.1, 7.2.1, 7.3.1, 7.4.1 | CIS 10 | 9.1, 9.2, 9.3 | 164.310(a)(1) |

---

## Data protection

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Encryption Standard | SC-8, SC-12, SC-13, SC-28 | PR.DS | 10.1.1, 8.24.1 | CIS 3 | 3.5, 4.2.1 | 164.312(a)(2)(iv), 164.312(e)(2)(ii) |
| Information Classification Standard | RA-2, MP-3, SI-12 | ID.AM, PR.DS | 5.12, 5.13, 5.14 | CIS 3 | 9.4.1, 12.3.1 | 164.308(a)(1) |

---

## Monitoring and integrity

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Security Logging Standard | AU-1, AU-2, AU-3, AU-6, AU-9, AU-12 | DE.CM, DE.AE | 8.15.1, 8.16.1 | CIS 8 | 10.2, 10.3, 10.5, 10.7 | 164.312(b) |
| System and Information Integrity Policy | SI-1, SI-2, SI-3, SI-4, SI-7, SI-10 | DE.CM, PR.DS | 8.8.1, 8.16.1, 8.7.1 | CIS 7, 10 | 6.3.3, 11.5 | 164.312(c)(1) |

---

## Auditing and oversight

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Auditing and Accountability Policy | AU-1, AU-2, AU-6, AU-11, AU-12 | DE.AE, GV.OC | 9.5.1, 9.5.2, 8.15.1 | CIS 8 | 10.1, 10.2, 10.4, 10.6 | 164.308(a)(1)(ii)(D), 164.312(b) |

---

## Resilience and recovery

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Contingency Planning Policy | CP-1, CP-2, CP-3, CP-4, CP-6, CP-9, CP-10 | RC.RP, RC.CO | 5.29, 5.30, 8.13.1 | CIS 11 | 12.3.4, 12.10.1 | 164.308(a)(7) |

---

## Acceptable use

| Policy / Standard | NIST 800-53 | NIST CSF | ISO 27001 | CIS v8 | PCI DSS | HIPAA |
|---|---|---|---|---|---|---|
| Acceptable Use of IT Resources Policy | PL-4, AC-8, PS-6 | GV.OC, PR.AT | 5.10, 6.2.1 | CIS 4, 14 | 12.3.3 | 164.308(a)(3)(ii)(A) |

---

## Framework reference key

| Framework | Description |
|---|---|
| NIST SP 800-53 Rev 5 | Security and privacy controls for federal information systems. Control families: AC, AT, AU, CA, CM, CP, IA, IR, MA, MP, PE, PL, PM, PS, PT, RA, SA, SC, SI, SR |
| NIST CSF v1.1 | Five functions: GV=Govern, ID=Identify, PR=Protect, DE=Detect, RS=Respond, RC=Recover |
| ISO/IEC 27001:2022 | International ISMS standard. Clause 5–10 cover requirements; Annex A controls referenced as 5.x–8.x |
| CIS Controls v8 | 18 prioritised security controls across three implementation groups (IG1, IG2, IG3) |
| PCI DSS v4.0 | Payment Card Industry standard. Applies to any system that stores, processes, or transmits cardholder data |
| HIPAA | Health Insurance Portability and Accountability Act. 164.3xx references the Security Rule safeguards |

---

*Last updated: April 2026*
*For the full control-level mapping download the [Excel version](./policy-framework-mapping.xlsx).*
