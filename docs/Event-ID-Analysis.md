# Event Analysis

## Event ID 1 – Process Creation

### Purpose

Tracks execution of processes on Windows systems.

### Observed Activity

- cmd.exe execution
- ipconfig.exe execution
- rundll32.exe execution

### Investigation Fields

- Image
- CommandLine
- ParentImage
- User

### Security Relevance

Threat actors frequently use:

- cmd.exe
- powershell.exe
- wmic.exe
- rundll32.exe

for reconnaissance and execution.

---

## Event ID 3 – Network Connections

### Purpose

Monitors outbound and inbound network activity.

### Observed Activity

- Brave Browser connections
- DNS communication
- Local network discovery

### Investigation Fields

- Source IP
- Destination IP
- Destination Port
- Protocol

---

## Event ID 11 – File Creation

### Purpose

Tracks file creation activity.

### Observed Activity

- Desktop text file creation
- Windows service file generation

### Investigation Fields

- TargetFilename
- Process Image
- User

---

## Event ID 7 – Image Load

### Purpose

Monitors DLL loading activity.

### Observed Activity

- urlmon.dll loaded by taskhostw.exe

### Investigation Fields

- Image
- ImageLoaded
- Hashes
- Signature Status

### Security Relevance

Useful for:

- DLL Hijacking Detection
- Malicious Module Detection
- Malware Analysis
