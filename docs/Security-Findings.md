# Security Findings

## Executive Summary

Analysis of Sysmon telemetry identified normal Windows operating system activity and user-generated actions.

No indicators of compromise were identified during the investigation.

---

## Finding 1

### Process Creation Monitoring

Observed:

- cmd.exe
- ipconfig.exe

Classification:

Legitimate Administrative Activity

Risk Level:

Low

---

## Finding 2

### Network Connections

Observed:

- Brave Browser
- UDP Port 5353

Classification:

Normal mDNS Traffic

Risk Level:

Low

---

## Finding 3

### File Creation Activity

Observed:

Desktop text file creation

Classification:

Authorized User Activity

Risk Level:

Low

---

## Finding 4

### Image Load Activity

Observed:

urlmon.dll

Classification:

Microsoft Signed DLL

Risk Level:

Low

---

## Conclusion

No suspicious activity detected.

System activity appears consistent with expected Windows operations.
