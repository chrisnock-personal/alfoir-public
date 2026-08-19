# Alfoir

**A testing, monitoring, and script orchestration platform, with AI
woven in throughout rather than bolted on.**
*Test Everything, Automate Anything.*

Alfoir runs checks against servers, APIs, services, devices, and
networks - on a schedule, on demand, or triggered by a webhook or SNMP
trap ,and turns the results into trends, alerts, and a clearer picture
of what's actually happening.

---

## Highlights

- **Write checks in Python, Bash, JavaScript, TypeScript, or Playwright**,
  chain them into branching flows, and run them locally or on lightweight
  remote agents - reach internal systems, test from multiple network
  locations, or fan a check out across a fleet at once.
- **100+ ready-made checks** across databases, Linux/Windows hosts,
  containers & Kubernetes, web/app servers, HashiCorp, cloud platforms,
  CI/CD, and more, deploy with one click, or write your own.
- **Telemetry, not just pass/fail** -scripts report named attributes over
  time, with per-target history, fleet-wide breach views, and one-click
  thresholds.
- **Custom dashboards** built from composable widgets, system metrics or
  any telemetry attribute, scoped to a target, a group, or the whole
  fleet.
- **Alerting across six channels** - webhooks, email, Pushover, Slack,
  PagerDuty, and Zendesk, with maintenance windows, silent mode, and
  per-rule cooldowns to keep noise down.
- **A public status page** with grouped "service" rollups (worst-of, or
  "N of M up"), disabled by default until an admin turns it on.
- **AI assistance throughout**, optional and provider-configurable
  (Anthropic or a self-hosted model):
  - Draft or edit a script from a plain-English description
  - Describe what you want monitored and land in a ready-to-save
    automation, matched against the existing catalog or drafted fresh
  - Explain why a check failed , or what a passing check actually
    verified - using its output and recent telemetry
  - Suggest which catalog checks are worth deploying for newly
    discovered targets
  - Summarize telemetry, logs, alarms, and audit activity into a short
    digest
  - Every AI feature proposes text for review - nothing is ever saved or
    actioned without a human clicking to confirm it
- **Security by default** - TLS-only (self-signed out of the box, or
  bring your own cert), integration secrets encrypted at rest, role-based
  access, SSO (Microsoft Entra ID) and LDAP/Active Directory login, and a
  full audit log.
