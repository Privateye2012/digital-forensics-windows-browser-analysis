## Digital Forensics – Windows & Browser Artifact Analysis

### Overview
This repository documents a hands-on digital forensics laboratory focused on
the analysis of Windows system artifacts, web browser data, and malicious
browser extensions.

The activity was developed as part of the Digital Forensics and Cyber Threat
Intelligence microcredential (Week 2).

The original forensic report is written in Portuguese, as the course was taught
in Portuguese. This repository exists to demonstrate practical forensic skills,
methodology, and analytical reasoning in a controlled academic environment.

---

### Objectives
- Identify and analyze Windows forensic artifacts
- Investigate browser activity and user behavior
- Detect malicious browser extensions
- Identify cryptomining activity in web browsers
- Trace malware delivery through browser and email artifacts
- Apply forensic best practices in evidence analysis

---

## Lab Environment
- Analysis System: Windows forensic image
- Analysis Tools:
  - FTK Imager (read-only mode)
  - Notepad++ (manual artifact inspection)
  - Browser artifact viewers
- Evidence Type:
  - Browser data
  - User profiles
  - Installed extensions
  - Downloaded executables

All analysis was performed using forensic copies to preserve evidence integrity.

---

## Windows & Browser Artifact Analysis

### User Profiles
- Identified multiple user profiles within Google Chrome
- Verified default and additional profiles through directory structure analysis

### Browser Configuration
- Analyzed Chrome preference files
- Identified installed themes and extensions through configuration inspection

---

## Malicious Extension Investigation

### Extension Identification
- Located suspicious browser extension directories
- Identified extension ID associated with cryptomining activity

### Extension Analysis
- Inspected manifest.json and JavaScript files
- Confirmed cryptominer functionality through code inspection
- Identified external mining script loading behavior

### Cryptomining Details
- Determined hashing rate configuration
- Identified public key associated with mining activity
- Traced communication with external mining services

---

## Email & Malware Delivery Analysis

### Malware Origin
- Identified suspicious executable disguised as a PDF file
- Correlated file execution with browser download artifacts

### Browser History Analysis
- Traced malicious download URL
- Identified browsing sequence leading to infection

### Email Correlation
- Analyzed email content suggesting social engineering
- Identified mismatched link text and destination URL

---

### Key Findings
- Browser extensions can be abused for covert cryptomining
- User interaction remains a critical infection vector
- Browser and email artifacts provide strong forensic timelines
- File naming deception plays a major role in malware delivery

---

### Ethical Considerations
- All analysis was performed in a controlled academic environment
- No real users or production systems were involved
- Malware samples were analyzed strictly for educational purposes
- Evidence integrity and forensic best practices were respected

---
