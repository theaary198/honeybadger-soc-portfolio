# Honeybadger SOC Analyst Portfolio

A hands-on blue team portfolio built around SSH intrusion simulations, Cowrie honeypot log analysis, SOC triage workflows, and detection engineering.

This repository demonstrates practical analyst thinking through investigation notes, case reports, detection content, and triage-driven decision making.

---

## Portfolio Overview

This portfolio was built to practice and demonstrate:

- Security log analysis
- IOC extraction
- Session-based triage
- Attack chain reconstruction
- MITRE ATT&CK mapping
- Detection engineering
- Analyst reporting and escalation

---

## Included Projects

### 1. HB-0001 — Local SSH Recon Investigation
**Focus:** SSH intrusion analysis, IOC extraction, attack chain reconstruction, and reporting.

**What this project demonstrates:**
- Parsing Cowrie honeypot logs
- Identifying suspicious command activity
- Building an attack timeline
- Mapping behavior to MITRE ATT&CK
- Writing a complete analyst case report

**Files:**
- `final_case_report.txt`
- `advanced_case_report.txt`

---

### 2. HB-0002 — SSH Authentication Abuse Analysis
**Focus:** Authentication-focused investigation involving repeated successful SSH access using weak/default credentials.

**What this project demonstrates:**
- Authentication log analysis
- Distinguishing brute force from valid account abuse
- Triage and escalation reasoning
- Writing interview-ready investigation summaries

**Files:**
- `triage_notes.txt`
- `interview_answer.txt`

---

### 3. HB-0003 — Mixed SSH Activity Triage
**Focus:** Differentiating benign and malicious SSH activity across multiple sessions.

**What this project demonstrates:**
- Signal vs. noise separation
- Session classification
- Investigation prioritization
- Severity assessment and SOC-style reporting

**Files:**
- `final_soc_report.txt`

---

### 4. HB-0004 — Detection Engineering
**Focus:** Converting observed attacker behavior into reusable detections across multiple platforms.

**What this project demonstrates:**
- Sigma rule writing
- Splunk search creation
- KQL query development
- ATT&CK-aligned detection logic

**Included Content:**
- `sigma/`
- `splunk/`
- `kql/`

---

## Tools and Technologies Used

- Kali Linux
- Cowrie Honeypot
- Linux CLI
- Git / GitHub
- Sigma
- Splunk SPL
- Kusto Query Language (KQL)
- MITRE ATT&CK

---

## Why I Built This

I built this portfolio to move beyond theory and practice the kind of structured investigation and detection work expected in junior SOC and blue team roles.

The goal was to simulate how an analyst would:
- review suspicious activity,
- validate findings,
- prioritize what matters,
- write detections,
- and communicate clearly.

---

## Supporting Files

- `RESUME_BULLETS.txt`
- `INTERVIEW_BULLETS.txt`

These files summarize the strongest portfolio talking points for resume and interview use.

