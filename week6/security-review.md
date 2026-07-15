# Week 6 — Security Review: n8n, Zapier & Make.com

## Identity

- **Authentication:** [PLACEHOLDER: MFA options, what you configured]
- **Authorization:** [PLACEHOLDER: team/workspace roles observed]
- **Self-hosted vs. Cloud (n8n specific):** [PLACEHOLDER: if self-hosted, who's responsible for patching/updates? if cloud, who's responsible for the underlying infra?]

## Data Protection

- **Credential Storage:** [PLACEHOLDER: this is the central risk of automation platforms — every connected app's API key/OAuth token lives inside this one tool. How are those credentials stored and protected?]
- **Data-in-transit between connected apps:** [PLACEHOLDER]
- **Execution Logs:** [PLACEHOLDER: do workflow run logs contain the actual data that passed through — e.g. a customer's email address sitting in a log for weeks?]

## Compliance

- **Audit Logs:** [PLACEHOLDER: what's logged — workflow edits, credential changes, execution history]
- **Data Retention in Logs:** [PLACEHOLDER: how long execution history persists, and whether it can be purged]

## Risks

- **Blast radius of a single compromised credential:** [PLACEHOLDER: this is the standout risk for this week — if the automation platform account itself is compromised, how many downstream systems (from Weeks 1–5) does the attacker now have a path into?]
- **Overly broad OAuth scopes on connected apps:** [PLACEHOLDER: same theme as Week 3, but now the automation tool is the thing requesting the scope]
- **Silent failure / error handling:** [PLACEHOLDER: what happens if a step in the workflow fails silently — does sensitive data get stuck somewhere, or does the workflow fail open (e.g. skip a safety check) rather than fail closed?]
- **Webhook exposure:** [PLACEHOLDER: if a webhook URL leaks, can anyone trigger the workflow?]

## Business Recommendations

[PLACEHOLDER: 2–4 concrete recommendations — e.g. principle of least privilege on connected app scopes, periodic credential rotation, monitoring workflow execution logs for anomalies]

## Final Risk Rating

[PLACEHOLDER: Low / Medium / High, with one sentence justifying it — this rating should probably be your highest of the six weeks, given the "single point of failure across the whole stack" nature of automation platforms]
