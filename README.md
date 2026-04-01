# Online Secure Bank: Secure Software Development

### 🛡️ Project Overview
This project demonstrates the implementation of an **Online Banking System** developed through a **Secure Software Development Life Cycle (S-SDLC)**. The focus is not just on functionality, but on defending against modern cyber threats using industry-standard security frameworks.

### 🔐 Security Architecture & The CIA Triad
The system is built around the three pillars of information security:
* **Confidentiality:** Sensitive data and passwords are never stored in plaintext.
* **Integrity:** Digital fingerprinting (Hashing) ensures that transaction data is not tampered with.
* **Availability:** Design patterns that ensure the banking service remains responsive under heavy load.

### 🕵️ STRIDE Threat Modeling
We performed a comprehensive security audit using the **STRIDE** model to identify and mitigate risks:
1. **Spoofing:** Mitigated via Multi-Factor Authentication (MFA).
2. **Tampering:** Prevented through SHA-256 integrity checks.
3. **Repudiation:** Addressed with secure audit logging and digital receipts.
4. **Information Disclosure:** Mitigated by encrypting sensitive database fields.
5. **Denial of Service (DoS):** Handled via input validation and resource management.
6. **Elevation of Privilege:** Controlled through strict Role-Based Access Control (RBAC).



### ⚙️ Core Security Features
* **Advanced Hashing:** Utilizes **SHA-256** for password protection, ensuring that even if the database is leaked, user credentials remain secure.
* **Unit Testing (Alloy):** Rigorous testing of the authentication module to handle edge cases, null inputs, and brute-force attempts.
* **Modular Design:** Complete separation of the Hashing Utilities, Transaction Logic, and User Interface to minimize the attack surface.

### 🛠️ Technologies Used
* **Languages:** Python / Java
* **Cryptography:** Hashlib (SHA-256 Implementation)
* **Design:** Draw.io (for DFDs and Activity Diagrams)
* **Analysis:** STRIDE Threat Modeling Framework

### 📂 Included Files
* `Online-Secure-Bank.zip`: Contains the full source code and secure utilities.
* `Report_Project_SSD.pdf`: 13-page technical report detailing the security analysis and testing results.
* `STRIDE_Analysis_Presentation.pptx`: Visual breakdown of the threat landscape and mitigations.
