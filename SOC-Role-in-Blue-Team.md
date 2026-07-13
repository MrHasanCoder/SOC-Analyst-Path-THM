# SOC-Analyst-Path-THM
this is my attempt to document my Journey
# [SOC Role in Blue Team](https://tryhackme.com/room/socroleinblueteam)

A walkthrough for the **SOC Role in Blue Team** room in the **Blue Team** path on **TryHackMe** (as of 06/11/2025).

This room belongs to **Section 1 – Blue Team Introduction**.

## Blue Team Introduction

Start your defensive security career by exploring the **Blue Team** and its core, the **Security Operations Centre (SOC)**. This room explains why defensive security is important and how it helps organizations stay protected against cyber attacks.

### Learning Objectives

- Understand the concept and purpose of the **Blue Team**.
- Learn where the **SOC** fits within an organization's structure.
- Explore the career path of a **SOC L1 Analyst**.

### Prerequisites

- Complete the **Junior Security Analyst Intro** room.
- Review **SOC Roles and Processes**.

---

## Task 1 – Introduction

### Question

**Let's find out!**

**Answer:** *No answer needed.*

---

# Task 2 – Security Hierarchy

## Security Hierarchy

Cybersecurity priorities vary depending on the type of organization.

For example:

- **Law firms** focus on protecting confidential legal documents.
- **Factories** prioritize the availability of production lines.
- **Hospitals** focus on patient safety.

Because every organization has different priorities, each company builds its security team differently.

Top executives such as the **CEO** focus on business objectives rather than technical security decisions. To manage cybersecurity effectively, organizations appoint a **Chief Information Security Officer (CISO)**, who oversees the company's security strategy and manages multiple security departments.

## Security Departments

In small organizations, the **IT department** often handles cybersecurity responsibilities.

Medium-sized companies may have a general **Information Security** team that manages various security tasks.

Larger organizations typically separate responsibilities into dedicated teams:

- **Red Team** – Offensive security professionals, penetration testers, and ethical hackers who identify vulnerabilities.
- **GRC Team** – Specialists responsible for governance, risk management, and compliance with standards such as **PCI DSS**.
- **Blue Team** – Defensive security professionals, including **SOC Analysts**, **SOC Engineers**, and **Incident Responders**, who monitor, detect, and respond to security incidents.

---

## Questions

### Which senior role typically makes key cybersecurity decisions?

**Answer:** `CISO`

**Explanation:**

The **Chief Information Security Officer (CISO)** leads the organization's cybersecurity strategy while aligning security with business objectives. Unlike the CEO, who focuses on overall business operations, or Security Managers, who oversee individual teams, the CISO is responsible for making organization-wide cybersecurity decisions.

# Task 3 – Meet the Blue Team

The **Blue Team** is responsible for **defensive security**. Its primary objective is to continuously monitor for cyber threats, detect suspicious activity, and respond to incidents as quickly as possible.

Depending on the organization's size and industry, a Blue Team can consist of **3 to 50 members**, divided into different specialized departments.

---

## Security Operations Centre (SOC)

The **Security Operations Centre (SOC)** is the heart of an organization's cybersecurity operations. It acts as the **first line of defense**, monitoring alerts, investigating suspicious activity, and responding to security incidents.

A typical SOC consists of the following roles:

- **L1 Analysts** – Junior analysts who triage alerts and escalate complex incidents to L2.
- **L2 Analysts** – Experienced analysts responsible for investigating advanced attacks.
- **SOC Engineers** – Specialists who configure, maintain, and improve security tools such as **SIEM** and **EDR**.
- **SOC Manager** – Oversees the SOC team and manages daily security operations.

---

## Cyber Incident Response Team (CIRT)

When a security incident becomes too complex or severe for the SOC, the **Cyber Incident Response Team (CIRT)** takes over.

Also known as **CSIRT** or **CERT**, this team is responsible for rapidly containing, investigating, and recovering from major cyber incidents.

Unlike SOC analysts, CIRT members rely heavily on their technical expertise rather than security tools alone.

Some well-known examples include:

- **JPCERT** – Japan's national CERT.
- **Mandiant** – A private incident response company handling global cyber incidents.
- **AWS CIRT** – Amazon Web Services' Cyber Incident Response Team.

---

## Specialized Defensive Roles

Large enterprises, technology companies, and government organizations often require highly specialized Blue Team roles.

These positions demand deep technical knowledge and usually require prior experience in SOC or IT environments.

Some examples include:

- **Digital Forensics Analyst** – Investigates disks and memory to uncover hidden evidence.
- **Threat Intelligence Analyst** – Researches emerging threat actors and attack techniques.
- **Application Security (AppSec) Engineer** – Ensures secure software development practices.
- **AI Researcher** – Studies AI-related threats and develops defensive strategies.

---

## Questions

### Does Blue Team focus on defensive or offensive security?

**Answer:** `Defensive`

**Explanation:**

The **Blue Team** focuses on **defensive security**, including monitoring systems, detecting threats, and responding to security incidents. In contrast, the **Red Team** performs offensive security by simulating attacks to identify vulnerabilities before attackers can exploit them.

---

### Which department handles active or urgent cyber incidents?

**Answer:** `CIRT`

**Explanation:**

The **Cyber Incident Response Team (CIRT)** is responsible for handling critical or high-priority security incidents that require immediate action or exceed the capabilities of the SOC team.--

### What is the common name for roles like SOC Analysts and Engineers?

**Answer:** `Blue Team`

**Explanation:**

The **Blue Team** consists of defensive security professionals responsible for monitoring systems, detecting threats, responding to incidents, and strengthening an organization's security posture.
# Task 4 – Advancing SOC Career

## SOC Career Path

Starting as a **SOC L1 Analyst** is one of the best ways to build a strong foundation in cybersecurity. This role provides hands-on experience with real-world security incidents, threat detection, and incident response while exposing you to different areas of defensive security.

To begin your SOC career:

- Develop strong **SOC fundamentals** and practice them regularly.
- Strengthen related skills such as **Networking**, **Operating Systems**, **General IT**, and even **Red Teaming** concepts.
- Participate in **CTFs (Capture The Flag)** competitions to improve practical skills.
- Stay updated with the latest cybersecurity news and emerging threats.
- Consider earning certifications such as **SAL1**.
- Prepare for interviews by understanding the differences between an **Internal SOC** and an **MSSP**.
- Gain real-world experience as a SOC L1 Analyst before moving into more specialized or senior positions.

---

## Internal SOC vs MSSP

Not every organization has the resources or expertise to operate its own Security Operations Centre.

Instead, many organizations outsource their security operations to a **Managed Security Services Provider (MSSP)**.

An **MSSP** provides cybersecurity services—including SOC monitoring—to multiple clients.

Working in an MSSP environment is often:

- Fast-paced
- High-pressure
- Exposure to multiple customers and environments
- Excellent for gaining broad cybersecurity experience early in your career

Whether you begin in an **Internal SOC** or an **MSSP**, both paths provide valuable experience for advancing your cybersecurity career.

---

## Next Steps

The most common career progression after becoming a **SOC L1 Analyst** is moving to a **SOC L2 Analyst** role.

However, SOC experience can also lead to several specialized career paths, including:

- **SOC Engineer**
- **Incident Response (CIRT)**
- **Threat Intelligence**
- **Digital Forensics**
- **Security Management**
- **Chief Information Security Officer (CISO)**

Your first one or two years in cybersecurity should focus on gaining practical experience, building technical skills, and discovering which area interests you the most.

---

## Questions

### How would you call a cybersecurity company providing SOC services?

**Answer:** `MSSP`

**Explanation:**

A **Managed Security Services Provider (MSSP)** is a cybersecurity company that provides outsourced security services, including Security Operations Centre (SOC) monitoring and incident response. Organizations without the resources or expertise to maintain an internal SOC often rely on an MSSP.

---

### Which role naturally continues your SOC L1 Analyst journey?

**Answer:** `SOC L2 Analyst`

**Explanation:**

A **SOC L2 Analyst** is the natural progression after working as a **SOC L1 Analyst**. L2 analysts investigate more complex security incidents using the experience gained from triaging alerts and performing basic incident response. However, professionals may also choose to specialize in other cybersecurity domains based on their interests.
# Task 5 – Final Challenge

## Final Challenge

In this challenge, you take the role of the **Chief Information Security Officer (CISO)** at **TrySecureMe**, a multinational company.

Seven different security incidents occur simultaneously, and your task is to assign the correct cybersecurity professional to each incident.

Successfully matching every role reveals the room flag.

---

## Role Assignments

### 1. SIEM created an alert about **FW-NY-01** firewall brute-force.

**Assigned Role:** **Lucas – SOC L1 Analyst**

**Explanation:**

A **SOC L1 Analyst** is responsible for monitoring and triaging security alerts. Since this is an initial SIEM alert, it falls under the responsibilities of an L1 analyst.

---

### 2. The HR manager Anna launched phishing malware.

**Assigned Role:** **Susan – SOC L2 Analyst**

**Explanation:**

A **SOC L2 Analyst** performs in-depth investigations of security incidents and analyzes malware, making them the correct person for this task.

---

### 3. The office in France was hit with ransomware and requires an immediate response.

**Assigned Role:** **Robert – CERT Lead**

**Explanation:**

A ransomware outbreak is a critical incident that requires rapid containment and recovery. The **CERT (CIRT) Lead** is responsible for coordinating and managing incident response.

---

### 4. Servers storing customer credit card data require a **PCI DSS** audit.

**Assigned Role:** **Nick – GRC Auditor**

**Explanation:**

A **Governance, Risk, and Compliance (GRC) Auditor** ensures that the organization complies with regulatory standards such as **PCI DSS**.

---

### 5. The new version of **tryhackme.thm** needs to be tested for vulnerabilities.

**Assigned Role:** **Ben – Penetration Tester**

**Explanation:**

A **Penetration Tester** performs authorized attacks against applications and systems to identify security vulnerabilities before attackers do.

---

### 6. The SIEM stopped working because of a storage limitation.

**Assigned Role:** **Eugen – SOC Engineer**

**Explanation:**

A **SOC Engineer** is responsible for deploying, maintaining, and troubleshooting security infrastructure, including SIEM platforms.

---

### 7. The **FIN7** threat group is actively targeting the organization.

**Assigned Role:** **Alice – Threat Researcher**

**Explanation:**

A **Threat Researcher (Threat Intelligence Analyst)** studies threat actors, attack techniques, and indicators of compromise to help organizations prepare for emerging threats.

---

## Flag

**Answer:**

```text
THM{trysecureme_is_secured!}
```

---
## Question

### Complete the room!

**Answer:** *No answer needed.*
--
used chatgpt to write the post , copy pasted the content from thm rooms , found the flags and uploaded.
--
