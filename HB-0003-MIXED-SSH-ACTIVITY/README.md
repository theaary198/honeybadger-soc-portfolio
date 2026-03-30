# HB-0003 — Mixed SSH Activity Triage

## Objective
Analyze multiple SSH sessions and separate likely benign activity from suspicious or malicious behavior using session context, source information, and command patterns.

## Scenario
This case simulates a mixed-activity SSH environment where some sessions reflect normal user or internal administrative behavior, while others show clear intrusion patterns.

## Data Source
- Cowrie honeypot session logs
- SSH login success events
- Command execution activity
- File download behavior

## Investigation Goals
- Classify SSH sessions by risk level
- Distinguish benign from malicious activity
- Prioritize investigations based on impact and confidence
- Produce a SOC-style incident assessment

## Key Findings
- Multiple sessions were reviewed across internal and external sources
- Two sessions were classified as suspicious / malicious
- Malicious sessions included weak credentials, recon behavior, download activity, and execution patterns
- Internal sessions appeared lower risk but still required contextual validation

## Skills Demonstrated
- Session-based triage
- Behavioral analysis
- Priority-based investigation
- Severity assessment
- SOC reporting

## Included Files
- `final_soc_report.txt` — full SOC-style triage and incident summary report

## Outcome
This project demonstrates practical analyst judgment under uncertainty and shows how suspicious behavior can be prioritized effectively in a mixed-signal environment.

