# Sysmon Deployment and Configuration

## Overview

Sysmon is a Windows system service that provides detailed logging of security-relevant system activity.

It extends native Windows logging capabilities and enables security analysts to investigate suspicious behavior more effectively.

---

## Installation Process

### Download Sysmon

Source:

Microsoft Sysinternals

### Configuration

A Sysmon configuration file was deployed to enable collection of:

- Process Creation Events
- Network Connections
- Image Load Events
- Registry Events
- DNS Queries
- File Creation Events

---

## Validation

Verification was performed through:

Event Viewer

Applications and Services Logs
→ Microsoft
→ Windows
→ Sysmon
→ Operational

Successful event generation confirmed proper Sysmon deployment.

---

## Security Benefits

- Enhanced Visibility
- Threat Detection
- Incident Investigation
- Threat Hunting
- Security Monitoring
