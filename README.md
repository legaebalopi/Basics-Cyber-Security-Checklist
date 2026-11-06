
# Basics-Cyber-Security-Checklist
A checklist that is designed to help individuals and samll organisations protect their digital information, environment and assets.
Checklist:# Basics of Cyber-Security Checklist

A comprehensive checklist designed to provide actionable security measures across various environments, demographics, and organizational structures to mitigate cyber risks.

---

## 1. 🏠 Home Users
Focuses on protecting personal devices, home networks, and personal identity.
* [ ] **Secure Your Wi-Fi Network:** Change the default router administrative credentials, use WPA3 encryption, and change the default SSID (network name).
* [ ] **Enforce Strong Password Hygiene:** Use a unique password or passphrase (minimum 12–15 characters) for every account and store them in a secure password manager.
* [ ] **Enable Multi-Factor Authentication (MFA):** Turn on MFA for all critical personal accounts, especially email, online banking, and social media.
* [ ] **Keep Software Updated:** Enable automatic updates for device operating systems (Windows, macOS, iOS, Android) and installed applications.
* [ ] **Isolate Smart Home (IoT) Devices:** Set up a separate guest network specifically for smart TVs, cameras, and IoT gadgets to isolate them from your primary computers.

---

## 2. 🏢 Small & Medium Businesses (SMBs)
Designed to safeguard company assets, customer data, and commercial networks with limited security budgets.
* [ ] **Establish Role-Based Access Control (RBAC):** Restrict employee data access based strictly on the principle of least privilege; only grant permissions required to execute their specific job function. Only give authorised people access.
* [ ] **Implement Security Awareness Training:** Conduct routine phishing checks and train employees to be aware and recognise social engineering attempts.
* [ ] **Deploy Centralized Endpoint Protection:** Install good antivirus, anti-malware, and host-based firewalls on all office machines.
* [ ] **Enforce Regular Data Backups:** Follow the 3-2-1 backup strategy (3 copies of data, across 2 different media types, with 1 copy stored securely offline/off-site). Back up data regularly inorder not to lose informarion.
* [ ] **Develop an Incident Response Policy:** Maintain a clearly documented plan detailing who to contact and what actions to take immediately following a data breach.

---

## 3. 💻 Remote Workers
Addresses the security challenges of accessing corporate resources outside the office perimeter.
* [ ] *Always Use a Secure VPN:* Mandate the use of an enterprise Virtual Private Network (VPN) when connecting to company systems over external networks.
* [ ] *Secure the Remote Workspace:* Ensure work devices are  not to be  used by family members and make  the screen to lock automatically after 2–5 minutes of inactivity.
* [ ] *Verify Home Router Security:* Confirm that the home router firmware is updated and that the remote worker's home network does not use weak default passwords.
* [ ] *Use Approved Storage and Collaboration Tools:* Sharefiles and communicate strictly through company-vetted, encrypted cloud channels rather than personal emails.
* [ ] *Shred Sensitive Physical Documents:* Utilize  a shredder to destroy any physical paper containing corporate or client data printed.

---

## 4. 📱 Mobile Users
Aims to secure smartphonesand tablets that handle sensitive personal or professional information.
* [ ] *Enforce Biometrics and Secure PINs:* Lock mobile devices using biometric authentication (FaceID/Fingerprint) paired with a complex 6-digit PIN or alphanumeric passcode.
* [ ] *Audit App Permissions:* Regularly check   app  settings and deny unnecessary access to location services, contacts, the microphone, and the camera.
* [ ] *Disable Auto-Connect Over Public Wi-Fi:* Turn off automatic wireless switching and Bluetooth discoverability to avoid connecting to rogue, unencrypted public hotspots.
* [ ] *Install a Remote Wipe Solution:* Enable  features like "Find My Device" or deploy Mobile Device Management (MDM) softare to remotely wipe data if the phone is lost or stolen.
* [ ] *Only Download  from Official Stores:* Restrict all installations to official ecosystems (Apple App Store or Google Play Store) to avoid sideloading malicious applications.

---

## 5. ☁️ Cloud Environments
Ensures cloud infrastructure, storage  buckets, and hosted web applications are properly defended.
* [ ] *Deactivate Default Public Cloud Access:* Confirm all cloud storage buckets (e.g., AWS S3, Azure Blobs) are configured to private  by default to prevent  accidental data leaks.
* [ ] *Enforce Zero-Trust Network Architecture:* Mandate  phishing-resistant hardware MFA for all administrative cloud accounts and rotate API access keys regularly.
* [ ] *Enable Continuous Cloud Logging:* Turn on  cloud trail logging and real-time monitoring to detect unauthorized configurations or anomalous file exfiltration.
* [ ] *Encrypt Data at Rest and in Transit:* Apply strong  encryption protocols (AES-256 for data at rest and TLS 1.3 for data in motion) across all cloud storage systems.
* [ ] *Perform Regular Configuration Audits:* Use  automated security tools to continuously scan cloud environments against baseline security benchmarks (like CIS Controls).....

---

## 6. 🏗️ Critical Infrastructure
Tailored for Operational Technology (OT) and systems managing utilities, transportation, and health networks.
* [ ] *Implement Strict Network Segmentation:* Physically or logically air-gap Industrial Control Systems (ICS) and SCADA networks from the standard corporate IT network.
* [ ] *Deploy Out-of-Band Management (OOBM):* Ensure critical control pathways use dedicated, non-internet-facing communication links.
* [ ] *Establish Rigorous Patch Management:* Set a strict, validated testing schedule for firmware and software updates on critical infrastructure equipment to prevent operational disruptions.
* [ ] *Maintain Strict Physical Access Controls:* Secure server rooms, control facilities, and terminal connection ports behind biometric locks, security badges, and  CCTV monitoring.
* [ ] *Plan for Offline Operational Failovers:* Maintain fully tested manual backup override systems so plants can continue basic operations even if the digital network is completely compromised.

---

## 7. 🏛️ Government Agencies
Designed to align with strict regulatory frameworks, compliance laws, and national security data handling.
* [ ] *Enforce Data Classification Controls:* Sort and label all organizational data by security clearance tier (e.g., Unclassified, Confidential, Secret) to manage access rights strictly.
* [ ] *Maintain Regulatory Compliance Standards:* Ensure all IT infrastructure fully adheres to required national standards (such as NIST frameworks, ISO 27001, or local data privacy laws).
* [ ] *Establish Third-Party Vendor Risk Management:* Vetting external software contractors and hardware suppliers through rigorous supply chain cyber evaluations before granting network integration.
* [ ] *Enforce Immutable Tamper-Evident Audit Trails:* Set up secure, centralized log aggregation that cannot be altered or deleted by any standard administrative account for forensic tracking.
* [ ] *Conduct Routine Penetration Testing:* Employ certified external ethical hackers to perform annual system vulnerability testing and black-box network security audits








