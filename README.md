# awesome-enterprise-ai-agents

Production-grade, open-source AI agents for **enterprise operations** — the HR, Finance and IT workflows where mistakes cost money and trust.

Most agent demos stop at "it works on my laptop." These are built to the bar an enterprise would actually deploy: every agent is evaluated, audited, governed by policy, and pauses for human approval before anything irreversible.

## What every agent ships with
- **LLM evaluation** — golden test cases and an eval runner, so quality is measured, not claimed
- **Human-in-the-loop approvals** — a gate before any payment, access grant or employee-record change
- **Guardrails and policy rules** — what the agent may and may not do, defined in config
- **Audit log** — every decision and tool call traceable
- **MCP integrations** — mock ERP and HRIS systems exposed as MCP servers, seeded with a synthetic company

## Planned agents
| Domain | Agent | Workflow automated |
|---|---|---|
| Finance | AR collections | Prioritise overdue invoices, draft follow-ups, escalate |
| Finance | AP 3-way match | Match PO, receipt and invoice; flag exceptions |
| HR / Finance | Payroll reconciler | Reconcile payroll runs against invoices, GL entries and payouts; flag mismatches |
| HR | Contractor classification screener | Flag misclassification risk before onboarding |
| IT | Access requests | Triage and route access requests by policy |

## Status
🚧 Building in public. First agent (AR collections) lands the week of Nov 23.

## License
Apache-2.0

Built by Vaibhav, Senior Product Manager building agentic AI for enterprise operations · [LinkedIn](https://www.linkedin.com/in/vaibhavgoelproduct/)
