# MITRE ATT&CK Reference

## T1059

### Command and Scripting Interpreter

Adversaries may use command shells or scripting environments to execute commands.

Observed:

- cmd.exe

Sysmon Event:

- Event ID 1

---

## T1016

### System Network Configuration Discovery

Adversaries gather network configuration information.

Observed:

- ipconfig.exe

Sysmon Event:

- Event ID 1

---

## T1033

### System Owner/User Discovery

Adversaries identify current user accounts.

Observed:

- User activity investigation

Sysmon Event:

- Event ID 1

---

## T1071

### Application Layer Protocol

Adversaries use common application layer protocols for communication.

Observed:

- Browser network traffic

Sysmon Event:

- Event ID 3

---

## T1071.004

### DNS

Adversaries may use DNS communications.

Observed:

- DNS query events

Sysmon Event:

- Event ID 22

---

## T1074

### Data Staged

Adversaries prepare data for collection or exfiltration.

Observed:

- File creation events

Sysmon Event:

- Event ID 11

---

## T1112

### Modify Registry

Adversaries modify Windows Registry settings.

Observed:

- Registry Value Set events

Sysmon Event:

- Event ID 13

---

## T1574

### Hijack Execution Flow

Adversaries may abuse DLL loading mechanisms.

Observed:

- DLL/Image Load Monitoring

Sysmon Event:

- Event ID 7

---

# ATT&CK Coverage Summary

| Sysmon Event | MITRE Technique |
|-------------|----------------|
| Event ID 1 | T1059 |
| Event ID 1 | T1016 |
| Event ID 1 | T1033 |
| Event ID 3 | T1071 |
| Event ID 7 | T1574 |
| Event ID 11 | T1074 |
| Event ID 13 | T1112 |
| Event ID 22 | T1071.004 |

This project demonstrates practical application of MITRE ATT&CK techniques through Windows Sysmon-based threat hunting and security monitoring.
