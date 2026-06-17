# Contribution Guidelines

Conceptual Dynamic allows team members to open pull requests autonomously.

AI attribution is advisory. It is used for reporting and learning how the team contributes, not to block pull requests or merges.

When a pull request includes AI-assisted work, fill the Attribution section when possible:

- Human owner: GitHub user responsible for the change.
- AI used: yes or no.
- Agent: for example Claude, Codex, Copilot, Cursor or another tool.
- Subagents: for example backend, frontend, tests, reviewer or documentation.
- Task source: Planner task, GitHub issue, ticket, meeting follow-up or other source.
- Tests run: checks or validation performed.

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

Missing attribution should be reported as pending traceability, not as a failure. Repository-specific rules may add stronger requirements later, but this organization default is intentionally non-blocking.
