# D431-WGU-Digital-Forensics
# D431 – Digital Forensics (WGU)

**Student:** Sara Goodie  
**Date:** March 2024  
**Course:** D431 – Digital Forensics  
**Program:** Western Governors University

---

## Repository Contents

| File | Description |
|------|-------------|
| `SaraG_Task1_D431.docx` | **Task 1** – Cybercrime Investigation Plan (written analysis) |
| `Sara_G_Task2D431.docx` | **Task 2** – Hands-On Autopsy Forensic Lab (John Smith case) |

---

## Task 1 – Cybercrime Investigation Plan

A written forensic investigation plan based on a scenario involving a suspected insider threat ("John Smith") at an oil company. Covers all phases of a digital forensic investigation:

| Section | Topic |
|---------|-------|
| **A1** | Incident triage and planning – initial meeting with management and legal; scoping who, what, where |
| **A2** | Evidence collection – tools used: FTK Imager, Volatility, Splunk, MD5/SHA-256 hashing, Autopsy, Grep |
| **A3** | Chain of custody and ISO/IEC 27037 compliance – standardized evidence preservation and documentation |
| **A4** | Timeline reconstruction – Splunk logs, Wireshark network forensics, email examination, security footage cross-referencing, NDA/AUP review |
| **A5** | Drawing conclusions – piecing together system logs, access controls, and network forensics to identify the culprit |
| **A6** | Presentation of findings – PowerPoint for senior management, Chain of Custody documentation, ISO/IEC 27037 adherence |
| **B** | References – Easttom (2021), Professor Messer Security+ |

---

## Task 2 – Hands-On Autopsy Forensic Lab

A step-by-step practical lab using **Autopsy** digital forensics software to analyze a disk image (`JSmith_Q1.001`) taken from John Smith's workstation.

### Lab Setup
- **Case directory:** `C:\Users\LabUser\Desktop\Evidence Files`
- **Case number / Examiner ID:** 377031666
- **Data source type:** Disk Image / VM file
- **Disk image:** `JSmith_Q1.001`
- **Export path:** `C:\Users\LabUser\Desktop\Evidence Files\J.Smith_Investigation\Export`

### Key Findings

| Finding | Detail |
|---------|--------|
| **Deleted files** | 12 deleted files recovered from John Smith's workstation |
| **Images** | 379 images found on the disk image |
| **PDFs** | 11 PDFs found; several matched deleted files |
| **Confidential documents** | "23-Drilling Methodology.pdf" – detailed proprietary oil drilling methods |
| **Business records** | "21-Business Strategy.pdf" – confidential 2021 company business strategy |
| **Metadata owner** | Files trace back to "Mike Morris" (likely document owner) |
| **Keyword hits** | Searches for "confidential" and "restricted" confirmed unauthorized access |
| **Cryptocurrency** | Article on anonymous crypto transactions found: "The best way to hide something, in plain sight. Crypto laundering" (Daily Fintech) |

### Conclusion

John Smith was found **in violation** of both:
- **Non-Disclosure Agreement (NDA)** – accessed and possessed confidential proprietary documents he had no authorization to view
- **Acceptable Use Policy (AUP)** – researched methods for anonymous cryptocurrency transactions, indicating potential financial misconduct

---

## Tools Referenced

| Tool | Purpose |
|------|---------|
| **Autopsy** | Primary forensic analysis platform; disk image examination, file recovery, keyword search |
| **FTK Imager** | Disk imaging; file metadata (creation/modification dates, author, file size) |
| **Volatility** | Volatile memory analysis; running processes, network connections, hidden code |
| **Splunk** | Log analysis; system/application events, unauthorized access logs |
| **Wireshark** | Network forensics; packet capture and network log analysis |
| **Grep** | Command-line keyword search within evidence files |
| **MD5 / SHA-256** | Cryptographic hashing for evidence integrity verification |

---

## Standards & References

- **ISO/IEC 27037** – Guidelines for identification, collection, acquisition and preservation of digital evidence
- Easttom, C. (2021). *Digital forensics, investigation, and response*. Jones & Bartlett Learning.
- Messer, P. (2021, October 6). *Digital Forensics – SY0-601 CompTIA Security+ : 4.5*. Professor Messer IT Certification Training Courses.

---

*All work is original and based on WGU D431 Digital Forensics course materials and lab environments.*
