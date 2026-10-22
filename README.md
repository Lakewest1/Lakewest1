<div align="center">

# Olalekan Ismail Musa

### Cloud Security Engineer | Detection & Security Automation (AWS · Azure)

I secure cloud-connected applications and infrastructure, investigate security risks, and build automation to improve detection and response. I maintain live production platforms, build AWS and Azure security projects, and teach practical cybersecurity through Lakewest Cybersecurity Academy.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Olalekan%20Musa-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olalekan-musa-499b48280/)
[![Email](https://img.shields.io/badge/Email-olamilake95@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:olamilake95@gmail.com)

</div>

> [!NOTE]
> **Open to:** Cloud Security Engineer and Cloud Security Analyst roles, cloud detection engineering roles, security automation projects, and freelance engagements.

---

## 🛡️ Production Platforms

I built and integrated security into three live platforms and maintain them part-time (about 1–3 hours a day): checking availability, troubleshooting technical and security issues, fixing identified flaws, and implementing owner-requested updates.

| Platform | Reach | Security work |
|:--|:--|:--|
| **[EVS Healthcare](https://www.evshealthcare.co.uk)**<br>Recruitment platform with CV uploads | 10,000+ visitors<br>in ~6 weeks | Cloudflare WAF, bot and DDoS mitigation, HTTPS/TLS, security headers, input validation, secure CV upload handling, SPF/DKIM/DMARC<br>[Repository](https://github.com/Lakewest1/evs-healthcare-secure-platform) |
| **[Rasoaf Travels & Tours](https://rasoaf.com)**<br>Travel platform | 3,000+ visitors<br>in ~8 weeks | Cloudflare protections, Semgrep, Gitleaks, npm audit, OWASP ZAP, GitHub Actions security workflows<br>[Repository](https://github.com/Lakewest1/Rasoaf-Devsecops-Security-Implementation) |
| **[TV-Tay](https://tv-tay.org)**<br>Donation platform with real transactions | 5,000+ visitors<br>in ~3 months | Cloudflare WAF, bot mitigation, DDoS protection, rate limiting; application, API and AWS security for the donation workflow<br>[Repository](https://github.com/Lakewest1/multi-cloud-secure-donation-platform) |

---

## 🔍 Detection Engineering & Security Automation

> Personal projects and labs, not client deployments.

### [LOSAF: Lakewest Open Security Automation Framework](https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline)

Multi-cloud detection pipeline for AWS CloudTrail, Microsoft Entra ID, and Kubernetes audit logs.

- Normalizes events for consistent analysis
- Maps activity to MITRE ATT&CK
- Applies configurable YAML detection rules with severity and confidence scoring
- Feeds an API and a PostgreSQL/Supabase dashboard
- Generates recommended response actions

**Scope:** recommends response actions; automated remediation is not implemented. [▶ Demo walkthrough](https://youtu.be/jT9a2qFGDHg)

`TypeScript` `Node.js` `Express` `React` `PostgreSQL` `Supabase`

### [Cross-Cloud SOC Automation & Response](https://github.com/Lakewest1/Cross-Cloud-SOC-Automation-Remediation-v2)

Microsoft Sentinel alerts drive Azure Logic App workflows that call AWS Lambda over OIDC, with no long-lived credentials. Confirmed working end-to-end in lab.

| Azure | AWS |
|:--|:--|
| Sentinel and KQL for detection | Lambda (Python) for response logic |
| Logic Apps for orchestration | DynamoDB for idempotency |
| Entra ID and Graph for identity response | SES for notifications |

### Azure Logic App SOAR Playbooks

SOC Tier 3-inspired security orchestration playbooks, developed and iterated across many versions to explore investigation, threat-intelligence enrichment, and controlled response workflows.

- Integrations with Azure Key Vault, Service Bus, ServiceNow, AbuseIPDB, and VirusTotal
- Microsoft Graph API containment actions gated behind human approval

### AI Security Assistant

An AI-assisted investigation tool: an agent loop with tool calls to threat-intelligence sources (VirusTotal, AbuseIPDB) to build evidence-backed assessments of URLs and IP addresses.

### [TorExfil SOC Investigation](https://github.com/Lakewest1/TorExfil-SOC-Investigation)

Investigation of suspicious network activity and potential data exfiltration using threat-intelligence enrichment, MITRE ATT&CK mapping, and SIEM techniques.

---

## ☁️ Cloud Security & DevSecOps Projects

| Project | What it covers |
|:--|:--|
| **[AWS Security Automation](https://github.com/Lakewest1/AWS-Security-Automation)** | Python/Boto3 checks for insecure IAM, S3, EC2, KMS, and CloudTrail configurations. |
| **[Secure Kubernetes Deployment](https://github.com/Lakewest1/Secure-Kubernetes-Deployment)** | Non-root containers, RBAC, network policies, OPA Gatekeeper admission control, Trivy and Gitleaks scanning, CI/CD validation. The repo documents the environment and what was tested. |
| **[PCI-Aware Cloud Security Architecture](https://github.com/Lakewest1/PCI-Compliant-Cloud-Security-Architecture-project)** | Least-privilege IAM, encryption, key management, STRIDE threat modelling, Zero Trust. An architecture project, not a PCI DSS certification or audit. |

---

## 🧰 Skills

| Domain | Technologies |
|:--|:--|
| **AWS** | IAM, CloudTrail, KMS, Lambda, API Gateway, S3, Boto3 |
| **Azure** | Sentinel, KQL, Logic Apps, Entra ID, Key Vault |
| **Detection & Response** | SIEM investigation, detection rules, MITRE ATT&CK, alert triage, SOAR |
| **Application Security** | OWASP ZAP, Semgrep, API security, input validation, security headers |
| **Web Protection** | Cloudflare WAF, rate limiting, bot mitigation, DDoS protection, TLS |
| **DevSecOps** | GitHub Actions, Gitleaks, npm audit, Trivy, CI/CD controls |
| **Cloud-Native** | Kubernetes, container hardening, RBAC, OPA Gatekeeper |
| **Languages** | Python, TypeScript, JavaScript, Node.js |

---

## 🎓 Certifications & Education

| Credential | Year |
|:--|:--:|
| **Kubernetes and Cloud Native Associate (KCNA)** | 2026 |
| **Cisco Junior Cybersecurity Analyst Career Path** | 2025 |
| **HND, Science Laboratory Technology (Chemistry)**, Upper Credit, Yaba College of Technology | 2023 |
| Ethical Hacking training | 2024 |

**Training completed (not certifications):** AWS Cloud Practitioner learning path (AWS Skill Builder) and AWS Solutions Architect Associate preparation (Udemy).

---

## 📚 Teaching

I run **[Lakewest Cybersecurity Academy](https://payhip.com/lakewestcybersecurity)**, with hands-on material on SOC alert investigation, network analysis, and threat detection.

---

<div align="center">

**Let's connect** · [LinkedIn](https://www.linkedin.com/in/olalekan-musa-499b48280/) · [Portfolio](https://lakewest.netlify.app) · [Email](mailto:olamilake95@gmail.com)

</div>
