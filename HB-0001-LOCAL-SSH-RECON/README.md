# HB-0001 — Local SSH Recon Investigation

## Objective
Investigate suspicious SSH activity captured in Cowrie honeypot logs and document the attacker’s behavior from login through command execution.

## Scenario
This case simulates an SSH intrusion involving successful login with weak credentials, reconnaissance activity, file retrieval, and script execution behavior.

## Data Source
- Cowrie honeypot logs
- SSH session activity
- Command input events
- File download events

## Investigation Goals
- Identify suspicious post-login behavior
- Extract indicators of compromise (IOCs)
- Reconstruct the attack chain
- Map activity to MITRE ATT&CK
- Produce a structured analyst report

## Key Findings
- Successful SSH login using weak credentials: `root:toor`
- Reconnaissance commands executed after login
- File retrieval observed via `wget` and `curl`
- Downloaded file was permission-modified and executed
- HTML content appeared as shell input, indicating anomalous execution behavior

## Skills Demonstrated
- Log triage
- IOC extraction
- Timeline reconstruction
- MITRE ATT&CK mapping
- Analyst reporting

## Included Files
- `final_case_report.txt` — base case investigation report
- `advanced_case_report.txt` — expanded case report with timeline and false positive analysis

## Outcome
This project demonstrates how to take raw SSH activity and turn it into a structured security investigation suitable for junior SOC analyst portfolio work.

