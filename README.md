# Healthcare-Startup-Cybersecurity-Assessment-NIST-CSF-2.0-


## Introduction
This project analyzes the cybersecurity posture of a fictional mid-sized healthcare startup, **MediSure Health**, which provides digital health services through cloud-based platforms. As a HIPAA-regulated entity handling protected health information (PHI), MediSure must safeguard patient records against unauthorized access, alteration, and loss.  

Using the **NIST Cybersecurity Framework (CSF) 2.0**, I evaluated the organization's current security posture, identified deficiencies, and provided a roadmap for improvement. The assessment includes a **Current Profile**, a **Target Profile**, and a set of recommendations tailored to healthcare compliance and cloud operations.

---

## CSF Core Functions
The NIST CSF Core Functions organize cybersecurity outcomes into six areas:

- **Govern** – Define and oversee security policies and risk management.  
- **Identify** – Understand assets, risks, and business context.  
- **Protect** – Implement safeguards to ensure delivery of services.  
- **Detect** – Identify anomalies and events in a timely manner.  
- **Respond** – Take action regarding detected incidents.  
- **Recover** – Restore capabilities and services impaired due to incidents.  

---

## Current Profile (Tier 1: Partial)
MediSure currently operates at **Tier 1: Partial**, meaning cybersecurity activities are largely ad hoc. Examples include:  
- No enterprise-wide risk management framework.  
- Limited asset inventory across cloud and on-premises systems.  
- Inconsistent access control (no MFA on remote access).  
- No formal incident response plan.  
- Training is limited to onboarding, with no periodic refreshers.  

---

## Target Profile (Tier 4: Adaptive)
The desired state is **Tier 4: Adaptive**, where cybersecurity practices are fully integrated into the organization’s culture and operations. Characteristics include:  
- Risk-informed governance with board-level oversight.  
- Real-time monitoring and analytics (e.g., SIEM, anomaly detection).  
- Consistent enforcement of HIPAA-aligned policies across all environments.  
- Continuous workforce training, including executives and third parties.  
- Adaptive risk management using lessons learned and predictive intelligence.  

---

## Assessment Highlights
**Key Gaps Identified:**  
- **Asset Management:** No consistent classification of PHI vs. non-PHI data. No third-party risk management for cloud vendors.  
- **Access Control:** No MFA for staff accessing cloud dashboards. Inadequate offboarding procedures.  
- **Data Security:** No Data Loss Prevention (DLP) tools in place. No policies for secure data disposal.  
- **Governance:** No formal cybersecurity policy or HIPAA compliance officer.  
- **Incident Response:** No defined escalation process or communication plan.  

---

## Recommendations Roadmap

### Short-Term (0–6 months)
- Implement Multi-Factor Authentication (MFA) across all cloud services.  
- Develop and publish a cybersecurity and HIPAA compliance policy.  
- Establish asset inventory with PHI classification.  
- Assign a compliance officer and define security roles.  

### Mid-Term (6–18 months)
- Deploy a Security Information and Event Management (SIEM) solution.  
- Launch a workforce-wide security awareness training program.  
- Create and test an Incident Response Plan aligned with HIPAA breach notification requirements.  
- Establish third-party risk management for cloud providers.  

### Long-Term (18+ months)
- Integrate continuous monitoring with MITRE ATT&CK-aligned detection.  
- Automate vulnerability management and patching.  
- Establish a culture of continuous improvement with quarterly tabletop exercises.  
- Share threat intelligence with healthcare ISACs (Information Sharing and Analysis Centers).  

---

## Framework References
- **NIST Cybersecurity Framework (CSF) 2.0**  
- **NIST SP 800-53** (Security and Privacy Controls for Federal Information Systems)  
- **HIPAA Security Rule**  
- **MITRE ATT&CK Framework**  
- **OWASP Secure Design Principles**  

---

## Conclusion
MediSure Health’s current cybersecurity posture is insufficient for protecting sensitive patient records and meeting HIPAA requirements. By following the roadmap, the organization can evolve from an ad hoc, reactive approach to a proactive, adaptive cybersecurity culture that protects patients, complies with regulations, and sustains trust in its healthcare services.

Author: James Murray Good

