# Access Control GRC Policy

## 1. Governance Framework
* [cite_start]**Policy Ownership:** The Information Security Committee is responsible for approval and oversight of standards[cite: 6].
* [cite_start]**Role-Based Access Control (RBAC):** Access is granted to defined Roles rather than individuals[cite: 7]. [cite_start]Roles are reviewed annually for alignment with gas and energy sector job descriptions[cite: 8].
* [cite_start]**Segregation of Duties (SoD):** No single individual shall have authority to both initiate and approve critical system changes (e.g., PLC setpoint modifications)[cite: 9].

## 2. Risk Management Integration
* [cite_start]**Asset Classification:** Assets (Servers, SCADA, Handhelds) must be classified by criticality to safety and production[cite: 12].
* **Risk-Based Authentication:**
  * [cite_start]**Low Risk:** Standard username and complex password[cite: 14].
  * [cite_start]**High Risk:** Mandatory Multi-Factor Authentication (MFA) and hardware tokens[cite: 15].
* [cite_start]**Privileged Access Management (PAM):** Administrative accounts must be tightly controlled, logged, and require a valid work order for activation[cite: 16, 17].

## 3. Compliance and Regulatory Alignment
* [cite_start]**Principle of Least Privilege:** Users receive the minimum access required for specific duties[cite: 20].
* [cite_start]**Access Reviews:** Managers must quarterly attest to team access levels[cite: 22].
* [cite_start]**Immediate Revocation:** Access disabled within 24 hours for terminations; immediately for high-risk role changes[cite: 23].
* [cite_start]**Audit Logging:** Access attempts to critical infrastructure must be logged, protected from modification, and kept for 2 years[cite: 24, 25].

## 4. Operational Technology (OT) Specific Controls
* [cite_start]**Physical-Digital Link:** Digital access is contingent upon physical site clearances and safety training certifications[cite: 28].
* [cite_start]**Remote Vendor Access:** Vendors must use a "Gateway" or "Jump Server"[cite: 29]. [cite_start]Access must be requested in advance, time-limited, and monitored by an internal technician[cite: 31, 32, 33].
