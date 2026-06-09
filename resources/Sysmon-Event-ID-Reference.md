# Sysmon Event ID Reference

## Event ID 1

### Process Creation

Logs process execution activity.

Important Fields:

- Image
- CommandLine
- ParentImage
- User

Security Use Cases:

- Malware Execution
- PowerShell Abuse
- Suspicious Commands

MITRE ATT&CK:

- T1059
- T1016
- T1033

---

## Event ID 3

### Network Connection

Logs outbound network communication.

Important Fields:

- Source IP
- Destination IP
- Destination Port
- Protocol

Security Use Cases:

- Command and Control Detection
- Data Exfiltration Detection

MITRE ATT&CK:

- T1071

---

## Event ID 7

### Image Load

Logs DLL loading activity.

Important Fields:

- ImageLoaded
- Signature
- Hashes

Security Use Cases:

- DLL Hijacking
- DLL Injection

MITRE ATT&CK:

- T1574

---

## Event ID 11

### File Creation

Logs file creation events.

Important Fields:

- TargetFilename
- User
- Process

Security Use Cases:

- Malware Staging
- Payload Delivery

MITRE ATT&CK:

- T1074

---

## Event ID 13

### Registry Value Set

Logs registry modifications.

Security Use Cases:

- Persistence Detection
- Registry Abuse

MITRE ATT&CK:

- T1112

---

## Event ID 22

### DNS Query

Logs DNS requests.

Security Use Cases:

- Domain Monitoring
- DNS Tunneling Detection

MITRE ATT&CK:

- T1071.004
