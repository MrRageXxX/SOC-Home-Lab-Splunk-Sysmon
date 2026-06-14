# SOC Home Lab using Splunk and Sysmon

## Project Overview

This project demonstrates the deployment of a Security Operations Center (SOC) Home Lab using:

- Splunk Enterprise
- Sysmon
- Splunk Universal Forwarder
- Windows 10
- Ubuntu
- Kali Linux

The goal was to collect endpoint telemetry, centralize logs, create detections, and visualize security events.

---

## Architecture

Kali Linux
      │
      ▼
Windows 10 + Sysmon
      │
      ▼
Splunk Universal Forwarder
      │
      ▼
Ubuntu + Splunk Enterprise
      │
      ▼
Dashboard & Security Monitoring

---

## Implemented Use Cases

### Process Creation Monitoring
- Sysmon Event ID 1
- Detection of cmd.exe and PowerShell execution

### Network Connection Monitoring
- Sysmon Event ID 3
- Destination IP and Port visibility

### DNS Monitoring
- Sysmon Event ID 22
- DNS query visibility

---

## Dashboard

### SOC Home Lab Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Screenshots

### Sysmon and Forwarder Running

![Services](screenshots/services.png)

### Process Creation Detection

![Process](screenshots/process.png)

### Network Connection Detection

![Network](screenshots/network.png)

### DNS Query Detection

![DNS](screenshots/dns.png)

---

## Skills Demonstrated

- SIEM Administration
- Log Collection
- Endpoint Monitoring
- Detection Engineering
- Security Monitoring
- Splunk Search Processing Language (SPL)
