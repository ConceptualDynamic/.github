# Contribution Guidelines

Conceptual Dynamic requires pull requests to declare contribution attribution so team activity can be reported by person, AI tool, agent and subagent.

The goal is measurement and traceability, not limiting who can open pull requests.

Every pull request should include:

- Human owner: GitHub user responsible for the change.
- AI used: yes or no.
- Agent: Claude, Codex, Copilot, Cursor, another AI tool, or none.
- Subagents: backend, frontend, tests, reviewer, documentation, none, or another role.
- Task source: Planner task, GitHub issue, ticket, meeting follow-up or other source.
- Tests run: checks or validation performed.

If no AI was used, use:

```md
AI used: no
Agent: none
Subagents: none
```

Suggested labels:

- `ai-assisted`
- `agent:claude`
- `agent:codex`
- `agent:copilot`
- `subagent:backend`
- `subagent:frontend`
- `subagent:tests`
- `subagent:reviewer`

Suggested branch naming:

- `agent/claude/backend/CD-123`
- `agent/claude/tests/CD-124`
- `human/username/CD-125`

Suggested commit trailers for AI-assisted commits:

```text
Agent: claude
Subagents: backend, tests
Human owner: username
Task source: planner/CD-123
```
