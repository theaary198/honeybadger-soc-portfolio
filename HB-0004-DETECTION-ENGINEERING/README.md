# HB-0004 — Detection Engineering

## Objective
Translate observed SSH intrusion behavior into practical detection content that can be reused across multiple blue team platforms.

## Scenario
This project is based on attacker behaviors observed across earlier Honeybadger SSH investigation cases, including weak credential access, reconnaissance, download activity, and script execution.

## Detection Goals
- Identify high-signal SSH intrusion behaviors
- Convert suspicious activity into reusable detections
- Build platform-specific content for analyst and engineering workflows
- Align detections to attacker behavior and ATT&CK techniques

## Detection Use Cases
- Weak / Default Credential SSH Success
- SSH Login Followed by Reconnaissance
- Download via Command Line
- Download Then Execute
- Repeated Successful SSH Access
- Mixed SSH Activity Requiring Triage

## Included Content

### Sigma
Generic detection rules for SSH intrusion-related behaviors:
- `sigma/ssh_weak_credential_success.yml`
- `sigma/ssh_success_followed_by_recon.yml`
- `sigma/download_then_execute.yml`

### Splunk
Platform-specific SPL searches:
- `splunk/ssh_weak_credential_success.spl`
- `splunk/download_then_execute.spl`

### KQL
Microsoft Sentinel / Defender-style hunting queries:
- `kql/ssh_weak_credential_success.kql`
- `kql/download_then_execute.kql`

## Skills Demonstrated
- Detection engineering
- Sigma rule writing
- Splunk SPL query writing
- KQL query development
- ATT&CK-aligned behavioral detection logic

## Outcome
This project demonstrates the ability to convert attacker tradecraft into practical detections that can support SOC monitoring, threat hunting, and blue team workflows.

