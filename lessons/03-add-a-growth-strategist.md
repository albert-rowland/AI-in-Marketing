# 03 · Add a Growth Strategist

[← Course home](../README.md) · [Prompt index](../prompts/README.md)

Delegate a strategy decision and check its reasoning against the synthetic campaign data.

All input paths below start inside your extracted project folder. Provide the named files in Work, or open that folder as your local Codex project.

## Prompt 07 · Create growth agent

| Before you paste | Your action |
| --- | --- |
| **Open this app** | Local Codex project or ChatGPT Work |
| **Provide these inputs** | agents/growth_strategist.md and .codex/agents/growth_strategist.toml |
| **Expect this output** | A verified local role or an explicitly delegated Work specialist using the Markdown role. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/07-create-growth-agent.txt)

```text
Read agents/growth_strategist.md and the corresponding .codex/agents/growth_strategist.toml. In a local Codex project, verify the TOML definition loads. In ChatGPT Work, use the Markdown role as specialist instructions for an explicit delegated task. Confirm its role, inputs, output, and approval boundary. Keep model settings inherited from the parent.
```

**Review before continuing.** Confirm role, inputs, outputs, and approval boundary.

**Next step.** Continue to prompt 08 and request the strategy.

## Prompt 08 · Growth goal

| Before you paste | Your action |
| --- | --- |
| **Open this app** | ChatGPT Work or a local Codex project with delegation available |
| **Provide these inputs** | Growth Strategist role, Discovery Box brief, data/past-campaigns.csv, data/metric-definitions.md |
| **Expect this output** | strategy.md and experiment-brief.md under campaigns/discovery-box/new-run/strategy/. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/08-growth-goal.txt)

```text
Delegate to a Growth Strategist using agents/growth_strategist.md. Read the Discovery Box brief and synthetic past-campaigns.csv with metric-definitions.md. Recommend a launch campaign and a bounded experiment. Save strategy.md and experiment-brief.md under campaigns/discovery-box/new-run/strategy/. Cite input paths and distinguish data findings from recommendations. Wait for the specialist result before returning the reviewed strategy.
```

**Review before continuing.** Recalculate the quoted metrics and distinguish data findings from recommendations.

**Next step.** Continue to Lesson 4 and define the Content Creator.

[Continue to lesson 4 →](04-prepare-social-content.md)
