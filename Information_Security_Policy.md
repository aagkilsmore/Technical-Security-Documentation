# Information Security Policy (ISP)

## 1. Purpose
This policy establishes a framework for protecting the confidentiality, integrity, and availability of Information and Operational Technology assets. It ensures the safe delivery of energy services while protecting personnel, the environment, and the company's reputation.

## 2. Scope
This policy applies to:
* All employees, contractors, and third-party vendors.
* All corporate IT systems (email, ERP, cloud storage).
* All Operational Technology (OT) systems (SCADA, PLC, DCS) used in upstream, midstream, or downstream operations.

## 3. Core Security Principles
| Principle | Oil & Gas Context |
| :--- | :--- |
| **Safety First** | Cybersecurity measures must never compromise Personnel or Process Safety (QHSE). |
| **Defense in Depth** | Multiple layers of security controls across both physical and digital perimeters. |
| **Asset Integrity** | Ensuring that sensor data and valve controls are accurate and tamper-proof. |
| **Resiliency** | The ability to maintain or quickly restore production during a security event. |

## 4. Network Segmentation (The Purdue Model)
The organization shall maintain strict logical and physical separation between the Corporate Office Network and the Field Production Network.
* **Air Gapping/DMZ:** A Demilitarized Zone (DMZ) must exist between IT and OT environments.
* **Access Control:** No direct "peer-to-peer" connection is allowed from the internet to a PLC or SCADA controller.

## 5. Access Management
* **Identity Verification:** Multi-Factor Authentication (MFA) is mandatory for remote access to the corporate network and strictly required for any access into the OT environment.
* **Least Privilege:** Access is granted based on the minimum level required to perform a job function.
* **Termination:** Access must be revoked within 24 hours of personnel offboarding or contract completion.

## 6. Physical Security
* Unauthorized physical access to server rooms or field control cabins is prohibited.
* All ports on networking equipment in the field must be physically locked or disabled when not in use.
* Use of unauthorized USB drives in field equipment is strictly forbidden.

## 7. Vulnerability & Patch Management
* **IT Systems:** Security patches must be applied monthly.
* **OT Systems:** Patches must be tested in a sandbox environment and deployed during scheduled maintenance windows or "turnarounds," unless a critical vulnerability poses an immediate threat to safety.

## 8. Incident Response and Recovery
The organization shall maintain a specific Cybersecurity Incident Response Plan (CIRP) integrated with the existing Emergency Response Plan (ERP).
* **Reporting:** All suspected breaches must be reported to the SOC immediately.
* **Backups:** Offline, immutable backups of critical systems must be maintained against ransomware.

## 9. Compliance and Standards
This policy aligns with:
* **ISO/IEC 27001:** Information Security Management.
* **IEC 62443:** Security for Industrial Automation and Control Systems.
* **NIST Cybersecurity Framework (CSF):** For critical infrastructure protection.
