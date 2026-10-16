# Coordinate the full marketing team

[← Return to the class guide](../START-HERE.md)

These prompts belong to the single 60-minute session. Use them in the displayed order.

## Prompt 06 · Coordinate the full marketing team

**Inputs**
`AGENTS.md`, `brand/context.md`, `.agents/skills/albert-copper-cup-ad-creative/SKILL.md`, `agents/marketing_lead.md`, `agents/growth_strategist.md`, `agents/content_creator.md`, `agents/creative_designer.md`, `agents/website_designer.md`, `agents/growth_analyst.md`, `campaigns/discovery-box/run-01/strategy.md`, `campaigns/discovery-box/run-01/ad-copy.md`, `campaigns/discovery-box/run-01/visual-brief.md`, `campaigns/discovery-box/run-01/image-prompts.md`

[Copy the full prompt](../prompts/06-coordinate-the-full-marketing-team.txt)

```text
Act as the Marketing Team Lead in this main project conversation. Read AGENTS.md, agents/marketing_lead.md, brand/context.md including Current campaign, all five specialist role cards, the ad skill, and the saved run-01 package. Explicitly coordinate a small campaign package under campaigns/discovery-box/coordinated-01/. Create independent output files so agents avoid editing one shared file.
First ask the Growth Strategist to confirm a campaign direction and acceptance criteria from the existing strategy. After that result, delegate these independent assignments using the confirmed direction and existing reviewed inputs. The Content Creator prepares three draft social posts. The Creative Designer prepares a visual brief and image prompt for the campaign. The Website Designer creates an editable static offer-page.html with a local preview and supported offer copy, with payment and lead collection absent. The Growth Analyst reviews the synthetic data below, showing CTR, lead conversion, cost per lead, and cost per order with denominators and objective caveats. Respect the client's concurrency limits and queue tasks when needed. The main conversation waits for the specialist outputs and merges the result.
Save this supplied fictional data as data/classroom-campaigns.csv before the analyst reads it:
campaign,objective,spend_usd,impressions,clicks,landing_visits,leads,orders
Brew guide,Lead acquisition,400,40000,1000,720,144,18
Discovery Box,Purchase,800,50000,1250,900,54,48
Use CTR = clicks / impressions * 100; lead conversion = leads / landing_visits * 100; CPL = spend_usd / leads; cost per order = spend_usd / orders. Leads and orders measure different outcomes. Different objectives and the absence of randomized assignment prevent a causal comparison. Revenue and profit are unspecified.
Review the actual saved files against the brand, Current campaign section, price, shipping, CTA, source evidence, and channel fit. Assign a specific revision to its owning specialist if needed, then recheck. Save review.md and handoff.md with actual files, task references or fallback labels, checked calculations, gaps, and the next human decision. Hold image-generation charges and external actions for separate decisions.
Use explicit subagent assignments when supported. Use the named local Codex role or pass its complete Markdown instructions to an available worker. In Work, supply accessible files and explicitly delegate. Return actual task activity or references and output paths. If delegation is unavailable, label the result a sequential role-based draft. A role definition alone is not an agent execution receipt.
Keep this classroom task inside the selected project. Prepare draft files only. Hold external sends, publication, scheduling, spending, deletion, and permission changes for a separate human decision. If file tools are unavailable, return downloadable files or full copyable text and name the missing file access. Report saved files separately from proposals.
```

**Expected result**
`data/classroom-campaigns.csv`, `campaigns/discovery-box/coordinated-01/strategy.md`, `campaigns/discovery-box/coordinated-01/social-posts.md`, `campaigns/discovery-box/coordinated-01/visual-brief.md`, `campaigns/discovery-box/coordinated-01/image-prompts.md`, `campaigns/discovery-box/coordinated-01/offer-page.html`, `campaigns/discovery-box/coordinated-01/findings.md`, `campaigns/discovery-box/coordinated-01/review.md`, `campaigns/discovery-box/coordinated-01/handoff.md`.

**Check before continuing**
Inspect the separate agent assignments, static page preview, one calculation, and the merged review. A running status remains separate from a checked result.
