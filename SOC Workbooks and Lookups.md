# SOC Workbooks and Lookups – TryHackMe

When I started this room, I realized that investigating an alert isn't just about checking logs. A SOC analyst first needs to understand **who** the user is, **what** device is involved, and **how** everything connects inside the organization's network. Having this extra context makes it much easier to decide whether an alert is harmless or something that needs immediate attention.

## Identity Inventory

An identity inventory is basically a directory of everyone in the company. It stores details like employee names, departments, job roles, managers, and access permissions.

During an investigation, analysts use it to understand if a user's activity is normal. For example, if someone from the Finance department accesses financial data, that's probably expected. But if a marketing employee suddenly starts accessing payroll information, it deserves a closer look.

## Asset Inventory

An asset inventory keeps track of all the systems and devices used by the organization.

It usually contains information such as:

* Hostname
* IP Address
* Operating System
* Device Owner
* Server Purpose
* Business Criticality

This information helps analysts understand how important a device is. An alert on a critical production server is usually much more serious than one on a normal employee workstation.

## Network Diagrams

Network diagrams show how devices communicate with each other inside the company.

They help analysts quickly understand:

* Which subnet a device belongs to
* Firewall locations
* VPN connections
* Internal servers
* Network zones

Instead of guessing where a machine sits in the environment, analysts can simply refer to the diagram and understand the bigger picture.

## SOC Workbooks

A SOC workbook is a step-by-step investigation guide that analysts follow whenever a specific alert appears.

Rather than making random decisions, the workbook provides a clear process to follow. This helps every analyst investigate alerts in the same way, reduces mistakes, and speeds up incident response.

These workbooks are especially useful for Level 1 SOC analysts, who deal with hundreds of alerts every day.

## Typical Investigation Process

Most investigations follow a simple workflow:

**1. Gather Context**

* Identify the user.
* Check the affected device.
* Collect any additional information about the alert.

**2. Investigate**

* Review logs from SIEM and EDR.
* Compare the activity with the user's normal behavior.
* Look for any suspicious indicators.

**3. Make a Decision**

* Close the alert if it is a false positive.
* Escalate it to the Level 2 SOC team if malicious activity is confirmed.
* Contact the user if more information is needed.

## What I Learned

This room showed me that security alerts don't tell the whole story. Context is just as important as the alert itself.

I learned how identity inventories, asset inventories, network diagrams, and SOC workbooks work together to help analysts investigate incidents more efficiently. Instead of relying only on logs, a SOC analyst combines information from multiple sources before making a decision.

Overall, this room gave me a better understanding of how real SOC teams investigate alerts in a structured and consistent way.
