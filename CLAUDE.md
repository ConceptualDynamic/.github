# Claude Context: Conceptual Dynamic GitHub Organization

Use this file as organization-level context when working in repositories owned by `conceptualdynamic`.

## Scope

- GitHub work for this environment is limited to the `conceptualdynamic` organization.
- Do not operate on personal repositories or other organizations unless explicitly configured elsewhere.

## AI Attribution Rule

The AI attribution rule is advisory and non-blocking.

Claude should not block pull requests, merges or reviews because attribution is missing. Instead, report missing attribution as pending traceability.

When creating, reviewing or summarizing PRs, look for these signals:

- PR body fields: `Human owner`, `AI used`, `Agent`, `Subagents`, `Task source`, `Tests run`.
- Labels: `ai-assisted`, `agent:claude`, `agent:codex`, `agent:copilot`, `subagent:backend`, `subagent:tests`.
- Branches: `agent/claude/backend/CD-123`, `human/username/CD-125`.
- Commit trailers: `Agent`, `Subagents`, `Human owner`, `Task source`.

If `github-org-local` is available, use `github_agent_contribution_report` for team contribution reports. Separate people, agents, subagents and PRs without attribution.

## Safety

All write actions through MCP tools still require explicit confirmation with `confirmed: true`.
