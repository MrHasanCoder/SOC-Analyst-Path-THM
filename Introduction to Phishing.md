# Introduction to Phishing - SOC Simulator

## Objective

The objective of this SOC Simulator scenario was to investigate phishing-related alerts, determine whether they were **True Positives** or **False Positives**, document the investigation findings, and recommend the appropriate response. The exercise also measured investigation speed, accuracy, and reporting quality.

---

# Scenario Outcome

**Status:** Failed

The scenario was not completed successfully because **one True Positive alert was misclassified**. Although I did not pass this attempt, the exercise provided valuable insight into my investigation process and highlighted areas where I can improve.

---

# Performance Metrics

| Metric                             | Result     |
| :--------------------------------- | :--------- |
| Alerts Closed                      | 5          |
| Mean Time to Resolve (MTTR)        | 4 minutes  |
| Mean Dwell Time                    | 15 minutes |
| True Positive Identification Rate  | 67%        |
| False Positive Identification Rate | 100%       |

---

# Alert Analysis

## True Positive Alerts

### Alert ID: 8816

| Field           | Value                                                  |
| :-------------- | :----------------------------------------------------- |
| Alert Rule      | Access to Blacklisted External URL Blocked by Firewall |
| Severity        | High                                                   |
| Type            | Firewall                                               |
| Resolution Time | 5.63 minutes                                           |
| Classification  | Correct                                                |

### Alert ID: 8817

| Field           | Value                                             |
| :-------------- | :------------------------------------------------ |
| Alert Rule      | Inbound Email Containing Suspicious External Link |
| Severity        | Medium                                            |
| Type            | Phishing                                          |
| Resolution Time | 4.92 minutes                                      |
| Classification  | Correct                                           |

---

## False Positive Alerts

### Alert ID: 8814

| Field           | Value                                             |
| :-------------- | :------------------------------------------------ |
| Alert Rule      | Inbound Email Containing Suspicious External Link |
| Severity        | Medium                                            |
| Type            | Phishing                                          |
| Resolution Time | 4.80 minutes                                      |
| Classification  | Correct                                           |

### Alert ID: 8815

| Field           | Value                                             |
| :-------------- | :------------------------------------------------ |
| Alert Rule      | Inbound Email Containing Suspicious External Link |
| Severity        | Medium                                            |
| Type            | Phishing                                          |
| Resolution Time | 1.62 minutes                                      |
| Classification  | Incorrect                                         |

This alert was the reason the scenario was not completed successfully.

### Alert ID: 8818

| Field           | Value                                             |
| :-------------- | :------------------------------------------------ |
| Alert Rule      | Inbound Email Containing Suspicious External Link |
| Severity        | Medium                                            |
| Type            | Phishing                                          |
| Resolution Time | 1.57 minutes                                      |
| Classification  | Correct                                           |

---

# AI Report Feedback

The AI evaluation reviewed the quality of my investigation reports and identified both strengths and areas for improvement.

## Strengths

* Included the **Who** involved in most investigations.
* Clearly described **What** happened.
* Successfully identified benign activity, resulting in a **100% False Positive identification rate**.

## Areas for Improvement

The reports should provide:

* Better context for **When** the activity occurred.
* A clearer explanation of **Where** the activity originated.
* Stronger reasoning for **Why** an alert was classified as malicious or benign.
* Justification for **why an alert should be escalated**.
* Appropriate **remediation recommendations** after the investigation.
* Faster investigation of **Firewall** alerts, as they required more time than the others.

---

# Key Takeaways

This exercise reinforced several important SOC analyst responsibilities:

* Investigate every alert carefully before making a classification.
* Avoid rushing decisions, especially when alerts appear similar.
* Produce clear and complete investigation reports.
* Explain the reasoning behind every classification.
* Include escalation decisions when necessary.
* Recommend remediation actions for confirmed threats.
* Balance investigation speed with accuracy.

---

# Reflection

Although I did not successfully complete this scenario, it provided valuable experience and constructive feedback. I correctly classified most of the alerts, achieved a **100% False Positive identification rate**, and identified several areas where I can improve my reporting and investigation workflow.

My next goal is to replay the scenario, improve my True Positive identification rate, reduce investigation time, and produce investigation reports that fully address the **Who, What, When, Where, Why, Escalation, and Remediation** aspects of every alert.

Each lab is another opportunity to improve my analytical thinking and become a more effective SOC Analyst.
