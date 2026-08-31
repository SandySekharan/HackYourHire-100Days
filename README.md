# 🗺️ Cybersecurity Interview Roadmap

This repo is to help to plan and prepare for interview ( cybersecurity, product security, ai security and cloud security). A 100 day road map for preparing an interview, for an average person with basic knowledge level and can spend 30 to 40 min for study and preparation. The key is **not to try to become an expert in 100 days**. With only 30–40 minutes, the goal should be to build **interview-ready breadth + strong fundamentals + the ability to explain concepts confidently**.

**Cybersecurity fundamentals → Product Security → Cloud Security → AI Security → Practical labs → Interview preparation**

### Your daily routine — only 30–40 minutes

Use the same structure almost every day:

* **15 min — Learn:** one small concept
* **10 min — Hands-on / example:** command, architecture, threat model, scenario
* **10 min — Interview:** answer 2–3 questions aloud
* **5 min — Revision:** write 3–5 points in your own words

Don't study for 2–3 hours occasionally. **30 minutes × 100 days = 50+ hours**, which is enough to make a significant difference if done consistently.

---

# 100-Day Cybersecurity Interview Roadmap

| Days   | Area                                    | Main Goal                               |
| ------ | --------------------------------------- | --------------------------------------- |
| 1–10   | Cybersecurity Fundamentals              | Build foundation                        |
| 11–20  | Network & Application Security          | Become comfortable with security basics |
| 21–40  | Product Security                        | Make this your strongest area           |
| 41–55  | Cloud Security                          | AWS/cloud fundamentals + security       |
| 56–70  | AI Security                             | GenAI/LLM security                      |
| 71–80  | Security Architecture & Threat Modeling | Think like a senior engineer            |
| 81–90  | Practical Security                      | Labs + real scenarios                   |
| 91–100 | Interview Mode                          | Mock interviews + revision              |

---

### 🟢 PHASE 1 — Cybersecurity Fundamentals (Days 1–10)

Don't go too deep. You need to be able to **explain the concepts clearly**.

Day 1 — CIA Triad

Day 2 — Security Controls

Day 3 — Risk

Day 4 — Vulnerabilities

Day 5 — Authentication

Day 6 — Cryptography

Day 7 — IAM

Day 8 — Logging & Monitoring

Day 9 — Incident Response

Day 10 — Revision + Mini Interview


# 🔵 PHASE 2 — Network & Application Security

## Days 11–20

This phase will be easier for you because you already have exposure to networking/security tools.

### Days 11–12 — Networking

Revise:

* TCP/IP
* TCP vs UDP
* IP
* MAC
* ARP
* DNS
* DHCP
* NAT
* Routing

Interview:

> What happens when you type google.com in your browser?

---

### Days 13–14 — Network Security

Learn:

* Firewall
* WAF
* IDS
* IPS
* VPN
* Proxy
* Network segmentation
* Zero Trust

Be able to draw:

**Internet → Firewall → DMZ → Application → Database**

---

### Days 15–16 — Ports & Protocols

Understand security implications of:

* HTTP/HTTPS
* SSH
* FTP
* DNS
* SMTP
* MQTT
* Modbus
* BACnet
* SNMP

For each:

> What is it?
> Default port?
> Security concern?

---

### Days 17–18 — OWASP

Focus on:

* Broken Access Control
* Injection
* Authentication failures
* Security misconfiguration
* Cryptographic failures
* SSRF
* Vulnerable components

Don't memorize the entire OWASP list.

Understand **why each vulnerability happens**.

---

### Day 19 — API Security

Learn:

* REST
* JWT
* API authentication
* Authorization
* Rate limiting
* Input validation
* API gateway
* BOLA/IDOR

---

### Day 20 — Mini Interview

Answer aloud:

> Explain TCP vs UDP.

> What happens during TLS?

> Firewall vs WAF?

> IDS vs IPS?

> What is Zero Trust?

> What is IDOR?

> What is SSRF?

---

# 🟠 PHASE 3 — PRODUCT SECURITY

## Days 21–40

**This should be one of your strongest sections.**

Your objective isn't just "penetration testing."

You should be able to discuss the **entire product security lifecycle**.

---

### Days 21–23 — Product Security Fundamentals

Learn:

* Product Security vs Cybersecurity
* Secure SDLC
* Security requirements
* Security architecture
* Security testing
* Vulnerability management
* Security release process

Think:

**Requirements → Design → Development → Testing → Release → Monitoring → PSIRT**

---

### Days 24–26 — Threat Modeling

Learn:

* Asset
* Entry point
* Trust boundary
* Data flow
* Threat
* Mitigation

Study:

**STRIDE**

* Spoofing
* Tampering
* Repudiation
* Information Disclosure
* Denial of Service
* Elevation of Privilege

Practice threat modeling a simple:

**Mobile App → Cloud → IoT Device**

---

### Days 27–29 — Secure Architecture

Learn:

* Defense in depth
* Least privilege
* Secure-by-design
* Fail secure
* Attack surface
* Trust boundaries
* Security zones

Interview:

> How would you design a secure IoT product?

---

### Days 30–32 — Embedded Security

Study:

* Secure boot
* Firmware signing
* Firmware encryption
* Hardware root of trust
* TPM
* HSM
* Debug interfaces
* JTAG
* UART
* OTA updates
* Anti-rollback

---

### Days 33–35 — IoT Security

Understand:

**Device → Gateway → Cloud → Mobile App**

Security issues:

* Default credentials
* Exposed services
* Insecure protocols
* Firmware vulnerabilities
* Weak authentication
* Certificate problems
* Insecure OTA
* Cloud misconfiguration

---

### Days 36–37 — Vulnerability Management

Learn:

**Discovery → Validation → Risk assessment → Remediation → Verification → Disclosure**

Understand:

* CVE
* CWE
* CVSS
* EPSS — basic
* CISA KEV — basic
* SBOM

---

### Days 38–39 — CRA / Compliance

Study high-level concepts:

* EU Cyber Resilience Act
* Vulnerability handling
* Security updates
* SBOM
* Product lifecycle
* Reporting obligations

Also understand:

* ISO 27001
* IEC 62443
* NIST CSF

Don't try to memorize standards.

Understand **why they exist and when they apply**.

---

### Day 40 — Product Security Interview

Practice answering:

> How do you perform threat modeling?

> How would you secure an IoT device?

> What is Secure Boot?

> How does OTA security work?

> What is SBOM?

> How do you prioritize vulnerabilities?

> Explain Secure SDLC.

> Product Security vs Application Security?

---

# ☁️ PHASE 4 — CLOUD SECURITY

## Days 41–55

Pick **AWS as your primary cloud**.

You don't need to learn every AWS service.

### Days 41–43 — Cloud Fundamentals

Understand:

* AWS account
* Region
* Availability Zone
* VPC
* Subnet
* Route table
* Internet Gateway
* NAT Gateway
* Security Group
* NACL

Draw the architecture yourself.

---

### Days 44–46 — IAM

Study:

* IAM users
* Roles
* Policies
* Resource policies
* AssumeRole
* Least privilege
* Access keys
* Service identities

Important interview question:

> Why are IAM roles preferred over access keys?

---

### Days 47–49 — AWS Security

Learn:

* CloudTrail
* CloudWatch
* GuardDuty
* Security Hub
* KMS
* Secrets Manager
* AWS WAF

Understand what problem each solves.

---

### Days 50–52 — Cloud Application Security

Study:

**Internet → WAF → Load Balancer → ECS/EC2 → Database**

Understand:

* Network segmentation
* Encryption
* Secrets
* IAM
* Logging
* Monitoring

---

### Days 53–54 — Container Security

Learn:

* Docker image
* Container
* Registry
* Kubernetes — basic
* Image vulnerabilities
* Secrets
* Container escape
* Runtime security

Tools:

* Trivy
* Docker Scout — basic

---

### Day 55 — Cloud Interview

Practice:

> Design a secure AWS application.

> Security Group vs NACL?

> IAM user vs role?

> What is KMS?

> How would you secure S3?

> How would you investigate a compromised AWS account?

---

# 🤖 PHASE 5 — AI SECURITY

## Days 56–70

This is increasingly important, but **don't get trapped trying to learn AI/ML mathematics**.

For security interviews, focus on **AI/LLM security**.

---

### Days 56–58 — AI Fundamentals

Understand:

* AI
* ML
* Deep Learning
* Generative AI
* LLM
* Transformer
* Training
* Inference
* Fine-tuning
* RAG
* Embeddings

You only need conceptual understanding.

---

### Days 59–61 — LLM Architecture

Understand:

**User → Application → LLM → Tools/API → Data**

Then understand:

**RAG**

**User → Application → Retriever → Vector DB → Context → LLM**

---

### Days 62–64 — OWASP LLM Security

Focus heavily on:

* Prompt Injection
* Insecure Output Handling
* Sensitive Information Disclosure
* Supply Chain
* Excessive Agency
* System Prompt Leakage
* Vector/Embedding weaknesses
* Model denial of service

---

### Days 65–67 — AI Threat Modeling

Threat model:

**User → AI Application → LLM → RAG → Database → External API**

Ask:

* Can prompt injection access data?
* Can the model call dangerous tools?
* Can users retrieve other users' documents?
* Can sensitive data reach the model?
* Can the model execute commands?
* Can an attacker poison the knowledge base?

---

### Days 68–69 — AI Security Controls

Learn:

* Input validation
* Output validation
* Guardrails
* Authorization
* Tool permissions
* Sandboxing
* Data classification
* RAG access control
* Logging
* Human approval
* Rate limiting

---

### Day 70 — AI Security Interview

Practice:

> What is prompt injection?

> Prompt injection vs jailbreak?

> How do you secure an LLM application?

> What is RAG?

> What security issues exist in RAG?

> How would you secure an AI agent?

> What is excessive agency?

---

# 🟣 PHASE 6 — Security Architecture & Threat Modeling

## Days 71–80

This is where you start thinking like a **Senior Engineer / Lead** rather than someone who only knows tools.

---

### Day 71 — Security Architecture

Learn:

**Defense in depth**

Example:

Application security
↓
API security
↓
IAM
↓
Network security
↓
Host security
↓
Data security

---

### Day 72 — Zero Trust

Understand:

> Never trust, always verify.

Learn:

* Identity
* Device
* Network
* Application
* Data

---

### Day 73 — Attack Surface

Practice identifying attack surfaces for:

**IoT product**

**Cloud application**

**AI application**

---

### Day 74 — Trust Boundaries

Draw:

**Internet → Cloud → API → Device**

Mark where trust changes.

---

### Day 75 — Threat Modeling Practice #1

Threat model:

**Smart HVAC Device**

---

### Day 76 — Threat Modeling Practice #2

Threat model:

**AWS web application**

---

### Day 77 — Threat Modeling Practice #3

Threat model:

**AI chatbot with RAG**

---

### Day 78 — Security Design Question

Question:

> Design a secure IoT system communicating with AWS.

Spend 30 minutes drawing it.

---

### Day 79 — Security Design Question

> Design a secure AI application handling confidential documents.

---

### Day 80 — Architecture Interview

Practice explaining your designs **without notes**.

---

# 🔴 PHASE 7 — PRACTICAL SECURITY

## Days 81–90

Now stop studying and start **doing**.

You don't need complicated labs.

### Day 81

Nmap:

* Host discovery
* Port scanning
* Service detection

---

### Day 82

Nessus:

Understand:

* Discovery
* Credentialed scan
* Non-credentialed scan
* Plugin
* Severity
* False positive

---

### Day 83

Burp Suite:

Practice:

* Proxy
* Repeater
* HTTP requests
* Authentication
* Authorization testing

---

### Day 84

Docker:

Build a vulnerable container and scan it with Trivy.

---

### Day 85

AWS:

Create a simple architecture diagram and identify:

* IAM
* VPC
* Security Groups
* Logs
* Encryption

---

### Day 86

Threat model your own lab.

---

### Day 87

Take one CVE.

Understand:

**Vulnerability → Root cause → Exploit → Impact → Mitigation**

---

### Day 88

Take one IoT vulnerability.

Explain it from:

**Attacker → Entry point → Vulnerability → Impact → Mitigation**

---

### Day 89

Take one AI vulnerability.

Explain prompt injection with a realistic scenario.

---

### Day 90

**Full practical interview day.**

Choose a product and answer:

> How would you assess its security?

---

# 🟡 PHASE 8 — FINAL 10 DAYS

# Interview Mode

This is extremely important.

Don't learn new topics.

---

## Day 91 — Cybersecurity Questions

Prepare answers to 20 common questions.

---

## Day 92 — Product Security Questions

Prepare 20 questions.

Especially:

* Threat modeling
* Secure SDLC
* IoT
* Vulnerability management
* Secure Boot
* OTA
* SBOM
* PSIRT

---

## Day 93 — Cloud Questions

Prepare 20 AWS security questions.

---

## Day 94 — AI Security Questions

Prepare 20 AI security questions.

---

## Day 95 — Scenario Questions

Practice:

> You discover a critical vulnerability in a released product. What do you do?

> An AWS credential is compromised. What do you do?

> An AI chatbot leaks confidential information. What do you investigate?

---

## Day 96 — Behavioral Questions

Prepare:

* Tell me about yourself.
* Biggest achievement?
* Biggest failure?
* Difficult colleague?
* Conflict with developer?
* How do you prioritize?
* Why should we hire you?
* Why are you changing jobs?

Use **STAR**:

**Situation → Task → Action → Result**

---

## Day 97 — Resume

For every important resume item, prepare:

> What did you do?

> Why did you do it?

> How did you do it?

> What tools did you use?

> What was the result?

> What was the biggest challenge?

**Never put something on your resume that you cannot explain technically.**

---

## Day 98 — Mock Interview #1

Do a complete 45–60 minute interview.

Record yourself if possible.

Look for:

* Too many "umm"
* Long answers
* Lack of structure
* Not answering the question directly
* Overclaiming knowledge

---

## Day 99 — Mock Interview #2

Focus on architecture/scenario questions.

Use this structure:

**Understand → Identify risks → Prioritize → Mitigate → Verify**

---

# 🏆 Day 100 — Final Interview

No studying.

Take 30–40 minutes and answer:

### Cybersecurity

5 questions

### Product Security

5 questions

### Cloud Security

5 questions

### AI Security

5 questions

### Architecture

2 scenarios

### Behavioral

5 questions

If you can answer these **clearly without memorization**, you're ready to start interviewing.

---

# 📚 What You Should Know at the End

Your target should look roughly like this:

```text
                    CYBERSECURITY
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
   PRODUCT             CLOUD              AI
   SECURITY           SECURITY          SECURITY
       │                 │                 │
       ├─ SSDLC          ├─ IAM            ├─ LLM
       ├─ Threat Model   ├─ VPC            ├─ RAG
       ├─ IoT            ├─ AWS            ├─ Prompt Injection
       ├─ Embedded       ├─ Containers     ├─ AI Agents
       ├─ SBOM           ├─ KMS            ├─ Data Security
       └─ PSIRT          └─ Monitoring     └─ Guardrails
                         │
                         ↓
                SECURITY ARCHITECTURE
                         │
                         ↓
                   INTERVIEW SKILLS
```

## ⭐ Golden Rule

### Your daily rule

**One concept. One example. Three interview questions.**

### And one final rule:

 **Don't just read the answer. Close the notes and explain it aloud.**

>**If you cannot explain a concept in **60–120 seconds in simple language**, you don't know it well enough for an interview yet.**

