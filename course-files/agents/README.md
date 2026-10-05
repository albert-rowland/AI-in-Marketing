# Agent Role Files

The Markdown files describe portable roles for ChatGPT Work. Read the selected role and ask Work to delegate to a specialist with those instructions. A Markdown role card alone creates a description, while the delegation prompt starts an agent run.

The corresponding .codex/agents/*.toml files use the documented local Codex schema. They become project-scoped definitions when you open teaching-kit as the primary local project folder. Work Cloud has its own execution environment, so it should receive role files and explicit delegation instructions rather than assume it loads local TOML configuration. Keep the model settings inherited from the parent.
