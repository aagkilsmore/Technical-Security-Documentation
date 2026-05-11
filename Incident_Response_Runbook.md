# Incident Response Runbook: Oil & Gas Operations

## Phase 1: Detection and Identification
[cite_start]Determine if an event is a routine glitch or a malicious incident[cite: 76].
* [cite_start]**Triggers:** Unexpected SCADA shutdowns, ghost commands, unusual outbound traffic, or ransomware notes[cite: 78, 79, 80].
* [cite_start]**Verification:** Cross-reference digital alerts with physical instrumentation and confirm local maintenance activity[cite: 82, 83].

## Phase 2: Activation and Mobilization
[cite_start]Activate the Cyber-Incident Response Team (CIRT)[cite: 85].
* [cite_start]**Roles:** Incident Commander (Lead), OT Specialist (Safety/Safe State), IT Lead (Forensics), HSSE Liaison (Regulatory/Safety)[cite: 87, 88, 89, 90].
* [cite_start]**Communication:** Use clean, out-of-band channels like encrypted messaging or satellite phones[cite: 91].

## Phase 3: Containment (Isolation)
[cite_start]**Priority: Safety over Data**[cite: 93].
* [cite_start]**Logical Isolation:** Disconnect the DMZ and disable all remote VPN/vendor access[cite: 96, 97].
* **Physical Safety:** OT lead decides if an Emergency Shutdown (ESD) is required. [cite_start]Deploy personnel for manual control of valves/breakers[cite: 99, 100].

## Phase 4: Eradication and Neutralization
* [cite_start]**Identify Patient Zero:** Trace entry points like phished laptops or vendor portals[cite: 103].
* [cite_start]**Cleanup:** Re-image infected workstations and force company-wide credential resets, specifically for PLC programming[cite: 104, 105].

## Phase 5: Recovery and Restoration
* [cite_start]**Safety Check:** Verify Safety Integrity Systems (SIS) function[cite: 108].
* [cite_start]**Restoration:** Use offline "Golden Image" backups for PLCs and HMIs[cite: 109].
* [cite_start]**Validation:** Reconnect segments gradually and physically walk the plant to verify digital readings[cite: 110, 111].

## Phase 6: Post-Incident Activity
* [cite_start]**Notification:** Report to energy regulators and environmental agencies[cite: 113].
* [cite_start]**Retention:** Preserve logs and hardware for forensics[cite: 114].
* [cite_start]**Analysis:** Review network segmentation and safety system performance[cite: 116, 117].

> [cite_start]**CRITICAL WARNING:** Never patch a live control system during an active incident without a verified safety plan; doing so may trigger process failures or explosions[cite: 121].
