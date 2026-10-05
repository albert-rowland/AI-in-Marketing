# Your course project

[← Return to the course](../README.md)

Open this folder as the primary project for local Codex. In Work, attach the folder or the files listed in the lesson guide. All prompt file paths begin here.

| Folder or file | Your use |
| --- | --- |
| [brand/context.md](brand/context.md) | Read the fictional product, audience, offer, palette, and claims. |
| [briefs/](briefs/) | Choose the Discovery Box or brewing-guide campaign. |
| [data/](data/) | Compare four synthetic campaigns using the supplied definitions. |
| [agents/](agents/) | Read six portable specialist and team-lead role cards. |
| [.codex/agents/](.codex/agents/) | Load project-scoped agent definitions in local Codex. |
| [.agents/skills/](.agents/skills/) | Read eight reusable task specifications. |
| [prompts/](prompts/) | Copy the sixteen course prompts. |
| [assets/](assets/) | Reuse the supplied fictional coffee artwork. |
| [campaigns/discovery-box/rehearsal/](campaigns/discovery-box/rehearsal/) | Inspect prepared ads, strategy, social posts, and offer page. |
| [campaigns/lead-magnet/rehearsal/](campaigns/lead-magnet/rehearsal/) | Inspect the brewing guide, calculations, and download page. |
| [AGENTS.md](AGENTS.md) | Read context, routing, output, and review instructions. |

## Preview the campaign examples

Open the offer page's `index.html` in your browser to inspect its layout. Open the guide PDF directly to review its ten pages. For the download-page form and relative links, ask Codex to serve a local preview using the prompt below. The sample form accepts an example address and reveals a PDF link, with production storage outside this classroom example.

Open course-files in Codex and paste this preview request. The two page paths below begin inside that project folder.

```text
Start a local preview from this course-files project folder. Serve only these supplied course files on localhost. Open campaigns/discovery-box/rehearsal/site/index.html and campaigns/lead-magnet/rehearsal/site/index.html. Keep the browser preview local. Confirm the guide link resolves. Test a malformed address and learner@example.com in the classroom form, then report validation results. Keep deployment and address storage outside this preview.
```

## Save your practice results

Preserve the supplied `rehearsal` folders for comparison. The prompts save generated outputs to `new-run` or `learner-exercise` folders. Review the files returned by the app before continuing.

The local TOML roles apply to Codex. Work uses the portable Markdown roles with explicit delegation instructions. A role file describes the specialist, while a delegation request starts the task.
