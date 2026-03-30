# HB-0002 — SSH Authentication Abuse Analysis

## Objective
Investigate repeated successful SSH authentication events and determine whether the observed activity represents brute force, valid account abuse, or another authentication-related threat pattern.

## Scenario
This case focuses on repeated successful SSH logins using weak/default credentials and evaluates whether the evidence supports brute-force classification.

## Data Source
- Cowrie honeypot authentication logs
- SSH login success events
- Session correlation data

## Investigation Goals
- Review authentication behavior
- Validate or reject the brute-force hypothesis
- Identify weak/default credential abuse
- Assess risk associated with repeated privileged access
- Document triage and escalation reasoning

## Key Findings
- Multiple successful SSH logins were observed
- Same source IP reused access across sessions
- Same credentials were reused: `root:toor`
- No failed login attempts were present in the dataset
- Activity was more accurately classified as valid account abuse rather than brute force

## Skills Demonstrated
- Authentication log analysis
- Triage reasoning
- Session correlation
- Escalation decision-making
- Investigation communication

## Included Files
- `triage_notes.txt` — SOC-style triage summary and analyst assessment
- `interview_answer.txt` — interview-ready explanation of how the case was handled

## Outcome
This project demonstrates the ability to investigate suspicious SSH access, challenge incorrect assumptions, and communicate findings clearly in an analyst-friendly format.

