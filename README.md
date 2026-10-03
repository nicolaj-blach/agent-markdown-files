# Agent Markdown Files

Instructions, subagents and skills for coding agents, used by pi through `~/nixos`.

- `AGENTS.md`: global instructions
- `agents/*.md`: subagent definitions (pi-subagents)
- `skills/*/SKILL.md`: skills

After changing a file, push and run `nix flake update agent-markdown-files` in `~/nixos`.
