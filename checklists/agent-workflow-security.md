# Agent Workflow Security Checklist

## System definition
- [ ] Define the user goal the agent is allowed to pursue.
- [ ] List every tool, API, data source, and output channel.
- [ ] Identify which actions are read-only, write-capable, external-facing, or irreversible.

## Trust boundaries
- [ ] Separate user instructions, system instructions, retrieved data, tool output, and memory.
- [ ] Treat web pages, documents, emails, tickets, and tool descriptions as untrusted input.
- [ ] Define what data the agent may never reveal or move.

## Permissions
- [ ] Use least privilege per tool.
- [ ] Avoid shared human credentials where possible.
- [ ] Require human approval for payments, deletion, publication, external messages, and privilege changes.

## Monitoring
- [ ] Log tool calls, arguments, results, user approvals, and final outputs.
- [ ] Alert on unusual tool chains, external egress, repeated failures, and policy overrides.

## Release gate
- [ ] Run safe prompt-injection tests.
- [ ] Review with a second human for high-impact workflows.
- [ ] Document known limitations.
