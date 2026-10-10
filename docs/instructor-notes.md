# Instructor notes

[← Return to the course](../README.md)

Every slide follows the uploaded teaching template. Copy each complete prompt between its BEGIN and END markers.

## Slide 01 · Build Your AI Marketing Team with Agents

TEACHING SCRIPT
This session follows a fictional coffee campaign through reusable skills and a specialist agent team. We will build draft ads, inspect an offer page, and coordinate social content before reviewing a lead-generation package. You will adapt one ad during the guided exercise. Every coffee product and campaign figure belongs to our classroom example. Human review governs the publishing decision throughout the lesson.

CLASSROOM ACTION
Open the Google Slides deck and the course-files project folder. Keep the rehearsal pages available in browser tabs.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

Github: https://github.com/albert-rowland/AI-in-Marketing

## Slide 02 · Your 60-minute course route

TEACHING SCRIPT
We will give Copper Cup a shared brief, create reusable skills, and define specialist responsibilities. You will watch the campaign handoffs before creating one ad concept in the ten-minute exercise. We will review the evidence and identify the decisions that remain with you. The voice demonstration adds a task link and written result so you can inspect the handoff after the conversation.

CLASSROOM ACTION
Ask learners to name one marketing task they want an agent to prepare. Take one response and connect it to the campaign examples.

TEACHING TIME
Allow one minute for teaching. The guided exercise receives ten minutes within the 60-minute lesson.

## Slide 03 · Work, Codex, and Dot

TEACHING SCRIPT
Grace uses Work for business deliverables and Codex for code and website implementation. Dot provides an ongoing coordination layer and can use connected projects and tools. These roles overlap, so treat this map as a starting guide. In our example, Work prepares the campaign, Codex can implement its page, and Dot coordinates the request. Account features and permissions determine which handoffs are available.

CLASSROOM ACTION
Point to the three roles and trace the offer-page request across them. Explain that each role name describes responsibility within the available products.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 1 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 00:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

UPDATED PRODUCT GUIDANCE
A Dot can start cloud threads and local Work or Codex tasks, then return progress in its conversation. Local files and local skills require the connected computer to stay online with the app open. A messaging connection supplies a contact channel, while app and computer connections supply separate capabilities. Official guidance checked October 10, 2026. https://learn.chatgpt.com/docs/dots

## Slide 04 · Accounts and access

TEACHING SCRIPT
Check access before learners arrive. Dot availability depends on plan, region, rollout, and workspace settings. Slack, Notion, and local project access each require their own connections. Those connections have separate permissions. Our full demonstration follows Grace’s tools. Learners can observe the Dot steps and use an available project chat for the ad exercise if their account lacks that feature. Prepared outputs keep the lesson moving.

CLASSROOM ACTION
Open setup-checklist.md and check each available feature. Reference slide 33 contains the current eligibility detail.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 01:20.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 05 · Onigiri receives the campaign role

TEACHING SCRIPT
Our demo Dot is called Onigiri. Give Onigiri the project, its responsibility, and a clear review boundary. The request tells Onigiri where to return decisions and which outputs to prepare. The cloud computer can continue without your laptop, while local files and skills require the relevant connected computer to remain available. Slack gives you another messaging channel, with separate access to the project and its tools.

CLASSROOM ACTION
Read prompt 02 and demonstrate the Dot profile connection choices if your account supports them. Confirm the project before requesting a task.

RECORDING CHECKLIST
Suggested clip length 30 seconds.
Open ChatGPT with your attached project. Paste Prompt 02 into your project. Show the confirmed project path and available connections.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/02-dot-setup.mp4.

COPYABLE PROMPT 02
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 02
Your name for this exercise is Onigiri. Coordinate the fictional Copper Cup marketing project that I attach. Prepare drafts and local previews, and bring review decisions to me in ChatGPT. Read AGENTS.md and brand/context.md before acting. Use connected tools only within their permissions. Ask before scheduling, sending, deploying, collecting leads, or spending. Confirm the project path and available connections. This request establishes a classroom role for the current project, with future recurring duties requiring a stated cadence.
END PROMPT 02
```

EXPECTED RESULT
Project role, available connections, and clear review boundaries.

TEACHING TIME
Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 01:20.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 06 · One lead and five specialists

TEACHING SCRIPT
The team has six roles, a lead and five specialists. Grace describes five specialist agents beneath a marketing team lead, so we show that structure explicitly. Onigiri coordinates access and requests outside the project. The lead reconciles the assembled campaign. Each specialist has a defined responsibility and a named output. You can begin with the strategist and content creator, then add roles when the campaign needs their judgment.

CLASSROOM ACTION
Open the supplied agent inventory file. Show the six Markdown roles and the matching local Codex TOML files. Explain that a role card needs an explicit delegation request to start a run.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 1 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:03.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 07 · Copper Cup campaign context

TEACHING SCRIPT
Copper Cup gives us one consistent company for the entire lesson. Its Discovery Box contains three 100 g bags with different roast styles. The price and shipping are fictional training inputs. We will keep those details consistent across ads, pages, and posts. The audience description is a hypothesis, so our strategy should explain how we would test it. Brand context defines the facts the agent can use.

CLASSROOM ACTION
Open the brand context and Discovery Box brief. Highlight the offer, audience, CTA, and unsupported-claim boundary.

COPYABLE PROMPT 01
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 01
Read this Copper Cup teaching-kit folder as the source for a fictional marketing project. Inspect brand/context.md, AGENTS.md, and the two briefs. Confirm the product, audience, offer, skill paths, and output structure. Report missing inputs before generating campaign assets. Keep the supplied rehearsal outputs separate from new runs.
END PROMPT 01
```

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 08 · Voice starts the task and leaves a written result

TEACHING SCRIPT
Voice provides another way to give Onigiri the campaign assignment. Name the prepared project and request a separate Codex task. Onigiri should leave the task link, status, saved result, and pending decision in this conversation. A running status describes progress, while completion requires checking the output against the brief. Local tasks require an available connected computer. Ending the call can leave assigned tasks running, so inspect Activity and Scheduled separately when stopping tasks. The recording shows a bounded draft handoff, and the classroom uses the prepared output if access is absent.

CLASSROOM ACTION
Use a prepared recording for this demonstration. Open the written result beside the conversation and compare it with the supplied Copper Cup brief.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Open the prepared Copper Cup project and confirm that the connected computer is online. Start a Dot call or use text. Paste Follow-up E and show the separate task. Display its written link and status, then cut to completion. Compare the USD 29 price and USD 5 shipping with the source brief. End with the checked output path and pending decision.
Record at 1920 by 1080. Hide unrelated chats and account details. Cut generation waiting time and hold the checked result for five seconds.

INSERT RECORDING
Replace the label shapes inside the large frame with your Google Drive recording. Keep the marked 16:9 frame and the quarter-width prompt panel. Save the recording as recordings/E-voice-codex-handoff.mp4.

COPYABLE FOLLOW-UP PROMPT E
Paste this full prompt into your Dot conversation, or read it during the call. Select the text between the two markers.

```text
BEGIN PROMPT E
Use the prepared Copper Cup Coffee project on my connected computer. Start a separate Codex task in that project to draft a one-page campaign handoff from brand/context.md and briefs/discovery-box-campaign.md. Include the supported product, audience hypothesis, price, shipping, outputs, review owner, and next action. Keep outputs inside the project and hold external sends, publication, spending, deletion, and permission changes. In this Dot chat, post the task link, current status, output path, and missing inputs. After completion, inspect the draft against its sources and post the checked result and pending decisions here. If the computer, project, or task capability is unavailable, explain the missing access and return a draft handoff in this conversation.
END PROMPT E
```

EXPECTED RESULT
A sourced draft handoff plus a written task link, completion status, and review checkpoint.

TEACHING TIME
Allow 2 minutes for teaching. The clip fits within this allocation.

SOURCES
Riley Brown, ChatGPT Dots Is WAY More Powerful Than You Think, October 9, 2026. https://www.youtube.com/watch?v=WXhOxfPECnM Relevant chapters begin at 02:33, 05:08, and 11:50.
Official documentation checked October 10, 2026. https://learn.chatgpt.com/docs/dots https://learn.chatgpt.com/docs/dots/controls

## Slide 09 · Shared context guides the campaign

TEACHING SCRIPT
The project folder gives the team a common source. Brand context describes the company and offer. AGENTS.md supplies project instructions and routing. Role definitions describe specialist responsibility. Skill files describe repeatable processes. Campaign folders hold outputs. The hidden folders travel inside the ZIP, so confirm extraction preserved them. Work Cloud can use attached sources, while local Codex discovers project files from its primary folder.

CLASSROOM ACTION
Open the extracted course-files project folder. Ask prompt 01 to confirm paths and missing inputs. Show one skill file and one agent definition.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Open the selected project folder. Paste Prompt 01 into your project. Show brand/context.md, the briefs, roles, and skills.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/01-project-setup.mp4.

COPYABLE PROMPT 01
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 01
Read this Copper Cup teaching-kit folder as the source for a fictional marketing project. Inspect brand/context.md, AGENTS.md, and the two briefs. Confirm the product, audience, offer, skill paths, and output structure. Report missing inputs before generating campaign assets. Keep the supplied rehearsal outputs separate from new runs.
END PROMPT 01
```

EXPECTED RESULT
A project folder with brand context, briefs, roles, skills, and campaign outputs.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 10 · A reusable skill gives ads a process

TEACHING SCRIPT
A skill packages a process you expect to repeat. The ad skill reads the brief, proposes concepts, generates artwork when a tool is available, and checks the result before saving it. Its completion criteria include copy, prompts, images, and alt text. The skill file alone cannot provide an image tool or account access. Confirm the skill appears in your environment before running the campaign.

CLASSROOM ACTION
Open the ad-creative SKILL.md and compare its inputs, process, outputs, and completion criteria. Run prompt 03 to verify discovery.

RECORDING CHECKLIST
Suggested clip length 75 seconds.
Paste Prompt 03 in your project task. Open the resulting skill instructions in SKILL.md. Point to its inputs, outputs, and review checks.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/03-create-ad-skill.mp4.

COPYABLE PROMPT 03
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 03
Read .agents/skills/albert-copper-cup-ad-creative/SKILL.md as the required skill specification. Create or verify that reusable project skill without changing its name or scope. Confirm it appears in the available skill interface. Leave existing files intact when the supplied definition already satisfies the specification.
END PROMPT 03
```

EXPECTED RESULT
A reusable ad skill with its frontmatter and completion checks.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 11 · One brief produces three ad concepts

TEACHING SCRIPT
This request points the agent to the approved campaign brief and the reusable skill. It defines the required package without rewriting every instruction. Keep new runs separate from the rehearsal assets so you can compare results. Review the concepts before generating images when a claim or offer needs correction. If generation exceeds the time box, use the prepared images and continue the teaching sequence.

CLASSROOM ACTION
Paste prompt 04 in the project chat, or open the rehearsal concepts and image prompts. Show the output paths and review criteria.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Paste Prompt 04 into your project. Cut past generation waiting time. Open the three concepts and their images, prompts, alt text, and review checklist.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/04-run-ad-skill.mp4.

COPYABLE PROMPT 04
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 04
Use the albert-copper-cup-ad-creative skill with briefs/discovery-box-campaign.md. Create three Instagram ad concepts and the corresponding images. Read brand/context.md and reuse assets/ when appropriate. Save outputs to campaigns/discovery-box/new-run/ads/. Return the concepts, images, generation prompts, alt text, and claim-review checklist. Label the campaign fictional and keep it ready for review.
END PROMPT 04
```

EXPECTED RESULT
Three ad concepts and an artwork review package.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 12 · Three angles, one supported offer

TEACHING SCRIPT
These ads use different audience angles while keeping the Discovery Box offer consistent. Compare the product, CTA, palette, and language. Each concept should connect to a stated audience need without promising health or productivity outcomes. Inspect small text and packaging labels before approving the artwork. The generated coffee images are fictional product illustrations, so they serve a teaching example without representing an existing company.

CLASSROOM ACTION
Open all three rehearsal ads. Ask learners to identify the shared offer and one difference in audience angle. Show the corresponding image-prompt file.

COPYABLE PROMPT 04
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 04
Use the albert-copper-cup-ad-creative skill with briefs/discovery-box-campaign.md. Create three Instagram ad concepts and the corresponding images. Read brand/context.md and reuse assets/ when appropriate. Save outputs to campaigns/discovery-box/new-run/ads/. Return the concepts, images, generation prompts, alt text, and claim-review checklist. Label the campaign fictional and keep it ready for review.
END PROMPT 04
```

EXPECTED RESULT
Three ad concepts, three artwork files, saved prompts, alt text, and a claim review.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 13 · The website skill keeps the offer consistent

TEACHING SCRIPT
The website skill creates a page from the marketing brief and design references. It preserves the offer and CTA while adapting the layout for mobile and desktop. Our page remains a local rehearsal preview. The source includes all assets and readable copy, so the teacher can revise it. Grace deploys through ChatGPT Sites after reviewing the page. Our prompt prepares that handoff with a separate launch decision.

CLASSROOM ACTION
Verify the website skill with prompt 05 and show design-references.md. Explain the local preview and approved deployment steps.

RECORDING CHECKLIST
Suggested clip length 60 seconds.
Paste Prompt 05 into your project. Open the website skill. Highlight offer consistency, source files, and the human launch decision.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/05-create-website-skill.mp4.

COPYABLE PROMPT 05
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 05
Read the complete website skill definition and design references. Create or verify the reusable website skill with those requirements. Keep the supplied skill name. Confirm a responsive page, a local preview, and form testing form part of its completion criteria.
END PROMPT 05
```

EXPECTED RESULT
A website skill with review and preview checks.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 06:02.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 14 · Onigiri hands off the offer page

TEACHING SCRIPT
Onigiri receives an outcome request, locates the project, and coordinates the build. The page shows the Discovery Box and its training price. Its CTA demonstrates the next step without taking payment. Review the offer, mobile layout, and link behavior before proposing deployment. Connected business data could strengthen a future campaign brief, but this class uses synthetic data. The kit includes the page source and a deployment-plan prompt.

CLASSROOM ACTION
Open the offer page from the local server, click its CTA, and resize to a mobile width. Show prompt 06 and the source folder.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Paste Prompt 06 to your project Dot. Show the delegated website task. Open the local page and click its product-detail CTA.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/06-dot-offer-page.mp4.

COPYABLE PROMPT 06
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 06
Onigiri, locate the attached Copper Cup project and read briefs/discovery-box-campaign.md. Use the website-builder skill to prepare a one-page Discovery Box offer site. Route the implementation to Codex if that is available in this environment. Keep the output under campaigns/discovery-box/new-run/site/. Show the preview and source files. Prepare the Sites deployment plan for review before any launch.
END PROMPT 06
```

EXPECTED RESULT
An offer page preview and editable source files.

TEACHING TIME
Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 06:02.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 15 · Skills and agents serve different decisions

TEACHING SCRIPT
A skill defines a process. An agent owns a goal and decides how to pursue it within its scope. For three ads from an approved brief, the ad skill may be sufficient. For choosing an audience and campaign approach from data, the strategist needs judgment. The agent can select relevant skills, but its instructions still define boundaries and completion. Explain that distinction before adding more roles.

CLASSROOM ACTION
Compare the ad request with the strategy request. Ask learners to name the judgment required by each.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 07:49.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 16 · A small skill library covers this campaign

TEACHING SCRIPT
The kit includes eight skills that cover every demonstrated workflow. Start with ad creative and website building, then add the processes the campaign needs. Each skill should define inputs, outputs, and a review criterion. Additional files need a defined purpose in the system. Inspect the skill descriptions so the agent selects the appropriate recipe, and keep overlap low. Scheduling has a separate boundary because a draft schedule and an external calendar write have different effects.

CLASSROOM ACTION
Open .agents/skills/ and point to the eight definitions. Reference slide 31 maps the complete file inventory.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 07:49.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 17 · Give each agent a lasting role

TEACHING SCRIPT
The Growth Strategist needs a lasting role that explains its responsibility across campaigns. These six fields make that role concrete. The brief supplies this campaign’s assignment, while the role defines permitted choices and a finished result. For Copper Cup, the strategist can analyze sample data and propose tests. It asks before sending, publishing, or spending, and flags missing evidence instead of inventing claims. Routine choices inside the brief can continue with recorded assumptions. Completion includes sources, gaps, a proposed next test, and saved output paths.

CLASSROOM ACTION
Point to each field and connect it to the role definition used in the next demonstration. Ask learners to identify one approval boundary for their own marketing team.

OPTIONAL FOLLOW-UP PROMPT A
This follow-up supports practice after class. The numbered demonstration prompts remain unchanged. Paste into your selected course-files project task and copy the text between the markers.

```text
BEGIN PROMPT A
Read agents/growth_strategist.md, brand/context.md, and briefs/discovery-box-campaign.md. Draft a six-field role contract for the Growth Strategist with headings OWNS, INPUTS, MAY, ASKS BEFORE, WHEN UNSURE, DONE WHEN. Separate lasting responsibilities from the current campaign assignment. Permit source review, sample-data analysis, and draft creation within the project. Require specific approval before external sends, publication, spending, deletion, or permission changes. Resolve routine choices within the brief and record assumptions. Escalate missing source evidence, conflicting instructions, or missing access. Define completion through supported claims, stated gaps, a bounded test proposal, and saved output paths. Return the contract for review without changing files or permissions.
END PROMPT A
```

EXPECTED RESULT
A six-field draft role contract that can guide later campaign assignments.

TEACHING TIME
Allow one minute for teaching within the 60-minute lesson. The ten-minute guided exercise remains in the lesson.

SOURCES AND ADAPTATION
Concepts adapted from the four reference screenshots supplied by the instructor on October 6, 2026. Copper Cup examples and the rehearsal stages are classroom adaptations. Run counts describe practice choices and provide no reliability guarantee.

## Slide 18 · The Growth Strategist gains a clear role

TEACHING SCRIPT
The strategist role has a persona, focus, and scope. It turns a goal into campaign recommendations, with evidence and assumptions stated separately. The kit supplies portable role instructions and a local Codex definition. Work uses the role card when you explicitly delegate, while local Codex can load the project TOML. Keep model settings inherited for this class so the role definition remains portable across accounts.

CLASSROOM ACTION
Use prompt 07 to inspect the role. Show the description, developer instructions, and expected output paths.

RECORDING CHECKLIST
Suggested clip length 60 seconds.
Paste Prompt 07 into your project. Open the resulting role instructions. Point to ownership, inputs, outputs, and spending boundaries.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/07-create-growth-agent.mp4.

COPYABLE PROMPT 07
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 07
Read agents/growth_strategist.md and the corresponding .codex/agents/growth_strategist.toml. In a local Codex project, verify the TOML definition loads. In ChatGPT Work, use the Markdown role as specialist instructions for an explicit delegated task. Confirm its role, inputs, output, and approval boundary. Keep model settings inherited from the parent.
END PROMPT 07
```

EXPECTED RESULT
A named strategy role with clear responsibility.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 08:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 19 · A growth goal becomes a testable plan

TEACHING SCRIPT
The strategy should connect the audience hypothesis to an observable outcome. Our synthetic data separates lead acquisition from purchases. A guide may acquire leads efficiently while a box campaign produces a stronger purchase result, so the strategist should avoid a universal winner. The rehearsal recommendation compares roast discovery and the morning routine with a shared offer. Budget and duration need a reviewer decision before a live test.

CLASSROOM ACTION
Run prompt 08 or open the rehearsal strategy and metric findings. Show the distinction between a recommendation and an observed result.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Paste Prompt 08 into your project. Show the metric findings. Open the strategy and experiment brief. Explain one hypothesis and its measurement.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/08-growth-goal.mp4.

COPYABLE PROMPT 08
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 08
Delegate to a Growth Strategist using agents/growth_strategist.md. Read the Discovery Box brief and synthetic past-campaigns.csv with metric-definitions.md. Recommend a launch campaign and a bounded experiment. Save strategy.md and experiment-brief.md under campaigns/discovery-box/new-run/strategy/. Cite input paths and distinguish data findings from recommendations. Wait for the specialist result before returning the reviewed strategy.
END PROMPT 08
```

EXPECTED RESULT
Metric findings, a strategy, and an experiment brief.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 08:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 20 · The Content Creator prepares review assets

TEACHING SCRIPT
The creator translates the approved campaign into audience-specific content. A useful package includes copy, a visual brief, an image prompt, and alt text for each post. Six post folders make review and revision easier to trace. A schedule CSV records the intended sequence but remains a draft. The agent should reconcile its copy with the campaign brief and return the package for review before an external action.

CLASSROOM ACTION
Read prompt 09 and inspect the content role. Open a rehearsal post folder and point to its four text files.

RECORDING CHECKLIST
Suggested clip length 30 seconds.
Paste Prompt 09 into your project. Open the content role. Show how copy, visual direction, and scheduling hand off for review.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/09-create-content-agent.mp4.

COPYABLE PROMPT 09
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 09
Read agents/content_creator.md and the corresponding .codex/agents/content_creator.toml. Verify the local Codex definition or use the Markdown role as specialist instructions in Work. Confirm the output structure includes six post folders, copy, visual briefs, prompts, alt text, and a draft schedule.
END PROMPT 09
```

EXPECTED RESULT
A content role with traceable source outputs.

TEACHING TIME
Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 21 · Limit access to the campaign’s needs

TEACHING SCRIPT
A connected account supplies access, while your instructions define the permitted action. Give the agent the files and fields its campaign needs. It can prepare six social drafts inside the project. Updating a Notion calendar needs an approved destination and fields. Sending a Slack message, launching a public page, or spending money needs approval that names the action and its scope. Deletion and permission changes also need specific approval. Reversibility helps planning, but privacy and the audience still affect permission. Before this class’s Slack demonstration, approve the classroom account, channel, and complete message. Publishing remains a separate decision.

CLASSROOM ACTION
Trace a social draft through the three columns. Before the next Slack demonstration, name the approved classroom channel, account, and message scope.

OPTIONAL FOLLOW-UP PROMPT B
This follow-up supports practice after class. The numbered demonstration prompts remain unchanged. Paste into your selected course-files project task and copy the text between the markers.

```text
BEGIN PROMPT B
Read the Copper Cup campaign brief and the current role instructions. Return a permission plan with three sections covering actions permitted within the project, internal updates needing a named destination and approved fields, and external or consequential actions awaiting specific approval. Include preparing six social drafts, proposing Notion calendar entries, sending a Slack message, publishing a page, and spending campaign funds. State the required account, destination, content, budget limit if relevant, and undo method for each proposed action. Keep all sends, updates, launches, spending, deletion, and permission changes pending until their scope is approved. Flag private data and audience changes even when an action can be reversed. Return the plan without executing it.
END PROMPT B
```

EXPECTED RESULT
A permission plan that distinguishes project drafts, scoped updates, and pending consequential actions.

TEACHING TIME
Allow one minute for teaching within the 60-minute lesson. The ten-minute guided exercise remains in the lesson.

SOURCES AND ADAPTATION
Concepts adapted from the four reference screenshots supplied by the instructor on October 6, 2026. Copper Cup examples and the rehearsal stages are classroom adaptations. Run counts describe practice choices and provide no reliability guarantee.

## Slide 22 · A Slack request coordinates specialists

TEACHING SCRIPT
The Slack request describes an outcome and names the review package. Onigiri must locate the brief and delegate to the selected roles. A connected Slack channel lets you reach Dot, while project and app permissions remain separate. During class, the teacher can send this request to their own Dot if the connections are ready. Otherwise read the prompt and inspect the prepared package. Prepared assets let the lesson continue during generation.

CLASSROOM ACTION
Show the complete tenth prompt. If the instructor has connected Slack, paste it to the instructor’s Dot. Keep sending within the instructor’s approved classroom destination. Use rehearsal outputs while generation runs.

RECORDING CHECKLIST
Suggested clip length 90 seconds.
Open your own connected Dot channel. Paste Prompt 10 only when that classroom destination is approved. Cut generation waiting time. Show the six draft post folders and review PDF.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/10-slack-social-handoff.mp4.

COPYABLE PROMPT 10
Paste into your connected Dot channel. Select the text between the two markers.

```text
BEGIN PROMPT 10
Onigiri, use the attached Copper Cup project and the approved Discovery Box brief to prepare two weeks of social content. Delegate audience and campaign checks to the Growth Strategist and post creation to the Content Creator using their supplied role files. Wait for both results, reconcile the offer and CTA, and return six post folders, a review PDF, and a schedule CSV. Keep the schedule in relative days until I provide a start date and time zone. Bring the package to me for review before any calendar write or publication.
END PROMPT 10
```

EXPECTED RESULT
Six post folders, a review PDF, and a draft schedule.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 23 · Six drafts become a proposed schedule

TEACHING SCRIPT
The review PDF helps the team compare all six posts. Each post folder preserves its source copy and visual instructions. The schedule uses relative days because the class has no launch date. To transfer it into Notion, provide the start date and time zone, review the specific entries and destination, then approve the write. A successful calendar connection still needs a readback to confirm the planned dates and content.

CLASSROOM ACTION
Open the social review PDF and schedule.csv. Show prompt 11 and explain the missing date and time zone. Keep this demonstration at draft preparation.

RECORDING CHECKLIST
Suggested clip length 75 seconds.
Paste Prompt 11 into your project. Show the missing date and time-zone questions. Open the schedule proposal. End before a calendar write.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/11-calendar-review.mp4.

COPYABLE PROMPT 11
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 11
Use the six reviewed post folders and schedule.csv. Prepare a dated calendar plan for the start date and time zone that I provide. If either input is missing, ask for it. Show every proposed entry, its content, the destination calendar, and the connected account. Wait for my specific approval before writing to Notion or another connected calendar. Read back approved entries after writing.
END PROMPT 11
```

EXPECTED RESULT
A schedule proposal with the missing inputs identified.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 24 · Routing gives each request an owner

TEACHING SCRIPT
Before expanding the team, update the project instructions so the agent knows when to use a skill directly and when to delegate. The request should define independent tasks and output directories. The lead waits for specialist results and reviews the combined package. Brand consistency, links, and measurement definitions often fail at handoffs, so include those checks in the merge. The supplied AGENTS.md already contains the routing used in this lesson.

CLASSROOM ACTION
Use prompt 12 to review routing. Trace an ad request and a lead-campaign request through AGENTS.md.

RECORDING CHECKLIST
Suggested clip length 60 seconds.
Paste Prompt 12 into your project. Open the project routing instructions in AGENTS.md. Trace one ad request and one multi-role campaign through the routing rules.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/12-update-routing.mp4.

COPYABLE PROMPT 12
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 12
Review the project agent roles and skills. Keep AGENTS.md concise and verify its routing distinguishes repeatable skill tasks from specialist judgment. Require an explicit coordinated-campaign request for delegation, named outputs for specialists, and a merged review before handoff. Preserve the current external-action approval gates.
END PROMPT 12
```

EXPECTED RESULT
Routing instructions with output paths and a final reviewer.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 25 · Campaign data guides the next hypothesis

TEACHING SCRIPT
Read the definitions before comparing results. Lead conversion divides leads by landing-page visits. CPL divides spend by leads. Cost per order divides spend by orders. The guide campaigns show stronger lead conversion in this synthetic example, while the Discovery Box row shows the lowest cost per order. Those outcomes differ, and campaign objectives also differ. The data suggests a next experiment, with no randomized evidence to establish causation.

CLASSROOM ACTION
Open the supplied campaign data and metric definitions. Calculate the first CPL as 400 divided by 144 and compare the purchase denominator.

COPYABLE PROMPT 13
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 13
Use the supplied lead campaign brief and past campaign data. Delegate performance analysis to the Growth Analyst, guide copy to the Content Creator, guide artwork to the Creative Designer, and the page to the Website Designer. Have the Marketing Team Lead reconcile the package after the independent tasks finish. Build a ten-page brewing guide, editable source, cover, local download page, and metric findings. Validate the demo form using learner@example.com. Return the review package and a Sites deployment proposal. Keep production collection and launch pending review.
END PROMPT 13
```

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 26 · The team builds a guide and download page

TEACHING SCRIPT
The lead campaign combines analysis, content, artwork, and website implementation. Our ten-page guide includes brewing starting points and a troubleshooting worksheet. The page uses the guide cover and validates a fictional test address before revealing the PDF link. It stores no lead in a production system. For a launch, define storage, consent, privacy language, email delivery, and spam protection, then review the Sites proposal and verify the approved deployment.

CLASSROOM ACTION
Open the local download page. Submit a malformed value, then learner@example.com. Open the PDF link and inspect the worksheet. Show prompt 16 for the production proposal.

RECORDING CHECKLIST
Suggested clip length 120 seconds.
Paste Prompt 13 into your project. Cut generation waiting time. Show the metric findings, guide PDF, and download page. Test a malformed address, then learner@example.com, and open the guide.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/13-lead-magnet-team.mp4.

COPYABLE PROMPT 13
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 13
Use the supplied lead campaign brief and past campaign data. Delegate performance analysis to the Growth Analyst, guide copy to the Content Creator, guide artwork to the Creative Designer, and the page to the Website Designer. Have the Marketing Team Lead reconcile the package after the independent tasks finish. Build a ten-page brewing guide, editable source, cover, local download page, and metric findings. Validate the demo form using learner@example.com. Return the review package and a Sites deployment proposal. Keep production collection and launch pending review.
END PROMPT 13
```

EXPECTED RESULT
A ten-page guide, cover, metric findings, and local form preview.

TEACHING TIME
Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

OPTIONAL PRIVATE CAMPAIGN LIBRARY
Keep the reviewed campaign package in a private Page, with the brief, source links, and copyable prompts together. Prepare the Page from sources attached in the conversation and inspect its access before sharing. This extension follows Riley Brown’s Pages chapter at 13:39 and remains outside the core demo playback.

```text
BEGIN PROMPT F
Use only the Copper Cup context, approved brief, prompts, and reviewed outputs attached in this conversation. If a required source is absent, name it before drafting. Create a private Page titled Copper Cup Campaign Kit in my Personal Space. Include the campaign brief, supported offer details, labeled draft assets, source links, and a prompt library. Preserve each supplied prompt verbatim and add its input files, expected result, and review checkpoint. Use copyable prompt blocks when available, with plain text as a fallback. Keep the Page owner-only, leave external sharing pending, and post its link and verification summary in this chat. If Pages is unavailable, return the structured document here for me to save.
END PROMPT F
```

EXPECTED RESULT
A private campaign library with unchanged prompts and a link returned in the conversation.

## Slide 27 · Your ten-minute ad exercise

TEACHING SCRIPT
You have ten minutes to adapt one ad for people setting up their first home office. Preserve the Discovery Box product, price, shipping, and palette. Use prompt 14 and the supplied ad skill. Focus on copy and visual direction if image generation exceeds the time box. At minute six, compare every claim with the brief and choose one revision. At minute nine, prepare to explain how the audience change affected the concept.

CLASSROOM ACTION
Start the ten-minute timer. After two minutes, confirm everyone has the prompt and sources. Use the six-minute checkpoint to call the review step. Invite one or two examples during the final minute.

COPYABLE PROMPT 14
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 14
Use the ad-creative skill and Discovery Box brief. Change the audience to people setting up their first home office while preserving the product, price, shipping, and palette. Draft one ad concept with headline, body copy, CTA, visual brief, image prompt, and alt text. Save it to campaigns/learner-exercise/. Check every claim against brand/context.md and explain the audience change. Use the existing artwork if image generation would exceed the classroom time box.
END PROMPT 14
```

EXPECTED RESULT
One audience-specific ad concept with supported copy, CTA, image prompt, alt text, and review evidence.

TEACHING TIME
Allow 10 minutes for teaching. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 28 · A review names the next revision

TEACHING SCRIPT
Use this five-point rubric to assess the draft. Each criterion receives one point when the evidence is visible. A useful review names the specific claim or design choice that needs revision. The example answer preserves product details and adapts the desk setting without promising productivity gains. This rubric checks a classroom output, while commercial performance needs an approved experiment and measurement.

CLASSROOM ACTION
Open the supplied exercise answer file. Compare one volunteer’s draft with the rubric and offer one supported revision.

RECORDING CHECKLIST
Suggested clip length 30 seconds.
Paste Prompt 15 with the supplied review package. Show a specific finding and its source. Explain the revision before considering launch.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/15-review-package.mp4.

COPYABLE PROMPT 15
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 15
Use the campaign-review skill to inspect the new campaign outputs. Check offer consistency, supported claims, readable visuals, alt text, mobile layout, PDF links, and the metric denominators. Return a review checklist with evidence, defects, and required decisions. Keep scheduling, sending, deployment, and production lead collection as separate approvals.
END PROMPT 15
```

EXPECTED RESULT
A review checklist with specific evidence and revisions.

TEACHING TIME
Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 29 · Rehearse, repair, and retest

TEACHING SCRIPT
One accepted draft gives us one example. Use these three rehearsal stages to examine the process across varied cases. First, watch the result and record guesses, missing inputs, and human corrections. Next, repair the instruction or handoff that produced the error. Then run a different case without supplying the missing answer by hand. For Copper Cup, remove the shipping detail or request an unsupported health claim in a temporary test copy. The expected result names the missing evidence and holds the claim for review. Track accepted results, corrections, review loops, elapsed time, and cost when available. Three stages organize rehearsal and provide no automatic permission increase.

CLASSROOM ACTION
Ask learners how their ad should respond when shipping information is absent. Record the expected escalation as a follow-up test. Preserve the approved source files when preparing test variations.

OPTIONAL FOLLOW-UP PROMPT C
This follow-up supports practice after class. The numbered demonstration prompts remain unchanged. Paste into your selected course-files project task and copy the text between the markers.

```text
BEGIN PROMPT C
Use the supplied fictional Copper Cup context and approved campaign brief. Draft a rehearsal plan for the Growth Strategist with three stages that observe an initial draft, repair a repeatable instruction or handoff failure, and retest with a different campaign case. Include one case with missing shipping information and one request containing an unsupported health claim. Define the expected escalation for each case. Track accepted results, human corrections, review loops, elapsed time, and cost when available. Keep absent cost data labeled unavailable. Require supported claims and approval boundaries in every accepted result. Return the test plan and a blank run log without changing project files or performing external actions.
END PROMPT C
```

EXPECTED RESULT
A varied rehearsal plan with expected escalations and a blank run log.

TEACHING TIME
Allow one minute for teaching within the 60-minute lesson. The ten-minute guided exercise remains in the lesson.

SOURCES AND ADAPTATION
Concepts adapted from the four reference screenshots supplied by the instructor on October 6, 2026. Copper Cup examples and the rehearsal stages are classroom adaptations. Run counts describe practice choices and provide no reliability guarantee.

## Slide 30 · Expand autonomy after evidence

TEACHING SCRIPT
Start with observation and draft preparation, then consider one additional capability after repeated accepted results. The first three examples describe how the agent participates in the task. Scheduling and coordination add timing and routing capabilities, so approve them separately. A weekly drafting routine can still hold every publishing decision for you. Before expanding access, review varied clean examples, correct escalation, the pause or undo path, and the person responsible. A fixed run count provides no reliability guarantee. Reduce access when quality drops, a connection changes, or recurring manual corrections signal an instruction failure. Copper Cup remains a draft-only classroom campaign unless you approve a named next action.

CLASSROOM ACTION
Point to the human approval bar. Choose weekly draft preparation as an example and ask learners to name the evidence and remaining publishing boundary. Use the optional prompt after collecting rehearsal results.

OPTIONAL FOLLOW-UP PROMPT D
This follow-up supports practice after class. The numbered demonstration prompts remain unchanged. Paste into your selected course-files project task and copy the text between the markers.

```text
BEGIN PROMPT D
Review the Copper Cup rehearsal results provided in this conversation. If results are absent, return a draft-only recommendation and name the missing evidence. Compare the current permission scope with one proposed additional capability, such as preparing a weekly draft schedule or routing tasks to the supplied specialists. Require repeated accepted results across varied cases, correct escalation, a tested undo or pause path, and an identified human owner before recommending an expansion. Treat scheduling and coordination as separately authorized capabilities. List the permitted inputs, outputs, destinations, and approval boundaries. Keep sending, publication, spending, deletion, and permission changes pending. Include triggers for reducing access after quality failures or an integration change. Return a recommendation for human review without enabling automation or changing access.
END PROMPT D
```

EXPECTED RESULT
A scoped recommendation for one additional capability, or a draft-only recommendation when evidence is absent.

TEACHING TIME
Allow one minute for teaching within the 60-minute lesson. The ten-minute guided exercise remains in the lesson.

SOURCES AND ADAPTATION
Concepts adapted from the four reference screenshots supplied by the instructor on October 6, 2026. Copper Cup examples and the rehearsal stages are classroom adaptations. Run counts describe practice choices and provide no reliability guarantee.

## Slide 31 · A launch proposal defines the next steps

TEACHING SCRIPT
For your next campaign, update the brand context and brief before running the skills. Keep supported claims, output paths, and review criteria consistent across the team. Select specialists when the goal needs judgment, and use a skill directly when the process already fits. The kit contains prompts and prepared outputs you can compare with a new run. Refresh tool access and product requirements before teaching this lesson again.

CLASSROOM ACTION
Point learners to README.md and the prompt index. End with one task they can adapt for their own brand.

RECORDING CHECKLIST
Suggested clip length 30 seconds.
Paste Prompt 16 into your project. Open the deployment proposal. Identify production integrations and requested approval. End the recording before publishing.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

INSERT RECORDING
Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/16-sites-deployment-plan.mp4.

COPYABLE PROMPT 16
Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
BEGIN PROMPT 16
Inspect the approved website source and campaign brief. Prepare a deployment proposal for ChatGPT Sites with destination, visibility, source version, lead-data behavior, privacy requirements, and rollback approach. Explain the difference between a local download demo and a production form. Wait for approval of this specific proposal before deploying. After an approved launch, verify the live URL, mobile layout, form behavior, storage destination, and PDF delivery.
END PROMPT 16
```

EXPECTED RESULT
A deployment proposal and an approval checkpoint.

TEACHING TIME
Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

CLASSROOM CLOSE
The 60-minute core lesson ends here. The recurring brief demonstration and remaining reference slides are optional extensions. Use the workbook for follow-up practice and recording preparation.

## Slide 32 · A daily brief and a focused follow-up check

TEACHING SCRIPT
The daily brief leads with the next campaign decision and reports the draft status and missing inputs. A recurring follow-up checks a named responsibility and brings a changed condition back to you. These routines need a source list, time zone, end date, destination, and permitted actions. In this recording, the prompt prepares one brief and proposes two schedules. It leaves both schedules disabled. After rehearsal, review usage and approve any routine separately. Inspect the saved schedule and the first result, and check active tasks separately when pausing future runs.

CLASSROOM ACTION
Use a prepared recording for this demonstration. Open the written result beside the conversation and compare it with the supplied Copper Cup brief.

RECORDING CHECKLIST
Suggested clip length 75 seconds.
Attach the fictional brief, metric snapshot, and reviewed draft outputs. Paste Follow-up G into Onigiri’s conversation. Show the decision at the top of the brief and the source references. Highlight the proposed time zone, end date, alert conditions, and disabled status. Show where Activity and Scheduled can be inspected. Finish before enabling either routine.
Record at 1920 by 1080. Hide unrelated chats and account details. Cut generation waiting time and hold the checked result for five seconds.

INSERT RECORDING
Replace the label shapes inside the large frame with your Google Drive recording. Keep the marked 16:9 frame and the quarter-width prompt panel. Save the recording as recordings/G-brief-followup-plan.mp4.

COPYABLE FOLLOW-UP PROMPT G
Paste this full prompt into your Dot conversation, or read it during the call. Select the text between the two markers.

```text
BEGIN PROMPT G
Using the attached Copper Cup brief, fictional campaign metrics, and reviewed draft outputs, prepare a marketing brief for today. Lead with the next decision, then list the current draft status, missing inputs, sources checked, and next action for the human owner. Label the campaign data synthetic and distinguish observed figures from hypotheses. After this one-time brief, propose two separate recurring routines without enabling either. First propose a weekday brief at 09:00 America/Los_Angeles for one teaching week. Then propose an hourly follow-up check during that week from 09:00 to 17:00 in that time zone. Limit both to the named Copper Cup sources and draft review. The follow-up should notify me only for a changed offer, a deadline at risk, a missing required input, or a decision awaiting my review. Name the destination, end date, usage considerations, and pause controls. Hold schedule creation, external sends, publication, spending, deletion, and permission changes for a separate decision.
END PROMPT G
```

EXPECTED RESULT
A one-time marketing brief and two scoped schedule proposals awaiting review.

TEACHING TIME
Optional extension outside the 60-minute lesson. Allow three minutes if you add this demonstration.

SOURCES
Riley Brown, ChatGPT Dots Is WAY More Powerful Than You Think, October 9, 2026. https://www.youtube.com/watch?v=WXhOxfPECnM Relevant chapters begin at 19:13 and 21:14.
Official documentation checked October 10, 2026. https://learn.chatgpt.com/docs/dots https://learn.chatgpt.com/docs/dots/controls

## Slide 33 · Account requirements and rollout

TEACHING SCRIPT
This reference records the current Dot eligibility described by OpenAI. Availability rolls out gradually, so an eligible plan can still lack a visible Dot. Enterprise administrators must enable access. Cloud tasks and local computer use have different availability requirements. Refresh these details before class.

CLASSROOM ACTION
Use setup-checklist.md and the linked official Dot guide.

EXPECTED RESULT
A completed instructor access checklist.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels
https://learn.chatgpt.com/docs/sites

DOT ACCESS REFRESH
Dot eligibility, mobile creation, local computer requirements, and delegated task controls were checked October 10, 2026. https://learn.chatgpt.com/docs/dots

## Slide 34 · The complete teaching-kit inventory

TEACHING SCRIPT
This inventory maps the lesson to the files learners receive. The kit separates portable role cards from local Codex configuration and rehearsal outputs from new runs. Preserve the hidden folders during extraction. The file-to-slide manifest gives you the prompt and source for every teaching slide.

CLASSROOM ACTION
Open the file manifest and kit instructions.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 35 · Prompt sequence and demo shortcuts

TEACHING SCRIPT
Use the prompt index for the full tutorial or jump to the task you need. Prompt 14 supports the learner exercise. Prompts 11 and 16 prepare external actions but require a specific approval before a calendar write or launch. The rehearsal examples remain available when a live step is delayed.

CLASSROOM ACTION
Open prompts/README.md and the selected text file.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 36 · Agent roles and routing reference

TEACHING SCRIPT
This table assigns responsibility without implying every request needs all six roles. Name the outputs and approval boundary when delegating. Independent specialist tasks can run concurrently when the environment supports them. The lead still reviews the assembled result before returning it.

CLASSROOM ACTION
Read agents/README.md and AGENTS.md for the environment-specific handoff.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 37 · Troubleshooting and rehearsal paths

TEACHING SCRIPT
The troubleshooting guide provides a defined rehearsal path for each missing feature. Confirm the cause before changing instructions or tools. A prepared example can explain the workflow while an unavailable connector remains unchecked. Use the integration checklist before moving a local page into production.

CLASSROOM ACTION
Open troubleshooting.md and choose the matching scenario.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 38 · Sources and adaptation credits

TEACHING SCRIPT
Grace’s tutorial supplies the demonstration order and agent-team pattern. This workshop rebuilds the examples with a fictional coffee brand and its own visual design. Official product guides supply current setup details. Coffee instructions provide qualified starting points, with equipment and taste affecting results. The synthetic campaign figures demonstrate arithmetic and decision boundaries.

CLASSROOM ACTION
Open sources.md for links, source timestamps, and the adaptation map.

EXPECTED RESULT
Learners can explain the distinction and identify the next step.

TEACHING TIME
Use this slide for reference. Reference slides sit outside the 60-minute lesson.

SOURCES
Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

ADDITIONAL SOURCE
Riley Brown, ChatGPT Dots Is WAY More Powerful Than You Think, October 9, 2026. https://www.youtube.com/watch?v=WXhOxfPECnM Full auto-generated transcript reviewed. Copper Cup voice, Page, and brief examples are course adaptations. Phone notification settings, shopping, 3D printing, and application feature development remain outside the core lesson. Every course slide follows the instructor-supplied Leland event template. The course retains its campaign artwork, full prompts, speaker scripts, and quarter-width prompt panels beside recording frames.
