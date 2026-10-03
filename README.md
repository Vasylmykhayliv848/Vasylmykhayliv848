# Hi, I'm Vasyl

## Cybersecurity & Security Automation

I'm a student of computer systems and networks in Ukraine, and a junior cybersecurity learner and builder.
I learn defensive security by building a real tool: a PowerShell platform that audits Windows security and automates response **safely**, with every critical action approved by a person.

---

## About Me

- Student, computer systems and networks (vocational college, Ukraine)
- Interested in defensive security, Windows security and security automation
- Main language for security work: **PowerShell**
- I care about the parts that make automation trustworthy: policy, evidence, verification, rollback and testing
- Learning mindset: I document what broke, why it broke and how I fixed it

## Main Project

### [AI Audit Center](https://github.com/Vasylmykhayliv848/ai-audit-center)

A Windows security auditing and security automation platform built with PowerShell. It covers detection, risk analysis, evidence, controlled response, verification, rollback, recovery and human-controlled automation.

**Autonomous Security Loop** - a fully integrated defensive security automation pipeline:

```text
Detect → Correlate → Assess Risk → Policy → Decide → Respond → Verify → Recover → Resolve
```

| What | Detail |
|---|---|
| Analyzers | 71 Windows security modules (Defender, Firewall, Services, Scheduled Tasks, Persistence, Event Logs …) |
| Safety model | 44 action types: 13 `SAFE_AUTO` · 15 `APPROVAL_REQUIRED` · 16 `BLOCKED`; default deny, tighten-only policy |
| Human approval | Keyboard-only, one incident / action / target, time-limited, re-checked at execution |
| Evidence | Integrity hashes, chain of custody, hash-chained journals |
| Verification | Expected vs actual state. Action success ≠ security resolved |
| Rollback | Three-way state check (previous / expected / actual) |
| Self-monitoring | Watchdog and Self-Test engines: detect and report, never repair |
| Integration | 20 loop states proven against the orchestrator's 27-state machine; 14 security boundaries checked every run; 20/20 simulated scenarios incl. rollback → recovery |
| Honest metrics | No real remediation has run through the loop yet, so response automation is reported as `NOT_MEASURED` |
| Status | Active development on a personal machine. Not a production product |
| Source | Private; showcase repo is public, code available to employers on request |

## Security Focus

- Defensive Security
- Windows Security
- Security Automation
- PowerShell
- Risk Analysis
- Incident Response (concepts and tooling)
- Security Monitoring

## Technologies

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white)

`PowerShell` · `Windows` · `Git` · `GitHub` · `GitHub Actions` · `JSON` · `Security analysis` · `Automation` · `REST API (read-only)` · `Cisco Packet Tracer`

## Current Focus

- Running the first real, human-approved remediations through the **Autonomous Security Loop**
- Read-only views of the loop for the dashboard and API
- Improving English (target B2) and learning more Windows internals

## Projects

| Project | Description | Status |
|---|---|---|
| [AI Audit Center](https://github.com/Vasylmykhayliv848/ai-audit-center) | Windows security auditing and human-controlled security automation (PowerShell) | Active development |

## Learning

- Windows security internals: Defender, firewall, services, scheduled tasks, event logs
- Threat modeling (STRIDE / DREAD) from my internship report
- Network design with Cisco Packet Tracer (VLANs, Fast Ethernet) from my coursework
- MITRE ATT&CK mapping and detection-rule design

## Contact

- LinkedIn: [vasyl-mykhayliv](https://www.linkedin.com/in/vasyl-mykhayliv-b7bbba415)
- GitHub: [@Vasylmykhayliv848](https://github.com/Vasylmykhayliv848)

<sub>Everything above describes learning projects. I don't claim professional experience, certifications or production deployments.</sub>
