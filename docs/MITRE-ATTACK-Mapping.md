# MITRE ATT&CK Mapping

## Event ID 1 – Process Creation

Observed:

- cmd.exe
- ipconfig.exe

MITRE Techniques:

- T1059 – Command and Scripting Interpreter
- T1016 – System Network Configuration Discovery
- T1033 – System Owner/User Discovery

---

## Event ID 3 – Network Connections

Observed:

- Browser network communication

MITRE Techniques:

- T1071 – Application Layer Protocol

---

## Event ID 11 – File Creation

Observed:

- New file creation

MITRE Techniques:

- T1074 – Data Staged

---

## Event ID 7 – Image Load

Observed:

- DLL loading activity

MITRE Techniques:

- T1574 – Hijack Execution Flow

---

## Event ID 22 – DNS Query

Observed:

- DNS Resolution Activity

MITRE Techniques:

- T1071.004 – DNS

---

## ATT&CK Coverage Summary

| Event ID | ATT&CK Technique |
|-----------|----------------|
| 1 | T1059 |
| 1 | T1016 |
| 1 | T1033 |
| 3 | T1071 |
| 7 | T1574 |
| 11 | T1074 |
| 22 | T1071.004 |
