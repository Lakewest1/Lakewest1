<div align="center">

# Olalekan Musa · Sir Lakewest

### Cloud Security Engineer | Detection & Security Automation (AWS · Azure)

I secure cloud-connected applications, investigate suspicious activity, and build security automation across cloud and application environments. I maintain live production platforms, build detection and investigation projects, and teach hands-on cybersecurity.

[![Portfolio](https://img.shields.io/badge/Portfolio-lakewest.netlify.app-0A66C2?style=for-the-badge&logo=netlify&logoColor=white)](https://lakewest.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Olalekan%20Musa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olalekan-musa-499b48280/)
[![Email](https://img.shields.io/badge/Email-olamilake95@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:olamilake95@gmail.com)

</div>

> [!NOTE]
> **Open to:** Cloud Security Engineer and Cloud Security Analyst roles, cloud detection engineering roles, security automation projects, and freelance engagements.

| | |
|:--|:--|
| ☁️ **Cloud** | AWS, Microsoft Azure |
| 🔍 **Detection & investigation** | MITRE ATT&CK, SIEM, threat hunting, network forensics |
| 🛡️ **Security engineering** | Application security, DevSecOps, Kubernetes, WAF |
| ⚙️ **Automation** | Python, TypeScript, Node.js, REST APIs, CI/CD |

---

## 🚀 Production Platforms

I built and integrated security into three live platforms and maintain them part-time (about 1–3 hours a day): checking availability, troubleshooting technical and security issues, fixing identified flaws, and implementing owner-requested updates.

| Platform | Reach | Security work |
|:--|:--|:--|
| **[EVS Healthcare](https://www.evshealthcare.co.uk)**<br>Recruitment platform with CV uploads | 10,000+ visitors<br>in ~6 weeks | Cloudflare WAF, bot and DDoS mitigation, HTTPS/TLS, security headers, input validation, secure CV upload handling, SPF/DKIM/DMARC<br>[Repository](https://github.com/Lakewest1/evs-healthcare-secure-platform) |
| **[Rasoaf Travels & Tours](https://rasoaf.com)**<br>Travel platform | 3,000+ visitors<br>in ~8 weeks | Cloudflare protections, security headers and TLS, Semgrep, Gitleaks, npm audit, OWASP ZAP, GitHub Actions security workflows<br>[Repository](https://github.com/Lakewest1/Rasoaf-Devsecops-Security-Implementation) |
| **[TV-Tay](https://tv-tay.org)**<br>Donation platform with real transactions | 5,000+ visitors<br>in ~3 months | Cloudflare WAF, bot mitigation, DDoS protection, rate limiting; application, API and AWS security for the donation workflow<br>[Repository](https://github.com/Lakewest1/multi-cloud-secure-donation-platform) |

---

## 🔎 Detection Engineering & Security Automation

> Personal projects and labs, not client deployments.

### [LOSAF: Lakewest Open Security Automation Framework](https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline)

A multi-cloud detection pipeline that brings cloud and Kubernetes audit data into one investigation workflow.

- Ingests and normalizes events from AWS CloudTrail, Microsoft Entra ID, and Kubernetes audit logs
- Maps activity to MITRE ATT&CK
- Applies configurable YAML detection rules with severity and confidence scoring
- Exposes results through an API and a PostgreSQL/Supabase dashboard
- Generates recommended response actions

**Scope:** produces recommendations only; automated remediation is not implemented. [▶ Demo walkthrough](https://youtu.be/jT9a2qFGDHg)

`TypeScript` `Node.js` `Express` `React` `AWS SDK` `Azure Identity` `PostgreSQL` `Supabase`

### [Cross-Cloud SOC Automation & Response](https://github.com/Lakewest1/Cross-Cloud-SOC-Automation-Remediation-v2)

Microsoft Sentinel alerts drive Azure Logic App workflows that call AWS Lambda over OIDC, with no long-lived credentials. Confirmed working end-to-end in lab.

| Azure | AWS |
|:--|:--|
| Sentinel and KQL for detection | Lambda (Python) for response logic |
| Logic Apps for orchestration | DynamoDB for idempotency |
| Entra ID and Graph for identity response | SES for notifications |

### Azure Logic App SOAR Playbooks

SOC Tier 3-inspired orchestration playbooks, iterated across many versions to explore alert enrichment, investigation, and controlled response.

- Threat-intelligence enrichment with VirusTotal and AbuseIPDB
- Integrations with Azure Key Vault, Service Bus, and ServiceNow
- Approval gates before sensitive identity-containment actions

### AI Security Assistant

An AI-assisted investigation tool for URLs and IP addresses: an agent loop with tool calls to VirusTotal and AbuseIPDB that returns structured, evidence-backed assessments for analyst review.

---

## 🕵️ Investigation & Network Forensics

### [Network Forensic Investigation: PCAP Analysis](https://github.com/Lakewest1/Network-Forensic-Project)

Investigation of packet-capture evidence from a controlled lab, reconstructing a multi-stage attack. [▶ Video walkthrough](https://www.youtube.com/watch?v=DKyiUF0_3K0)

- Analysed HTTP, TCP, DNS, and SSH traffic in Wireshark
- Identified reconnaissance, SQL injection attempts, webshell upload, reverse-shell execution, and attempted unauthorised SSH access
- Extracted IOCs, built an event timeline, and mapped techniques to MITRE ATT&CK
- Documented evidence, methodology, and findings in a forensic report

`Wireshark` `Gobuster` `SQLMap` `SHA-256` `IOC extraction` `MITRE ATT&CK`

### [TorExfil SOC Investigation](https://github.com/Lakewest1/TorExfil-SOC-Investigation)

Investigation of suspicious network activity and potential data exfiltration, using threat-intelligence enrichment, SIEM techniques, and MITRE ATT&CK mapping.

### [Phishing Campaign Simulation: GoPhish & Postfix](https://github.com/Lakewest1/Phishing-campaign)

Educational lab exploring phishing campaign configuration and email delivery. Not an authorised engagement with any organization. [▶ Video demonstration](https://youtu.be/e2-R2_xyk54)

---

## ☁️ Cloud Security & DevSecOps Projects

| Project | What it covers |
|:--|:--|
| **[AWS Security Automation](https://github.com/Lakewest1/AWS-Security-Automation)** | Python/Boto3 checks for insecure IAM, S3, EC2, KMS, and CloudTrail configurations. |
| **[Secure Kubernetes Deployment](https://github.com/Lakewest1/Secure-Kubernetes-Deployment)** | Non-root containers, RBAC, network policies, OPA Gatekeeper admission control, Trivy and Gitleaks scanning, CI/CD validation. |
| **[PCI-Aware Cloud Security Architecture](https://github.com/Lakewest1/PCI-Compliant-Cloud-Security-Architecture-project)** | Least-privilege IAM, encryption and key management, STRIDE threat modelling, Zero Trust. An architecture project, not a PCI DSS certification or audit. |

---

## 🧰 Skills

| Domain | Technologies |
|:--|:--|
| **Cloud security** | AWS (IAM, CloudTrail, KMS, Lambda, API Gateway, S3, Boto3), Azure (Sentinel, KQL, Logic Apps, Entra ID, Key Vault) |
| **Detection & investigation** | Detection rules, MITRE ATT&CK, alert triage, log analysis, IOC extraction, timeline reconstruction |
| **Network forensics** | Wireshark, PCAP analysis, HTTP, TCP, DNS, SSH |
| **Threat intelligence** | VirusTotal, AbuseIPDB, URL and IP reputation analysis |
| **Application security** | OWASP ZAP, Semgrep, API security, input validation, security headers |
| **Web protection** | Cloudflare WAF, rate limiting, bot mitigation, DDoS protection, TLS |
| **DevSecOps** | GitHub Actions, Gitleaks, npm audit, Trivy, CI/CD controls |
| **Cloud-native** | Kubernetes, container hardening, RBAC, NetworkPolicy, OPA Gatekeeper |
| **Automation** | Python, TypeScript, Node.js, REST APIs, OIDC |
| **Threat modelling** | STRIDE, attack-chain analysis |

---

## 🎓 Certifications & Education

| Credential | Year |
|:--|:--:|
| **Kubernetes and Cloud Native Associate (KCNA)** | 2026 |
| **Cisco Junior Cybersecurity Analyst Career Path** | 2025 |
| **HND, Science Laboratory Technology (Chemistry)**, Upper Credit, Yaba College of Technology | 2023 |
| Ethical Hacking training | 2024 |

**Training completed (not certifications):** AWS Cloud Practitioner learning path (AWS Skill Builder, 2025) and AWS Solutions Architect Associate preparation (Udemy).

---

## 👨‍🏫 Teaching

I run **[Lakewest Cybersecurity Academy](https://payhip.com/lakewestcybersecurity)**, creating hands-on resources on SOC alert investigation, network forensics with Wireshark, and threat detection and incident-investigation methodology.

---

<div align="center">

**Let's connect** · [Portfolio](https://lakewest.netlify.app) · [GitHub](https://github.com/Lakewest1) · [LinkedIn](https://www.linkedin.com/in/olalekan-musa-499b48280/) · [Email](mailto:olamilake95@gmail.com)

</div>
