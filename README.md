````markdown
### 👋 Musa Olalekan Ismail — Cloud Security & DevSecOps Engineer

# 🔐 Cloud Security Engineer | DevSecOps Engineer | Detection Engineer | SOC / Security Engineer

I specialize in AWS, Azure, Cloudflare, Kubernetes security, IAM, threat detection, security automation, and secure cloud-native application development.

I build security into systems from design → development → CI/CD → deployment → detection → response, with a strong focus on practical security engineering and automation.

---

## 🛡️ What I Do

- Design and secure **cloud-native, containerized, and serverless applications**
- Implement **AWS and Azure security controls**
- Design **IAM least-privilege architectures**
- Secure Kubernetes workloads using **RBAC, Network Policies, and SecurityContext**
- Build **DevSecOps CI/CD security pipelines**
- Perform **SAST, DAST, SCA, and secret detection**
- Conduct **threat modeling using STRIDE**
- Build **cloud threat detection and response automation**
- Develop **MITRE ATT&CK-aligned detection logic**
- Perform security investigations and incident response
- Implement **Cloudflare WAF, DDoS protection, TLS, and security headers**
- Design **compliance-aware architectures** aligned with PCI DSS and GDPR

---

# 🚀 Engineering Impact

Some of my security engineering work includes:

- 🔐 Secured a **production-grade payment/donation platform** handling real transactions
- 🛡️ Blocked **1,200+ attacks** through layered cloud security controls
- ⚡ Achieved **99.9% uptime** in the production platform
- 💰 Reduced security tooling costs by approximately **$11,000/year**
- 🤖 Built **cross-cloud security detection and automated remediation**
- ☁️ Integrated security workflows across **AWS + Azure**
- 🚨 Built **multi-cloud threat detection pipelines** with MITRE ATT&CK mapping
- 🔄 Implemented DevSecOps workflows following:

```text
Code
 ↓
Build
 ↓
Test
 ↓
SAST / SCA / Secret Scan
 ↓
DAST
 ↓
Security Gate
 ↓
Deploy
 ↓
Monitor
 ↓
Detect
 ↓
Respond
````

---

# 🔥 Featured Security Projects

## 🧠 LOSAF - Lakewest Open Security Automation Framework

### [LOSAF Multi-Cloud Detection Pipeline](https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline)

An open-source **multi-cloud threat detection pipeline** designed to ingest security telemetry from AWS, Azure, and Kubernetes, normalize events, map them to MITRE ATT&CK techniques, evaluate declarative detection rules, and surface detections through a real-time dashboard.

### Architecture

```text
AWS CloudTrail
       │
Azure Entra ID
       │
Kubernetes Audit Logs
       │
       ▼
┌─────────────────────┐
│ Multi-Cloud         │
│ Collectors          │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Event Normalization │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ MITRE ATT&CK Mapper │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Detection Engine    │
│ YAML Detection      │
│ Rules               │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ REST Detection API  │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Real-Time Dashboard │
└─────────────────────┘
```

### Key Capabilities

* Multi-cloud telemetry collection

  * AWS CloudTrail
  * Azure Entra ID
  * Kubernetes audit logs
* Common event normalization
* MITRE ATT&CK technique and tactic mapping
* Declarative YAML detection rules
* Weighted detection conditions
* Threat severity evaluation
* Recommended response actions
* Real-time detection dashboard
* PostgreSQL/Supabase persistence
* REST API for detection results
* Cloud-native security architecture

### Detection Engineering

LOSAF evaluates normalized events against declarative detection rules and produces:

* Detection severity
* Matched conditions
* Detection weight
* MITRE ATT&CK context
* Recommended response action
* High-confidence response classification

Example recommended actions include:

```text
TERMINATE_POD
REVOKE_CREDENTIALS
CONTAIN_ACTOR
```

### Current Security Scope

The current implementation **computes and recommends response actions** but does not yet directly execute remediation against AWS IAM, Kubernetes, or Microsoft Graph APIs.

This separation provides a controlled architecture where detection logic can be validated before automated remediation is introduced.

### Technology

* TypeScript
* Node.js
* Express
* React
* Vite
* PostgreSQL
* Supabase
* Prisma
* AWS SDK
* Azure Identity
* Kubernetes Client
* YAML detection rules
* MITRE ATT&CK

📂 **Repository:**
[https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline](https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline)

🎥 **Demo:**
[https://youtu.be/jT9a2qFGDHg](https://youtu.be/jT9a2qFGDHg)

---

# ☸️ Secure Kubernetes DevSecOps Deployment

### [Secure Kubernetes Deployment](https://github.com/Lakewest1/Secure-Kubernetes-Deployment)

Built and deployed a hardened containerized application on Kubernetes with security integrated throughout the development lifecycle.

### Security Controls

* Trivy container image scanning
* Snyk vulnerability validation
* Vulnerability remediation
* Kubernetes RBAC
* Network Policies
* SecurityContext
* Non-root containers
* Container hardening
* DevSecOps security workflow

### Security Workflow

```text
Application
     ↓
Container Build
     ↓
Trivy Scan
     ↓
Vulnerability Remediation
     ↓
Snyk Validation
     ↓
Kubernetes Deployment
     ↓
RBAC + Network Policies
     ↓
Runtime Hardening
```

Demonstrates that Kubernetes security is not simply about deployment, but about **secure deployment and continuous validation**.

---

# 🔐 PCI-Compliant Cloud Security Architecture

### [PCI-Compliant Cloud Security Architecture](https://github.com/Lakewest1/PCI-Compliant-Cloud-Security-Architecture-project)

Enterprise-style cloud security architecture designed around protecting sensitive payment and personal data.

### Security Controls

* AWS IAM least privilege
* AWS KMS encryption
* TLS 1.3
* mTLS
* JWT authentication
* Cloudflare WAF
* Zero Trust architecture
* Threat modeling using STRIDE
* Tokenization
* Security monitoring
* PCI DSS alignment

The project demonstrates security architecture and defense-in-depth principles for cloud-based applications.

---

# 💳 Multi-Cloud Secure Donation Platform

### [Multi-Cloud Secure Donation Platform](https://github.com/Lakewest1/multi-cloud-secure-donation-platform)

Production-grade serverless payment/donation platform secured using AWS and Cloudflare security controls.

### Architecture

```text
Users
  │
  ▼
Cloudflare
  │
  ├── WAF
  ├── DDoS Protection
  ├── Bot Protection
  └── TLS
  │
  ▼
API Gateway
  │
  ▼
AWS Lambda
  │
  ├── IAM
  ├── KMS
  └── Security Controls
  │
  ▼
Payment Services
```

### Security Outcomes

* **0 reported security incidents**
* **99.9% uptime**
* **1,200+ attacks blocked**
* Approximately **$11,000/year tooling savings**
* PCI DSS and GDPR-aware security architecture

---

# 🤖 AWS Security Automation & CIS Audit Tool

### [AWS Security Automation](https://github.com/Lakewest1/AWS-Security-Automation)

Python-based AWS security automation framework using **Boto3**.

### Capabilities

* IAM security assessment
* S3 security checks
* EC2 security checks
* CloudTrail validation
* KMS security checks
* CIS benchmark-oriented assessments
* Security posture reporting
* Cloud security automation

Demonstrates practical experience with **Python-based cloud security automation and governance**.

---

# 🚨 Cross-Cloud SOC Auto-Remediation

### [Cross-Cloud SOC Automation & Remediation](https://github.com/Lakewest1/Cross-Cloud-SOC-Automation-Remediation-v2)

Built a cross-cloud security detection and response architecture integrating **Microsoft Sentinel and AWS serverless services**.

### Architecture

```text
AWS CloudTrail
      │
      ▼
Microsoft Sentinel
      │
      ▼
Detection / KQL
      │
      ▼
SOAR Workflow
      │
      ▼
AWS Lambda
      │
      ▼
Automated Response
```

### Capabilities

* Microsoft Sentinel SIEM
* KQL detection rules
* MITRE ATT&CK mapping
* AWS Lambda automation
* Cross-cloud response
* Security incident investigation
* Automated containment
* SOC workflow automation

Demonstrates the combination of **detection engineering, cloud security, and automated response**.

---

# 🕵️ TorExfil SOC Investigation

### [TorExfil SOC Investigation](https://github.com/Lakewest1/TorExfil-SOC-Investigation)

End-to-end SOC investigation demonstrating threat detection, investigation, and incident response.

### Investigated

* Tor-based traffic
* Potential data exfiltration
* DDoS indicators
* Phishing artifacts
* Suspicious infrastructure

### Frameworks & Tools

* Microsoft Sentinel
* KQL
* MITRE ATT&CK
* NIST SP 800-61
* VirusTotal
* Shodan
* IPinfo
* ViewDNS
* SecurityTrails
* Censys

Demonstrates practical **SOC investigation, threat intelligence, and incident response** capabilities.

---

# 🔒 Rasoaf Travels & Tours - DevSecOps Security Implementation

### [Rasoaf DevSecOps Security Implementation](https://github.com/Lakewest1/Rasoaf-Devsecops-Security-Implementation)

Security implementation for a production web platform demonstrating the integration of security into the software development lifecycle.

### DevSecOps Pipeline

```text
Developer Push
      │
      ▼
GitHub Actions
      │
      ├── Build
      ├── Automated Tests
      ├── ESLint
      ├── npm audit
      ├── Gitleaks
      ├── Semgrep SAST
      ├── Security Headers
      ├── OWASP ZAP
      │
      ▼
 Security Gate
      │
   ┌──┴──┐
   │     │
 FAIL   PASS
   │     │
 STOP   Deploy
          │
          ▼
       Monitor
```

### Security Controls

* GitHub Actions CI/CD
* SAST
* DAST
* Software Composition Analysis
* Secret detection
* Automated testing
* Security headers
* Cloudflare WAF
* TLS / HSTS
* OWASP ZAP
* Semgrep
* Gitleaks
* npm audit
* ESLint
* Automated security gates

This project demonstrates practical **DevSecOps implementation in a production web application**.

---

# 🏥 EVS Healthcare Secure Platform

### [EVS Healthcare Secure Platform](https://github.com/Lakewest1/evs-healthcare-secure-platform)

A production healthcare recruitment platform designed and secured using **cloud-native security and defense-in-depth principles**.

The platform enables healthcare professionals to apply for opportunities, securely upload CVs, and communicate with recruiters while protecting application data through layered security controls.

### Architecture

```text
Users
  │
  ▼
Cloudflare Edge Security
  │
  ├── WAF
  ├── DDoS Protection
  ├── Bot Protection
  ├── Rate Limiting
  └── HTTPS / TLS
  │
  ▼
Netlify
  │
  ├── React Application
  │
  └── Netlify Serverless Functions
          │
          ├── Input Validation
          ├── Secure Form Processing
          ├── Secret Management
          │
          ├───────────────┐
          ▼               ▼
     Cloudinary         EmailJS
     CV Storage       Email Delivery
          │               │
          ▼               ▼
     Recruiter        Applicant
     Workflow        Confirmation
```

### Security Controls

#### Edge Security

* Cloudflare WAF
* DDoS Protection
* Bot Protection
* Rate Limiting

#### Transport Security

* HTTPS
* TLS 1.2 / TLS 1.3
* HSTS

#### Application Security

* Content Security Policy (CSP)
* X-Frame-Options
* X-Content-Type-Options
* Permissions Policy
* Input Validation

#### Backend Security

* Netlify Serverless Functions
* Environment-variable secret management
* Secure form processing
* Serverless isolation

#### File & Communication Security

* Secure CV/file upload handling
* Cloudinary secure CV storage
* Email delivery through EmailJS
* SPF
* DKIM
* DMARC

### Security Testing

The production platform was validated using:

| Tool                    | Purpose                         |
| ----------------------- | ------------------------------- |
| **OWASP ZAP**           | Vulnerability assessment        |
| **SSL Labs**            | TLS configuration testing       |
| **Mozilla Observatory** | Security-header assessment      |
| **SecurityHeaders.com** | HTTP security-header validation |

### Technology

* React
* Vite
* JavaScript
* Node.js
* Netlify Functions
* Cloudflare
* Cloudinary
* EmailJS
* Git
* GitHub
* OWASP ZAP
* SSL Labs

### Engineering Focus

This project demonstrates practical experience in:

* Cloud Security
* Application Security
* Serverless Security
* Secure File Uploads
* Web Security
* Security Headers
* Edge Security
* Production Deployment
* Defense-in-Depth
* Security Testing

📂 **Repository:**
[https://github.com/Lakewest1/evs-healthcare-secure-platform](https://github.com/Lakewest1/evs-healthcare-secure-platform)

🌐 **Live Platform:**
[https://www.evshealthcare.co.uk](https://www.evshealthcare.co.uk)

---

# 🧠 My Engineering Approach

> **I don't just deploy applications. I secure, validate, detect, and continuously improve them.**

My security engineering approach follows:

```text
Identify
   ↓
Threat Model
   ↓
Secure Design
   ↓
Implement
   ↓
Scan
   ↓
Test
   ↓
Deploy
   ↓
Monitor
   ↓
Detect
   ↓
Respond
   ↓
Improve
```

I focus on building security into the system rather than treating security as a final-stage activity.

---

# 🧰 Core Security Skills

### ☁️ Cloud Security

* AWS
* Azure
* Cloudflare
* IAM
* KMS
* CloudTrail
* API Gateway
* Lambda
* S3
* Microsoft Sentinel

### 🔐 Application Security

* Threat Modeling
* STRIDE
* OWASP
* SAST
* DAST
* SCA
* Secret Detection
* Security Headers
* TLS / HSTS
* Secure SDLC

### ☸️ Kubernetes Security

* RBAC
* Network Policies
* SecurityContext
* Container Hardening
* Trivy
* Snyk
* Kubernetes Audit Logs

### 🚨 Detection & Response

* Microsoft Sentinel
* KQL
* MITRE ATT&CK
* Detection Engineering
* Incident Response
* SOC Investigation
* Security Automation
* SOAR

### ⚙️ DevSecOps

* GitHub Actions
* CI/CD Security
* Semgrep
* Gitleaks
* npm audit
* OWASP ZAP
* Automated Security Gates
* Vulnerability Management

### 💻 Development

* Python
* TypeScript
* JavaScript
* Node.js
* React
* Express
* PostgreSQL
* Prisma

---

# 🌱 Currently Focused On

* Advanced Kubernetes Security
* Cloud Security Engineering
* DevSecOps and CI/CD Security
* Detection Engineering
* Cloud Threat Detection
* Security Automation
* Multi-Cloud Security Architecture
* Incident Response

---

# 🤝 Open To

* Cloud Security Engineer roles
* DevSecOps Engineer roles
* Detection Engineer roles
* SOC / Security Engineering roles
* Cloud Security Architecture opportunities
* Security automation projects
* Cloud and application security collaborations

---

# 📫 Contact

📧 **Email:**
[olamilake95@gmail.com](mailto:olamilake95@gmail.com)

🔗 **LinkedIn:**
[https://www.linkedin.com/in/olalekan-musa-499b48280/](https://www.linkedin.com/in/olalekan-musa-499b48280/)

🐙 **GitHub:**
[https://github.com/Lakewest1](https://github.com/Lakewest1)

🌐 **Portfolio:**
[https://lakewest.netlify.app/](https://lakewest.netlify.app/)

---

# ⭐ Featured Repositories

The projects I recommend reviewing first:

1. 🧠 **[LOSAF — Multi-Cloud Detection Pipeline](https://github.com/Lakewest1/LOSAF-multi-cloud-detection-pipeline)**
2. 🚨 **[Cross-Cloud SOC Automation & Remediation](https://github.com/Lakewest1/Cross-Cloud-SOC-Automation-Remediation-v2)**
3. ☸️ **[Secure Kubernetes DevSecOps Deployment](https://github.com/Lakewest1/Secure-Kubernetes-Deployment)**
4. 🔐 **[PCI-Compliant Cloud Security Architecture](https://github.com/Lakewest1/PCI-Compliant-Cloud-Security-Architecture-project)**
5. 💳 **[Multi-Cloud Secure Donation Platform](https://github.com/Lakewest1/multi-cloud-secure-donation-platform)**
6. 🔒 **[Rasoaf DevSecOps Security Implementation](https://github.com/Lakewest1/Rasoaf-Devsecops-Security-Implementation)**

---

## ⚡ Final Note

I enjoy researching complex security problems, building practical security automation, investigating threats, and designing systems where **security is engineered into the architecture from the beginning**.

> **Build it. Secure it. Detect it. Automate it.**

```

