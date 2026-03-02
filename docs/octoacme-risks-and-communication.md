# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution (Technical Lead, Security Champion flag technical/security risks; Support/Customer Success raises user-impact risks)
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans (Security Champion leads security mitigations)
- Monitor: review at weekly syncs and update status (PM, Technical Lead, Security Champion attend risk reviews)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Support/Customer Success representative receives pre-release briefings to prepare user-facing communications
- Security Champion is included on any communications related to security vulnerabilities or security-related releases

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, Security Champion leads triage and follows the security incident runbook; notify Security on-call immediately
- Support/Customer Success escalates user-impacting issues to PM and Product Manager for prioritization
