# Agent Markdown Files

Instructions, subagents and skills for coding agents, used by pi through `~/setup/nixos`.

- `AGENTS.md`: global instructions
- `agents/*.md`: subagent definitions (pi-subagents)
- `skills/*/SKILL.md`: skills
- `assistant.md`: system prompt for the assistant popup (`pi-assistant`, Mod+A)

After changing a file, push and run `nix flake update agent-markdown-files` in `~/setup/nixos`.
