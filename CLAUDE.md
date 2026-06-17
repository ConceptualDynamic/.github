# Claude Context: Conceptual Dynamic GitHub Organization

Use this file as organization-level context when working in repositories owned by `conceptualdynamic`.

## Scope

- GitHub work for this environment is limited to the `conceptualdynamic` organization.
- Do not operate on personal repositories or other organizations unless explicitly configured elsewhere.

## Required AI Attribution

Pull requests should declare attribution so contribution can be reported by human owner, AI tool, agent and subagent.

Required PR body fields:

- `Human owner`
- `AI used`
- `Agent`
- `Subagents`
- `Task source`
- `Tests run`

If no AI was used, use:

```md
AI used: no
Agent: none
Subagents: none
```

When AI was used, the agent and subagents must name the tool and roles used, for example:

```md
AI used: yes
Agent: claude
Subagents: backend, tests, reviewer
```

If `github-org-local` is available, use `github_agent_contribution_report` for team contribution reports. Separate people, agents, subagents and PRs without attribution.

## Safety

All write actions through MCP tools still require explicit confirmation with `confirmed: true`.
