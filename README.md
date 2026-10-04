# Benedict Havertz

### Industrial Maintenance & Workflow Automation

I build workflow automation that is **tested, auditable and privacy-conscious** — from an Outlook add-in to rule-based email automation with cross-platform CI and documented release gates. Background: industrial mechanic in maintenance.

**Portfolio:** [bh-automation.github.io](https://bh-automation.github.io/) · **Screenshots:** [Outlook add-in (mock data)](https://github.com/bh-automation/outlook-command-center/tree/main/SCREENSHOTS)

## Featured projects

### [Outlook Command Center](https://github.com/bh-automation/outlook-command-center)
**Problem:** several status categories per email create chaos. **Solution:** an Outlook task-pane add-in that gives every message exactly one status (ACTION · WAITING · PROJECT · DONE · REFERENCE) — no delete, move or send, minimal `ReadWriteItem` permission, no tracking.

**Proof:** 39/39 browser E2E checks (Playwright with Office.js mock, local run) · logic tests and repository validator in CI · CodeQL · GitHub Pages deployment · Actions pinned to commit SHAs

### [Gmail Automation](https://github.com/bh-automation/gmail-automation)
**Problem:** inbox triage is repetitive but risky to automate. **Solution:** local, rule-based labels and reply drafts for Windows — DRY-RUN by default, sending and deleting blocked in the application, every change audited, with conflict-checked undo.

**Proof:** 356 automated tests · CI on Windows and Ubuntu, Python 3.12 / 3.13, PowerShell 5.1 / 7 · separate read-only and write OAuth profiles · secret scan and static forbidden-API scan as release gates · tagged v1.0.0

## Verified stack

Python · JavaScript · PowerShell · Outlook / Office add-ins · Gmail API · GitHub Actions · CI/CD · automated and E2E testing · CodeQL · GitHub Pages · technical documentation

## How I work

**Understand the process → bound the risk → automate → test → red-team → document → release**

Guardrails, reproducible tests, rollback paths and clear human approval points wherever automation should not make the final decision.

## Current development

Structured training in **AI / automation management** and **project management**, including hands-on workflow automation with n8n *(in progress)*.

---

> Public repositories contain only portfolio-safe material. Production data, credentials and internal third-party data are excluded.
