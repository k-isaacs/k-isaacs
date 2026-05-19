# 🛡️ Keisha Isaacs | Vulnerability Management Analyst | Azure Security

I work hands-on in vulnerability management and system hardening across Azure environments, with a focus on identifying findings, remediating them, validating fixes, and documenting results clearly. My work uses Tenable, PowerShell, DISA STIGs, Microsoft Defender for Endpoint, and KQL to reduce risk and improve system security. I completed full-lifecycle remediation on a live Azure VM, reducing total vulnerabilities by 83% and eliminating all Critical and High findings. I also build script-based hardening with scan-backed evidence, and most recently developed a Python-based agent that ranks vulnerability findings based on organizational context.

---

## ⚠️ Vulnerability Management Projects

- **[End-to-End Vulnerability Remediation in Azure](https://github.com/k-isaacs/End-to-End-Vulnerability-Remediation-in-Azure-Production-Environment)**  
  Completed full-lifecycle vulnerability remediation on a live Azure VM, including governance, policy sign-off, credentialed Tenable scanning, PowerShell remediation, validation, and CAB approval. Reduced total vulnerabilities by **83%** and eliminated all **Critical** and **High** findings.

- **[Windows 11 STIG Hardening | DISA v2r6](https://github.com/k-isaacs/Windows11-STIG-Remediations)**  
  Remediated 10 Windows 11 STIG controls on an Azure VM using PowerShell and registry-level changes. Each control includes the fix, implementation details, and before-and-after Tenable scan evidence.

---

## 🔍 Security Projects

- **[TOR Usage Threat Hunt | Microsoft Defender for Endpoint & KQL](https://github.com/k-isaacs/TOR-Browser-Threat-Hunt)**  
  Conducted a threat hunt in Microsoft Defender for Endpoint using KQL to detect unauthorized TOR Browser installation and usage. Reviewed file, process, and network telemetry to identify TOR-related artifacts, silent installer execution, browser launch activity, and network connections over known TOR-associated ports.

---

## 🤖 Agentic Vulnerability Management Projects

- **[VM Risk Agent | Python + Anthropic API](https://github.com/k-isaacs/VM-Risk-Agent)**  
  Built a Python-based vulnerability management agent that takes a Tenable scan and an analyst interview, then ranks findings by what the organization needs to fix first. The rubric weighs CVSS against data sensitivity, asset criticality, defense maturity, and regulatory pressure, producing different priority lists for different organizational profiles. Validated against four scenarios (hospital, SaaS startup, clinic, mom-and-pop tax/bookeeping shop) using the same scan.

---

## 🛠️ Technical Stack

- **Cloud & Identity:** Microsoft Azure, Azure Virtual Machines, Entra ID  
- **Vulnerability Management:** Tenable Nessus, DISA STIGs, Remediation Validation  
- **Security Tooling:** Microsoft Defender for Endpoint, Microsoft Sentinel, KQL  
- **Automation:** PowerShell, Python, Anthropic API 

---

## 📫 Connect

- [LinkedIn](YOUR-LINKEDIN-URL)
