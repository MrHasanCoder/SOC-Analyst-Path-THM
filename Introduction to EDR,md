# Introduction to EDR (Endpoint Detection and Response)

**Room Link:** https://tryhackme.com/room/introductiontoedrs

---

# Overview

This room introduced me to one of the most important security tools used in a Security Operations Center (SOC): **Endpoint Detection and Response (EDR)**.

Unlike a traditional antivirus that mainly depends on signatures, an EDR continuously monitors endpoint activity, collects detailed telemetry, detects suspicious behavior, and provides analysts with the ability to investigate and respond to threats.

The room also included a practical investigation inside a simulated EDR console, which helped me understand how analysts perform alert triage using endpoint telemetry. :contentReference[oaicite:0]{index=0}

---

# What I Learned

- What Endpoint Detection and Response (EDR) is
- Difference between Antivirus (AV) and EDR
- The three pillars of an EDR
- EDR architecture
- Endpoint telemetry collection
- Detection techniques used by modern EDRs
- Response capabilities available to analysts
- Investigating alerts inside an EDR dashboard
- Understanding attack chains using process trees

---

# Key Concepts

## What is an EDR?

Endpoint Detection and Response (EDR) is a security solution that continuously monitors endpoint devices such as:

- Windows systems
- Linux systems
- macOS devices
- Servers
- Workstations

It records endpoint activities, detects suspicious behavior, and provides security analysts with the tools needed to investigate and respond quickly.

Unlike antivirus software, EDR focuses on **behavior** rather than just known malware signatures. :contentReference[oaicite:1]{index=1}

---

# Antivirus vs EDR

| Antivirus | EDR |
|-----------|-----|
| Signature-based detection | Behavior-based detection |
| Detects known malware | Detects known and unknown threats |
| Limited visibility | Complete attack timeline |
| Minimal investigation capability | Deep forensic investigation |
| Basic protection | Detection + Investigation + Response |

One example from the room demonstrated how a malicious Microsoft Word macro could bypass a traditional antivirus but still be detected by an EDR because of the suspicious process chain.

---

# Three Pillars of an EDR

## 1. Visibility

Provides complete visibility into endpoint activity.

Examples include:

- Process creation
- File modifications
- Registry changes
- Command execution
- User actions
- Process trees
- Historical activity

This visibility helps analysts reconstruct the entire attack chain.

---

## 2. Detection

Modern EDRs detect threats using:

- Behavioral analysis
- Indicators of Attack (IOA)
- Machine Learning
- Threat Intelligence
- Process relationships

Instead of asking:

> "Is this file known malware?"

An EDR asks:

> "Is this behavior suspicious?"

---

## 3. Response

Once malicious activity is detected, analysts can:

- Kill malicious processes
- Isolate endpoints
- Quarantine files
- Collect forensic evidence
- Access the endpoint remotely
- Run response scripts

These actions help stop attacks before they spread.

---

# How an EDR Works

A typical EDR consists of two major components.

## EDR Agent

Installed on every endpoint.

Responsible for:

- Collecting telemetry
- Monitoring system activity
- Sending logs to the console

---

## EDR Console

The central dashboard used by SOC analysts.

Allows analysts to:

- View alerts
- Investigate incidents
- Search telemetry
- Perform threat hunting
- Respond to threats

---

# Endpoint Telemetry

Telemetry is one of the biggest strengths of an EDR.

Examples include:

- Process creation
- Command-line activity
- PowerShell execution
- Registry modifications
- File creation
- File deletion
- Network connections
- User logins
- Parent-child process relationships

All of this information helps analysts understand what happened before, during, and after an attack.

---

# Detection Capabilities

Modern EDRs detect attacks through multiple techniques:

- Behavioral Detection
- Threat Intelligence
- Machine Learning
- Indicators of Attack (IOA)
- Suspicious parent-child processes
- Memory injection detection
- Persistence detection

Instead of relying only on malware signatures, EDRs analyze suspicious behaviors across the endpoint.

---

# Response Capabilities

The room also covered the response actions available to analysts.

Common actions include:

- Kill Process
- Quarantine File
- Isolate Endpoint
- Remote Shell Access
- Collect Memory Dumps
- Retrieve Event Logs
- Gather Registry Hives
- Collect Specific Files

These capabilities allow analysts to investigate and contain attacks without physically accessing the affected machine.

---

# Practical Investigation

The final section of the room provided access to a simulated EDR dashboard.

During the investigation I learned how to:

- Read alert details
- View attack timelines
- Examine process trees
- Follow parent-child relationships
- Inspect downloaded payloads
- Identify suspicious executables
- Review network connections
- Use threat intelligence labels
- Understand endpoint telemetry during investigations

This was the most useful part of the room because it demonstrated how real SOC analysts investigate endpoint alerts.

---

# Room Answers

## Task 2

**Q1. Which feature of EDR provides a complete context for all the detections?**

```
Visibility
```

**Q2. Which process spawned sc.exe?**

```
services.exe
```

---

## Task 3

**Q1. In the given analogy, what represents an AV?**

```
Immigration Check
```

**Q2. Which legitimate process was hijacked by the attacker?**

```
svchost.exe
```

**Q3. Which security solution might mark this activity as clean?**

```
Antivirus
```

---

## Task 4

**Q1. Which component collects telemetry from endpoints?**

```
EDR Agent
```

**Q2. An EDR Agent is also known as a?**

```
Sensor
```

---

## Task 5

**Q1. Which telemetry helps detect C2 communications?**

```
Network Connections
```

**Q2. Where are Windows configuration settings primarily stored?**

```
Registry
```

---

## Task 6

**Q1. Which feature identifies threats based on known malicious behaviours?**

```
Indicators of Attack (IOA)
```

---

## Task 7

**Q1. Which tool was launched by CMD.exe to download the payload?**

```
curl.exe
```

**Q2. Absolute path to the downloaded malware?**

```
C:\Users\Administrator\Downloads\payload.exe
```

**Q3. Absolute path to syncsvc.exe?**

```
C:\Users\Public\syncsvc.exe
```

**Q4. URL used during exfiltration?**

```
http://104.21.88.45/upload
```

**Q5. UpdateAgent.exe Threat Intel label?**

```
Trojan
```

---

# My Takeaway

This room clearly showed why modern organizations rely on EDR instead of traditional antivirus alone. The biggest lesson for me was that detecting malicious **behavior** is often more valuable than detecting a known malicious file.

Understanding process trees, endpoint telemetry, and response actions gave me a much better idea of how SOC analysts investigate incidents in real environments. The hands-on investigation inside the simulated EDR console made the concepts much easier to understand and connected the theory with practical analysis. :contentReference[oaicite:2]{index=2}
