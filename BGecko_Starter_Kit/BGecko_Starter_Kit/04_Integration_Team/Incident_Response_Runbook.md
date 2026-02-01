# Incident Response Runbook (v0)

## Axioms
- Speed matters, but **containment** matters more than blame.
- Document everything in real time.

## Severity
- SEV0: customer data exposure, active compromise
- SEV1: service outage / payments broken
- SEV2: degraded service / partial outage
- SEV3: minor bug

## Process
1) Detect + triage (what happened, when, impact)
2) Contain (disable keys, rotate creds, lock accounts)
3) Eradicate (remove root cause)
4) Recover (restore services, validate)
5) Learn (postmortem: cause, fixes, prevention)

## Minimal comms
- Single incident channel + single incident commander.
- External updates: factual, short, no speculation.
