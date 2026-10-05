# 02 · Create ads and a website

[← Course home](../README.md) · [Prompt index](../prompts/README.md)

Create reusable task instructions, then use them for three ad concepts and a local offer page.

All input paths below start inside your extracted project folder. Provide the named files in Work, or open that folder as your local Codex project.

## Prompt 03 · Create ad skill

| Before you paste | Your action |
| --- | --- |
| **Open this app** | Local Codex project or ChatGPT Work with the skill file attached |
| **Provide these inputs** | .agents/skills/albert-copper-cup-ad-creative/SKILL.md |
| **Expect this output** | The ad skill is verified or created within the supplied project scope. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/03-create-ad-skill.txt)

```text
Read .agents/skills/albert-copper-cup-ad-creative/SKILL.md as the required skill specification. Create or verify that reusable project skill without changing its name or scope. Confirm it appears in the available skill interface. Leave existing files intact when the supplied definition already satisfies the specification.
```

**Review before continuing.** Confirm the skill name, input files, output folder, and claim-review requirement.

**Next step.** Continue to prompt 04 and run the ad skill.

## Prompt 04 · Run ad skill

| Before you paste | Your action |
| --- | --- |
| **Open this app** | Local Codex project or ChatGPT Work with image-generation access |
| **Provide these inputs** | brand/context.md, briefs/discovery-box-campaign.md, ad-creative SKILL.md, assets/ |
| **Expect this output** | Three concepts, images, generation prompts, alt text, and a review checklist under campaigns/discovery-box/new-run/ads/. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/04-run-ad-skill.txt)

```text
Use the albert-copper-cup-ad-creative skill with briefs/discovery-box-campaign.md. Create three Instagram ad concepts and the corresponding images. Read brand/context.md and reuse assets/ when appropriate. Save outputs to campaigns/discovery-box/new-run/ads/. Return the concepts, images, generation prompts, alt text, and claim-review checklist. Label the campaign fictional and keep it ready for review.
```

**Review before continuing.** Check product, price, shipping, claims, readable text, and all three saved concepts.

**Next step.** Continue to prompt 05 and verify the website skill.

## Prompt 05 · Create website skill

| Before you paste | Your action |
| --- | --- |
| **Open this app** | Local Codex project or ChatGPT Work with the skill definition attached |
| **Provide these inputs** | .agents/skills/albert-copper-cup-website-builder/SKILL.md and design-references.md |
| **Expect this output** | The website skill includes responsive design, a local preview, and form testing. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/05-create-website-skill.txt)

```text
Read the complete website skill definition and design references. Create or verify the reusable website skill with those requirements. Keep the supplied skill name. Confirm a responsive page, a local preview, and form testing form part of its completion criteria.
```

**Review before continuing.** Read the completion criteria and confirm the supplied skill name remains intact.

**Next step.** Continue to prompt 06 and request the offer page.

## Prompt 06 · Dot offer page

| Before you paste | Your action |
| --- | --- |
| **Open this app** | Onigiri in ChatGPT Dot |
| **Provide these inputs** | Discovery Box brief, brand context, website-builder skill, and assets/ |
| **Expect this output** | A one-page offer site, local preview, source files, and a deployment plan under campaigns/discovery-box/new-run/site/. |

Copy the complete text below into the message field and submit it once. Wait for the app to finish before inspecting the returned files.

[Open the copyable text file](../prompts/06-dot-offer-page.txt)

```text
Onigiri, locate the attached Copper Cup project and read briefs/discovery-box-campaign.md. Use the website-builder skill to prepare a one-page Discovery Box offer site. Route the implementation to Codex if that is available in this environment. Keep the output under campaigns/discovery-box/new-run/site/. Show the preview and source files. Prepare the Sites deployment plan for review before any launch.
```

**Review before continuing.** Open the page, check its offer and CTA, and inspect the source files before considering a launch.

**Next step.** Continue to Lesson 3 and define the Growth Strategist.

[Continue to lesson 3 →](03-add-a-growth-strategist.md)
