# Incident Response Recommendations

## Process Monitoring

Monitor for:

- powershell.exe
- cmd.exe
- wscript.exe
- mshta.exe
- rundll32.exe

Investigate unusual command-line arguments.

---

## Network Monitoring

Monitor:

- Unknown external IP addresses
- High-volume outbound traffic
- Rare destination ports

Implement network traffic baselines.

---

## File Monitoring

Investigate:

- Executables in Temp directories
- Startup folder modifications
- Unexpected file creation activity

---

## DLL Monitoring

Validate:

- DLL signatures
- DLL load paths
- Unsigned modules

Investigate DLLs loaded outside trusted directories.

---

## DNS Monitoring

Monitor:

- Excessive DNS requests
- Suspicious domains
- Dynamic DNS providers

---

## Logging Improvements

- Deploy Sysmon enterprise-wide
- Centralize logs using SIEM
- Enable alerting for high-risk events
- Implement MITRE ATT&CK-based detections

---

## Conclusion

Continuous monitoring of Sysmon telemetry significantly improves threat detection, incident response, and visibility into Windows system activity.
