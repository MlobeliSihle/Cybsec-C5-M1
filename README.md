# 🔐 Understanding Risks, Threats, and Vulnerabilities

In cybersecurity, addressing incidents effectively requires **clear communication**, **precise definitions**, and **team coordination**. This guide covers three foundational concepts in security: **risks**, **threats**, and **vulnerabilities** — and how they relate to one another in planning and response.

---

## 🛡️ Key Definitions

| Term          | Definition                                                                 |
|---------------|----------------------------------------------------------------------------|
| **Risk**      | Anything that can impact the confidentiality, integrity, or availability of an asset. |
| **Threat**    | Any circumstance or event that can negatively impact assets.               |
| **Vulnerability** | A weakness that can be exploited by a threat.                          |

> ⚠️ These terms are often used interchangeably in everyday language but have **very specific meanings in cybersecurity**.

---

## 📉 What Is a Security Risk?

Risk is defined differently across organizations, but in security, it generally refers to:

> **Risk = Likelihood × Impact**

### 💡 Real-world analogy:
- **Risk**: Being late to work
- **Threat**: A nail in the road
- **Vulnerability**: Your tires being susceptible to puncture

### ✅ Why Calculate Risk?
- Prevent costly and disruptive events  
- Identify system/process improvements  
- Determine which risks are tolerable  
- Prioritize attention to critical assets  

As a security analyst, you’ll often **focus on likelihood**, working to reduce risks by minimizing vulnerabilities or avoiding threats.

---

## 📊 Risk Factors

There are two main contributors to risk:

### ⚠️ Threats
Events or conditions that can negatively impact assets.

### 🧩 Vulnerabilities
Weaknesses in systems or behaviors that can be exploited by threats.

---

## 🎯 Categories of Threats

| Type            | Example                                                                 |
|-----------------|-------------------------------------------------------------------------|
| **Intentional** | A hacker exploits a misconfigured application.                         |
| **Unintentional** | An employee accidentally lets an unauthorized person into a secure area. |

---

## 🛠️ Categories of Vulnerabilities

| Type            | Example                                                                 |
|-----------------|-------------------------------------------------------------------------|
| **Technical**   | A misconfigured application or outdated system.                         |
| **Human**       | A lost access badge or falling for phishing emails.                     |

Both technical and human weaknesses contribute to overall organizational risk.

---

## ✅ Key Takeaways

- Risks, threats, and vulnerabilities are **core concepts** in cybersecurity.
- Understanding how they relate helps you:
  - Speak the language of the industry
  - Build better defenses
  - Gain credibility and contribute to team success

> 🎓 Mastering these terms is a critical first step in your journey as a cybersecurity professional.

---

# 🗃️ Common Classification Requirements in Asset Management

Effective cybersecurity starts with **asset management** — identifying, tracking, and classifying what needs protection. You can only protect what you know you have.

---

## 📦 Why Asset Management Matters

Organizations rely on many types of assets to function and stay secure. To protect them, they must understand:

- **What** they have  
- **Where** it is  
- **Who** owns it  
- **How important** it is  

### 💼 Types of Assets

| Asset Type         | Examples                                      |
|--------------------|-----------------------------------------------|
| **Digital**        | Customer data, financial records              |
| **Information Systems** | Networks, databases, software          |
| **Physical**       | Facilities, equipment, supplies               |
| **Intangible**     | Brand reputation, intellectual property       |

> 🛠️ **Asset classification** helps organizations label and prioritize assets based on **sensitivity** and **importance**.

---

## 🏷️ Common Asset Classification Levels

Asset classification helps with:

- Prioritizing security resources  
- Reducing IT costs  
- Meeting legal and compliance requirements  

### 🔐 Typical Classification Scheme:

| Level        | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| **Restricted**   | Highest sensitivity; access limited to essential personnel only          |
| **Confidential** | Exposure could significantly harm the organization                       |
| **Internal-Only**| Intended for internal use by employees and trusted partners              |
| **Public**       | Lowest sensitivity; safe to disclose externally                          |

> 📌 Note: Some organizations (e.g., governments) may use **different labels** (e.g., using “Confidential” for the highest level).

---

## ⚠️ Challenges in Asset Classification

### 🔍 Ownership Confusion
Determining the **owner** of an asset isn’t always straightforward.  
**Example:**  
A company issues a laptop to an employee →  
- Is the company the owner?
- What if the employee stores personal data (photos, documents)?

### 🧾 Multiple Classifications
Some information includes a mix of sensitivity levels.  
**Example:**  
A letter to you may include:
- **Public info**: Your name  
- **Confidential info**: Your address  

This mix makes it hard to assign a single classification level.

---

## 🎯 Key Takeaways

- **Every organization** has different classification requirements.
- Asset classification is key to a strong **risk management strategy**.
- **Information assets** are among the most complex and important to classify.
- As a cybersecurity professional, your role includes:
  - Protecting information from misuse and unauthorized disclosure  
  - Helping businesses navigate challenges in asset classification  

> 💡 Building your expertise in asset management and classification will help you provide real value to organizations and protect what matters most.

---

# ☁️ The Emergence of Cloud Security

Cloud computing is one of the most transformative developments in modern technology. As more businesses shift operations online, cloud-based services offer scalability, efficiency, and cost savings — but also introduce new cybersecurity risks.

> _"An on-demand, massively scalable service, hosted on shared infrastructure, accessible via the internet."_  
> — UK National Cyber Security Centre

---

## 🚀 Rise of Cloud-Based Services

Historically, launching an online business required managing your own infrastructure. Cloud technologies now empower businesses to:
- Scale quickly
- Reduce operational costs
- Deploy global services easily

Despite these benefits, cloud adoption brings **new challenges for data protection and cybersecurity**.

---

## 🔧 What Are Cloud-Based Services?

Cloud services are **on-demand** and **internet-accessible** solutions for running applications, storing data, and building infrastructure.

### 🧱 The Three Main Cloud Models

| Service Type     | Description                                                                 | Examples                             |
|------------------|-----------------------------------------------------------------------------|--------------------------------------|
| **SaaS**         | Software delivered via web browser. No infrastructure setup required.       | Gmail, Slack, Zoom                   |
| **PaaS**         | Online tools to build and deploy applications.                              | Google App Engine, Heroku, Cloud Foundry |
| **IaaS**         | Virtualized computing resources like servers, networking, and storage.      | Google Cloud Platform, Microsoft Azure |

---

## 🔒 What Is Cloud Security?

Cloud security is a growing subfield of cybersecurity that focuses on:
- Protecting data stored in the cloud
- Securing cloud-hosted applications
- Managing shared infrastructure access

In traditional IT, the organization managed everything **on-premises**. In the cloud, responsibilities are split.

---

## 🧩 The Shared Responsibility Model

Security responsibilities are **shared** between the cloud provider and the customer, depending on the type of service:

| Responsibility         | SaaS              | PaaS              | IaaS              |
|------------------------|-------------------|-------------------|-------------------|
| Physical Infrastructure| ✅ Provider       | ✅ Provider       | ✅ Provider       |
| Network Controls       | ❌                | ⚠️ Shared         | ⚠️ Shared         |
| Application Security   | ❌                | ✅ Customer       | ✅ Customer       |
| Data Handling & Access | ✅ Customer       | ✅ Customer       | ✅ Customer       |

Customers are typically responsible for:
- Identity and access management (IAM)
- Configuring their environment
- Protecting their own data

---

## ⚠️ Cloud Security Challenges

Despite providers' best efforts, several challenges persist:

### 🔧 Misconfiguration
- One of the **top causes** of cloud-native breaches.
- Default settings often fail to meet security objectives.

### 🕵️ Access Monitoring
- Hard to track across shared environments and service layers.

### ⚖️ Regulatory Compliance
- Meeting legal frameworks such as:
  - HIPAA (healthcare)
  - PCI DSS (payments)
  - GDPR (data protection in the EU)

---

## 📈 Growing Demand for Cloud Security

As businesses shift online, demand for **cloud security professionals** is rising sharply.

> 🔥 _Cloud security is ranked among the most in-demand cybersecurity skills_  
> — Burning Glass Technologies

---

## ✅ Key Takeaways

- **Cloud computing** enables rapid business growth, but introduces complex security risks.
- **Cloud security** is about protecting cloud-hosted data, applications, and infrastructure.
- The **shared responsibility model** divides security tasks between the provider and customer.
- Professionals must understand **misconfiguration**, **access control**, and **compliance** as key challenges.
- Cloud security is **an essential and fast-growing field** in cybersecurity.

---

# 🛡️ Security Guidelines in Action: Understanding the NIST Cybersecurity Framework (CSF)

Organizations face growing security risks that can be difficult to manage. The **NIST Cybersecurity Framework (CSF)** provides a **flexible and scalable approach** to assessing, building, and improving security operations.

---

## 📜 Origins of the Framework

Released in **2014**, the **National Institute of Standards and Technology (NIST)** developed the CSF to:
- Protect U.S. **critical infrastructure**
- Serve as an **unbiased source of security best practices**
- Provide a resource suitable for **public and private sector** organizations

> ⚠️ In **February 2024**, the sixth function **"Govern"** was added to emphasize leadership's role in cybersecurity.

---

## 🧱 Components of the NIST CSF

The CSF is composed of three main components:

### 1. 🔧 **Core**
Describes desired cybersecurity outcomes and activities across six key **functions**:

| Function   | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| **Identify** | Understand assets, risks, and organizational context                     |
| **Protect**  | Implement safeguards to secure assets                                      |
| **Detect**   | Develop the ability to detect cybersecurity events                        |
| **Respond**  | Take action regarding detected cybersecurity incidents                    |
| **Recover**  | Restore services and operations post-incident                             |
| **Govern**   | (Added 2024) Define cybersecurity risk management policies and oversight  |

---

### 2. 📶 **Tiers**
Tiers measure the **maturity level** of an organization’s cybersecurity program:

| Tier | Description                                 |
|------|---------------------------------------------|
| 1    | Partial (low control and coordination)       |
| 2    | Risk Informed                                |
| 3    | Repeatable                                   |
| 4    | Adaptive (fully optimized and integrated)    |

---

### 3. 📂 **Profiles**
**Profiles** are customizable templates that help organizations:
- Benchmark their current state
- Compare against industry standards
- Align with specific **risk environments**

> 📝 Profiles support both **starting new security programs** and **enhancing existing ones**.

---

## 🛠️ Implementing the NIST CSF

Although the NIST CSF is **voluntary**, it is widely adopted to help achieve **compliance** with regulatory frameworks such as:
- HIPAA
- PCI DSS
- GDPR

### 🧭 CISA's Implementation Guidance

1. **Create a current profile** of security operations  
2. **Perform a risk assessment** based on regulations and business needs  
3. **Analyze gaps** in current defenses  
4. **Develop a plan of action** to address weaknesses  

> 💡 _Tip: Always consider evolving risks, threats, and vulnerabilities when applying the CSF._

---

## 🌐 Industries Embracing the CSF

The CSF is used across **many industries**, including:
- Healthcare  
- Finance  
- Critical infrastructure  
- Commercial facilities

Its **global relevance** and alignment with **regulatory expectations** make it a go-to resource for businesses of all sizes.

---

## ✅ Key Takeaways

- The **NIST CSF** is a trusted, flexible cybersecurity framework.
- It helps organizations **measure, assess, and improve** their security programs.
- Core components: **Core Functions**, **Tiers**, and **Profiles**
- Used to achieve **regulatory compliance** and reduce **financial and reputational risk**
- Supported by detailed **implementation guidance** from CISA

> 🚀 Embracing the CSF helps organizations align with global security best practices and build a resilient cybersecurity posture.

---

