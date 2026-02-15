# 🛡️ Identity and Data Protection Protocol (For Technical Tools)

This instruction is mandatory for all side tools (such as upload portals) and senior project maintainers.

### 1. Zero-Log Policy
* **Prohibited Data:** Storing IP addresses, browser User-Agents, exact timestamps of uploads, and any tracking cookies is strictly prohibited.
* **Temporary Processing:** Files must be processed in temporary memory (RAM). After scanning and stripping metadata, they are moved to the final repository.

### 2. Open Audit (Code Transparency)
* All infrastructure-related code must be placed in the project repository.
* Security experts must be able to verify the metadata removal and zero-logging processes within the source code.

### 3. Secure Repository Management
* **Anonymous Accounts:** For project management, never use a GitHub account created with your personal email or phone number. Study the **[Anonymous Account Setup Guide](./anonymous-github-setup.md)** for a step-by-step tutorial.
* **Secure Browsing:** All administrative access to GitHub must be conducted via Tor or reliable VPNs (with no DNS leaks).

---
[🛡️ Security Overview](./README.md) | [⬅️ Back to Help Center](../README.md) | [⬅️ Back to Home](../../README.md)
