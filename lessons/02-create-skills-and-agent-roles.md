# Create a skill and the six roles

[← Return to the class guide](../START-HERE.md)

These prompts belong to the single 60-minute session. Use them in the displayed order.

## Prompt 02 · Create the reusable ad skill

**Inputs**
`AGENTS.md`, `brand/context.md`

[Copy the full prompt](../prompts/02-create-the-reusable-ad-skill.txt)

```text
Read AGENTS.md, brand/context.md, and the Current campaign section in brand/context.md. Create only .agents/skills/albert-copper-cup-ad-creative/SKILL.md. Include valid YAML frontmatter with name: albert-copper-cup-ad-creative and a description that triggers for Copper Cup ad copy, ad concepts, visual briefs, and image prompts.
The process should read the brand and brief, select an audience need, draft three copy options unless the assignment requests one, check each product claim against the source, propose visual direction and image prompts, and return a review checklist. Separate copy drafting from artwork generation. Keep image creation optional and subject to available tools and account permissions. Text drafts and image prompts are sufficient for this class. Name the saved campaign output directory and hold external actions for human review.
Explain the frontmatter name and description, then show the process headings and completion criteria. Saving this process does not start a specialist task. Show the saved file path and how to ask the next task to read this skill explicitly. Stop after creating and explaining the skill.
Keep this classroom task inside the selected project. Prepare draft files only. Hold external sends, publication, scheduling, spending, deletion, and permission changes for a separate human decision. If file tools are unavailable, provide the full named files as downloadable files or copyable text and explain how I can save them. Report actual saved files separately from proposed files.
```

**Expected result**
`.agents/skills/albert-copper-cup-ad-creative/SKILL.md`.

**Check before continuing**
Open SKILL.md, locate name and description between --- lines, and identify the source check and completion criteria.

## Prompt 03 · Create the marketing team roles

**Inputs**
`AGENTS.md`, `brand/context.md`, `.agents/skills/albert-copper-cup-ad-creative/SKILL.md`

[Copy the full prompt](../prompts/03-create-the-marketing-team-roles.txt)

```text
Read AGENTS.md, the brand context, its Current campaign section, and ad skill. Create six portable Markdown role cards under agents/ with these filenames and responsibilities.
marketing_lead.md coordinates the assignment, reads specialist outputs, resolves conflicts against sources, and returns a checked handoff and human decision. growth_strategist.md proposes an audience hypothesis, three ad angles, and a recommended test without promising results. content_creator.md turns the approved direction into headlines, body copy, and the supported CTA using the ad skill. creative_designer.md creates a visual brief, image prompts, and planned alt text using the approved copy and palette.
Add website_designer.md to own a local offer-page preview and source files. Add growth_analyst.md to own formula-based synthetic-data findings and limitations.
Give every role six fields: owns, inputs, may do, asks before, when unsure, and done when. State the output filenames for each role. Require AGENTS.md, brand/context.md, and the Current campaign section to be read. A role card describes a job; a later explicit assignment starts an agent task.
If this is local Codex with project-file access, also create matching .codex/agents/marketing_lead.toml, growth_strategist.toml, content_creator.toml, creative_designer.toml, website_designer.toml, and growth_analyst.toml. Each standalone file must contain name, description, and developer_instructions. Use the documented current schema and inherit model settings and permissions. Read the role card within developer_instructions. Explain the six role names and how to start a new chat or refresh the client if the saved definitions are absent. In Work Cloud, use the Markdown cards with explicit delegation instead of assuming that local TOML files register there. Keep this response to role creation and inspection, then wait for prompt 04.
Keep this classroom task inside the selected project. Prepare draft files only. Hold external sends, publication, scheduling, spending, deletion, and permission changes for a separate human decision. If file tools are unavailable, provide the full named files as downloadable files or copyable text and explain how I can save them. Report actual saved files separately from proposed files.
```

**Expected result**
`agents/marketing_lead.md`, `agents/growth_strategist.md`, `agents/content_creator.md`, `agents/creative_designer.md`, `agents/website_designer.md`, `agents/growth_analyst.md`, `.codex/agents/marketing_lead.toml`, `.codex/agents/growth_strategist.toml`, `.codex/agents/content_creator.toml`, `.codex/agents/creative_designer.toml`, `.codex/agents/website_designer.toml`, `.codex/agents/growth_analyst.toml`.

**Check before continuing**
Inspect one role card and its local TOML wrapper. Explain each specialist output before starting an assignment.
