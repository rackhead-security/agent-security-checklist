# Tool-Use Security Checklist

- [ ] Inventory tools and owners.
- [ ] Pin versions and review provenance.
- [ ] Treat tool names, descriptions, schemas, and outputs as untrusted data.
- [ ] Validate arguments before execution.
- [ ] Use allowlists for hosts, file paths, commands, and API scopes.
- [ ] Add timeouts, rate limits, and budget limits.
- [ ] Require approval for destructive or external actions.
- [ ] Log tool calls in a reviewable format.
- [ ] Test for confused-deputy flows: read from private source, write to public sink.
