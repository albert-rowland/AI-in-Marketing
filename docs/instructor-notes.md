# Complete instructor speaker notes

[← Return to the course](../README.md)

Open [the editable Google Slides deck](https://docs.google.com/presentation/d/1EY7U2ZDfHXPUsubG0SyrNJdkPEbLEOhQGgygsC7SWC0/edit) using the instructor account. The instructor controls deck and video permissions. The [plain text notes](speaker-notes.txt) contain the matching script.

## Slide 01 · Build Your AI Marketing Team with Agents.

### Teaching Script

This session follows a fictional coffee campaign through reusable skills and a specialist agent team. We will build draft ads, inspect an offer page, and coordinate social content before reviewing a lead-generation package. You will adapt one ad during the guided exercise. Every coffee product and campaign figure belongs to our classroom example. Human review governs the publishing decision throughout the lesson.

### Classroom Action

Open the Google Slides deck and the course-files project folder. Keep the rehearsal pages available in browser tabs.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 02 · Work, Codex, and Dot

### Teaching Script

Grace uses Work for business deliverables and Codex for code and website implementation. Dot provides an ongoing coordination layer and can use connected projects and tools. These roles overlap, so treat this map as a starting guide. In our example, Work prepares the campaign, Codex can implement its page, and Dot coordinates the request. Account features and permissions determine which handoffs are available.

### Classroom Action

Point to the three roles and trace the offer-page request across them. Explain that each role name describes responsibility within the available products.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 00:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 03 · Accounts and access

### Teaching Script

Check access before learners arrive. Dot availability depends on plan, region, rollout, and workspace settings. Slack, Notion, and local project access each require their own connections. Those connections have separate permissions. Our full demonstration follows Grace’s tools. Learners can observe the Dot steps and use an available project chat for the ad exercise if their account lacks that feature. Prepared outputs keep the lesson moving.

### Classroom Action

Open setup-checklist.md and check each available feature. Reference slide 26 contains the current eligibility detail.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 01:20.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 04 · Onigiri receives the campaign role

### Teaching Script

Our demo Dot is called Onigiri. Give Onigiri the project, its responsibility, and a clear review boundary. The request tells Onigiri where to return decisions and which outputs to prepare. The cloud computer can continue without your laptop, while local files and skills require the relevant connected computer to remain available. Slack gives you another messaging channel, with separate access to the project and its tools.

### Classroom Action

Read prompt 02 and demonstrate the Dot profile connection choices if your account supports them. Confirm the project before requesting a task.

### Recording Checklist

Suggested clip length 30 seconds.
Open ChatGPT with your attached project. Paste Prompt 02 into your project. Show the confirmed project path and available connections.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/02-dot-setup.mp4.

### Copyable Prompt 02

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Your name for this exercise is Onigiri. Coordinate the fictional Copper Cup marketing project that I attach. Prepare drafts and local previews, and bring review decisions to me in ChatGPT. Read AGENTS.md and brand/context.md before acting. Use connected tools only within their permissions. Ask before scheduling, sending, deploying, collecting leads, or spending. Confirm the project path and available connections. This request establishes a classroom role for the current project, with future recurring duties requiring a stated cadence.
```

### Expected Result

Project role, available connections, and clear review boundaries.

### Teaching Time

Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 01:20.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 05 · One lead and five specialists

### Teaching Script

The team has six roles, a lead and five specialists. Grace describes five specialist agents beneath a marketing team lead, so we show that structure explicitly. Onigiri coordinates access and requests outside the project. The lead reconciles the assembled campaign. Each specialist has a defined responsibility and a named output. You can begin with the strategist and content creator, then add roles when the campaign needs their judgment.

### Classroom Action

Open the supplied agent inventory file. Show the six Markdown roles and the matching local Codex TOML files. Explain that a role card needs an explicit delegation request to start a run.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:03.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 06 · Copper Cup campaign context

### Teaching Script

Copper Cup gives us one consistent company for the entire lesson. Its Discovery Box contains three 100 g bags with different roast styles. The price and shipping are fictional training inputs. We will keep those details consistent across ads, pages, and posts. The audience description is a hypothesis, so our strategy should explain how we would test it. Brand context defines the facts the agent can use.

### Classroom Action

Open the brand context and Discovery Box brief. Highlight the offer, audience, CTA, and unsupported-claim boundary.

### Copyable Prompt 01

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read this Copper Cup teaching-kit folder as the source for a fictional marketing project. Inspect brand/context.md, AGENTS.md, and the two briefs. Confirm the product, audience, offer, skill paths, and output structure. Report missing inputs before generating campaign assets. Keep the supplied rehearsal outputs separate from new runs.
```

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 07 · Shared context guides the campaign

### Teaching Script

The project folder gives the team a common source. Brand context describes the company and offer. AGENTS.md supplies project instructions and routing. Role definitions describe specialist responsibility. Skill files describe repeatable processes. Campaign folders hold outputs. The hidden folders travel inside the ZIP, so confirm extraction preserved them. Work Cloud can use attached sources, while local Codex discovers project files from its primary folder.

### Classroom Action

Open the extracted course-files project folder. Ask prompt 01 to confirm paths and missing inputs. Show one skill file and one agent definition.

### Recording Checklist

Suggested clip length 90 seconds.
Open the selected project folder. Paste Prompt 01 into your project. Show brand/context.md, the briefs, roles, and skills.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/01-project-setup.mp4.

### Copyable Prompt 01

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read this Copper Cup teaching-kit folder as the source for a fictional marketing project. Inspect brand/context.md, AGENTS.md, and the two briefs. Confirm the product, audience, offer, skill paths, and output structure. Report missing inputs before generating campaign assets. Keep the supplied rehearsal outputs separate from new runs.
```

### Expected Result

A project folder with brand context, briefs, roles, skills, and campaign outputs.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 02:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 08 · A reusable skill gives ads a process

### Teaching Script

A skill packages a process you expect to repeat. The ad skill reads the brief, proposes concepts, generates artwork when a tool is available, and checks the result before saving it. Its completion criteria include copy, prompts, images, and alt text. The skill file alone cannot provide an image tool or account access. Confirm the skill appears in your environment before running the campaign.

### Classroom Action

Open the ad-creative SKILL.md and compare its inputs, process, outputs, and completion criteria. Run prompt 03 to verify discovery.

### Recording Checklist

Suggested clip length 75 seconds.
Paste Prompt 03 in your project task. Open the resulting skill instructions in SKILL.md. Point to its inputs, outputs, and review checks.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/03-create-ad-skill.mp4.

### Copyable Prompt 03

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read .agents/skills/albert-copper-cup-ad-creative/SKILL.md as the required skill specification. Create or verify that reusable project skill without changing its name or scope. Confirm it appears in the available skill interface. Leave existing files intact when the supplied definition already satisfies the specification.
```

### Expected Result

A reusable ad skill with its frontmatter and completion checks.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 09 · One brief produces three ad concepts

### Teaching Script

This request points the agent to the approved campaign brief and the reusable skill. It defines the required package without rewriting every instruction. Keep new runs separate from the rehearsal assets so you can compare results. Review the concepts before generating images when a claim or offer needs correction. If generation exceeds the time box, use the prepared images and continue the teaching sequence.

### Classroom Action

Paste prompt 04 in the project chat, or open the rehearsal concepts and image prompts. Show the output paths and review criteria.

### Recording Checklist

Suggested clip length 90 seconds.
Paste Prompt 04 into your project. Cut past generation waiting time. Open the three concepts and their images, prompts, alt text, and review checklist.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/04-run-ad-skill.mp4.

### Copyable Prompt 04

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the albert-copper-cup-ad-creative skill with briefs/discovery-box-campaign.md. Create three Instagram ad concepts and the corresponding images. Read brand/context.md and reuse assets/ when appropriate. Save outputs to campaigns/discovery-box/new-run/ads/. Return the concepts, images, generation prompts, alt text, and claim-review checklist. Label the campaign fictional and keep it ready for review.
```

### Expected Result

Three ad concepts and an artwork review package.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 10 · Three angles, one supported offer

### Teaching Script

These ads use different audience angles while keeping the Discovery Box offer consistent. Compare the product, CTA, palette, and language. Each concept should connect to a stated audience need without promising health or productivity outcomes. Inspect small text and packaging labels before approving the artwork. The generated coffee images are fictional product illustrations, so they serve a teaching example without representing an existing company.

### Classroom Action

Open all three rehearsal ads. Ask learners to identify the shared offer and one difference in audience angle. Show the corresponding image-prompt file.

### Copyable Prompt 04

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the albert-copper-cup-ad-creative skill with briefs/discovery-box-campaign.md. Create three Instagram ad concepts and the corresponding images. Read brand/context.md and reuse assets/ when appropriate. Save outputs to campaigns/discovery-box/new-run/ads/. Return the concepts, images, generation prompts, alt text, and claim-review checklist. Label the campaign fictional and keep it ready for review.
```

### Expected Result

Three ad concepts, three artwork files, saved prompts, alt text, and a claim review.

### Teaching Time

Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 03:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 11 · The website skill keeps the offer consistent

### Teaching Script

The website skill creates a page from the marketing brief and design references. It preserves the offer and CTA while adapting the layout for mobile and desktop. Our page remains a local rehearsal preview. The source includes all assets and readable copy, so the teacher can revise it. Grace deploys through ChatGPT Sites after reviewing the page. Our prompt prepares that handoff with a separate launch decision.

### Classroom Action

Verify the website skill with prompt 05 and show design-references.md. Explain the local preview and approved deployment steps.

### Recording Checklist

Suggested clip length 60 seconds.
Paste Prompt 05 into your project. Open the website skill. Highlight offer consistency, source files, and the human launch decision.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/05-create-website-skill.mp4.

### Copyable Prompt 05

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read the complete website skill definition and design references. Create or verify the reusable website skill with those requirements. Keep the supplied skill name. Confirm a responsive page, a local preview, and form testing form part of its completion criteria.
```

### Expected Result

A website skill with review and preview checks.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 06:02.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 12 · Onigiri hands off the offer page

### Teaching Script

Onigiri receives an outcome request, locates the project, and coordinates the build. The page shows the Discovery Box and its training price. Its CTA demonstrates the next step without taking payment. Review the offer, mobile layout, and link behavior before proposing deployment. Connected business data could strengthen a future campaign brief, but this class uses synthetic data. The kit includes the page source and a deployment-plan prompt.

### Classroom Action

Open the offer page from the local server, click its CTA, and resize to a mobile width. Show prompt 06 and the source folder.

### Recording Checklist

Suggested clip length 90 seconds.
Paste Prompt 06 to your project Dot. Show the delegated website task. Open the local page and click its product-detail CTA.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/06-dot-offer-page.mp4.

### Copyable Prompt 06

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Onigiri, locate the attached Copper Cup project and read briefs/discovery-box-campaign.md. Use the website-builder skill to prepare a one-page Discovery Box offer site. Route the implementation to Codex if that is available in this environment. Keep the output under campaigns/discovery-box/new-run/site/. Show the preview and source files. Prepare the Sites deployment plan for review before any launch.
```

### Expected Result

An offer page preview and editable source files.

### Teaching Time

Allow 4 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 06:02.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 13 · Skills and agents serve different decisions

### Teaching Script

A skill defines a process. An agent owns a goal and decides how to pursue it within its scope. For three ads from an approved brief, the ad skill may be sufficient. For choosing an audience and campaign approach from data, the strategist needs judgment. The agent can select relevant skills, but its instructions still define boundaries and completion. Explain that distinction before adding more roles.

### Classroom Action

Compare the ad request with the strategy request. Ask learners to name the judgment required by each.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 07:49.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 14 · A small skill library covers this campaign

### Teaching Script

The kit includes eight skills that cover every demonstrated workflow. Start with ad creative and website building, then add the processes the campaign needs. Each skill should define inputs, outputs, and a review criterion. Additional files need a defined purpose in the system. Inspect the skill descriptions so the agent selects the appropriate recipe, and keep overlap low. Scheduling has a separate boundary because a draft schedule and an external calendar write have different effects.

### Classroom Action

Open .agents/skills/ and point to the eight definitions. Reference slide 27 maps the complete file inventory.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 07:49.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 15 · The Growth Strategist gains a clear role

### Teaching Script

The strategist role has a persona, focus, and scope. It turns a goal into campaign recommendations, with evidence and assumptions stated separately. The kit supplies portable role instructions and a local Codex definition. Work uses the role card when you explicitly delegate, while local Codex can load the project TOML. Keep model settings inherited for this class so the role definition remains portable across accounts.

### Classroom Action

Use prompt 07 to inspect the role. Show the description, developer instructions, and expected output paths.

### Recording Checklist

Suggested clip length 60 seconds.
Paste Prompt 07 into your project. Open the resulting role instructions. Point to ownership, inputs, outputs, and spending boundaries.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/07-create-growth-agent.mp4.

### Copyable Prompt 07

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read agents/growth_strategist.md and the corresponding .codex/agents/growth_strategist.toml. In a local Codex project, verify the TOML definition loads. In ChatGPT Work, use the Markdown role as specialist instructions for an explicit delegated task. Confirm its role, inputs, output, and approval boundary. Keep model settings inherited from the parent.
```

### Expected Result

A named strategy role with clear responsibility.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 08:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 16 · A growth goal becomes a testable plan

### Teaching Script

The strategy should connect the audience hypothesis to an observable outcome. Our synthetic data separates lead acquisition from purchases. A guide may acquire leads efficiently while a box campaign produces a stronger purchase result, so the strategist should avoid a universal winner. The rehearsal recommendation compares roast discovery and the morning routine with a shared offer. Budget and duration need a reviewer decision before a live test.

### Classroom Action

Run prompt 08 or open the rehearsal strategy and metric findings. Show the distinction between a recommendation and an observed result.

### Recording Checklist

Suggested clip length 90 seconds.
Paste Prompt 08 into your project. Show the metric findings. Open the strategy and experiment brief. Explain one hypothesis and its measurement.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/08-growth-goal.mp4.

### Copyable Prompt 08

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Delegate to a Growth Strategist using agents/growth_strategist.md. Read the Discovery Box brief and synthetic past-campaigns.csv with metric-definitions.md. Recommend a launch campaign and a bounded experiment. Save strategy.md and experiment-brief.md under campaigns/discovery-box/new-run/strategy/. Cite input paths and distinguish data findings from recommendations. Wait for the specialist result before returning the reviewed strategy.
```

### Expected Result

Metric findings, a strategy, and an experiment brief.

### Teaching Time

Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 08:27.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 17 · The Content Creator prepares review assets

### Teaching Script

The creator translates the approved campaign into audience-specific content. A useful package includes copy, a visual brief, an image prompt, and alt text for each post. Six post folders make review and revision easier to trace. A schedule CSV records the intended sequence but remains a draft. The agent should reconcile its copy with the campaign brief and return the package for review before an external action.

### Classroom Action

Read prompt 09 and inspect the content role. Open a rehearsal post folder and point to its four text files.

### Recording Checklist

Suggested clip length 30 seconds.
Paste Prompt 09 into your project. Open the content role. Show how copy, visual direction, and scheduling hand off for review.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/09-create-content-agent.mp4.

### Copyable Prompt 09

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Read agents/content_creator.md and the corresponding .codex/agents/content_creator.toml. Verify the local Codex definition or use the Markdown role as specialist instructions in Work. Confirm the output structure includes six post folders, copy, visual briefs, prompts, alt text, and a draft schedule.
```

### Expected Result

A content role with traceable source outputs.

### Teaching Time

Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 18 · A Slack request coordinates specialists

### Teaching Script

The Slack request describes an outcome and names the review package. Onigiri must locate the brief and delegate to the selected roles. A connected Slack channel lets you reach Dot, while project and app permissions remain separate. During class, the teacher can send this request to their own Dot if the connections are ready. Otherwise read the prompt and inspect the prepared package. Prepared assets let the lesson continue during generation.

### Classroom Action

Show the complete tenth prompt. If the instructor has connected Slack, paste it to the instructor’s Dot. Keep sending within the instructor’s approved classroom destination. Use rehearsal outputs while generation runs.

### Recording Checklist

Suggested clip length 90 seconds.
Open your own connected Dot channel. Paste Prompt 10 only when that classroom destination is approved. Cut generation waiting time. Show the six draft post folders and review PDF.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/10-slack-social-handoff.mp4.

### Copyable Prompt 10

Paste into your connected Dot channel. Select the text between the two markers.

```text
Onigiri, use the attached Copper Cup project and the approved Discovery Box brief to prepare two weeks of social content. Delegate audience and campaign checks to the Growth Strategist and post creation to the Content Creator using their supplied role files. Wait for both results, reconcile the offer and CTA, and return six post folders, a review PDF, and a schedule CSV. Keep the schedule in relative days until I provide a start date and time zone. Bring the package to me for review before any calendar write or publication.
```

### Expected Result

Six post folders, a review PDF, and a draft schedule.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels

## Slide 19 · Six drafts become a proposed schedule

### Teaching Script

The review PDF helps the team compare all six posts. Each post folder preserves its source copy and visual instructions. The schedule uses relative days because the class has no launch date. To transfer it into Notion, provide the start date and time zone, review the specific entries and destination, then approve the write. A successful calendar connection still needs a readback to confirm the planned dates and content.

### Classroom Action

Open the social review PDF and schedule.csv. Show prompt 11 and explain the missing date and time zone. Keep this demonstration at draft preparation.

### Recording Checklist

Suggested clip length 75 seconds.
Paste Prompt 11 into your project. Show the missing date and time-zone questions. Open the schedule proposal. End before a calendar write.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/11-calendar-review.mp4.

### Copyable Prompt 11

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the six reviewed post folders and schedule.csv. Prepare a dated calendar plan for the start date and time zone that I provide. If either input is missing, ask for it. Show every proposed entry, its content, the destination calendar, and the connected account. Wait for my specific approval before writing to Notion or another connected calendar. Read back approved entries after writing.
```

### Expected Result

A schedule proposal with the missing inputs identified.

### Teaching Time

Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 09:51.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 20 · Routing gives each request an owner

### Teaching Script

Before expanding the team, update the project instructions so the agent knows when to use a skill directly and when to delegate. The request should define independent tasks and output directories. The lead waits for specialist results and reviews the combined package. Brand consistency, links, and measurement definitions often fail at handoffs, so include those checks in the merge. The supplied AGENTS.md already contains the routing used in this lesson.

### Classroom Action

Use prompt 12 to review routing. Trace an ad request and a lead-campaign request through AGENTS.md.

### Recording Checklist

Suggested clip length 60 seconds.
Paste Prompt 12 into your project. Open the project routing instructions in AGENTS.md. Trace one ad request and one multi-role campaign through the routing rules.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/12-update-routing.mp4.

### Copyable Prompt 12

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Review the project agent roles and skills. Keep AGENTS.md concise and verify its routing distinguishes repeatable skill tasks from specialist judgment. Require an explicit coordinated-campaign request for delegation, named outputs for specialists, and a merged review before handoff. Preserve the current external-action approval gates.
```

### Expected Result

Routing instructions with output paths and a final reviewer.

### Teaching Time

Allow 2 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 21 · Campaign data guides the next hypothesis

### Teaching Script

Read the definitions before comparing results. Lead conversion divides leads by landing-page visits. CPL divides spend by leads. Cost per order divides spend by orders. The guide campaigns show stronger lead conversion in this synthetic example, while the Discovery Box row shows the lowest cost per order. Those outcomes differ, and campaign objectives also differ. The data suggests a next experiment, with no randomized evidence to establish causation.

### Classroom Action

Open the supplied campaign data and metric definitions. Calculate the first CPL as 400 divided by 144 and compare the purchase denominator.

### Copyable Prompt 13

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the supplied lead campaign brief and past campaign data. Delegate performance analysis to the Growth Analyst, guide copy to the Content Creator, guide artwork to the Creative Designer, and the page to the Website Designer. Have the Marketing Team Lead reconcile the package after the independent tasks finish. Build a ten-page brewing guide, editable source, cover, local download page, and metric findings. Validate the demo form using learner@example.com. Return the review package and a Sites deployment proposal. Keep production collection and launch pending review.
```

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 22 · The team builds a guide and download page

### Teaching Script

The lead campaign combines analysis, content, artwork, and website implementation. Our ten-page guide includes brewing starting points and a troubleshooting worksheet. The page uses the guide cover and validates a fictional test address before revealing the PDF link. It stores no lead in a production system. For a launch, define storage, consent, privacy language, email delivery, and spam protection, then review the Sites proposal and verify the approved deployment.

### Classroom Action

Open the local download page. Submit a malformed value, then learner@example.com. Open the PDF link and inspect the worksheet. Show prompt 16 for the production proposal.

### Recording Checklist

Suggested clip length 120 seconds.
Paste Prompt 13 into your project. Cut generation waiting time. Show the metric findings, guide PDF, and download page. Test a malformed address, then learner@example.com, and open the guide.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/13-lead-magnet-team.mp4.

### Copyable Prompt 13

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the supplied lead campaign brief and past campaign data. Delegate performance analysis to the Growth Analyst, guide copy to the Content Creator, guide artwork to the Creative Designer, and the page to the Website Designer. Have the Marketing Team Lead reconcile the package after the independent tasks finish. Build a ten-page brewing guide, editable source, cover, local download page, and metric findings. Validate the demo form using learner@example.com. Return the review package and a Sites deployment proposal. Keep production collection and launch pending review.
```

### Expected Result

A ten-page guide, cover, metric findings, and local form preview.

### Teaching Time

Allow 3 minutes for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg Source chapter starts at 12:34.
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 23 · Your ten-minute ad exercise

### Teaching Script

You have ten minutes to adapt one ad for people setting up their first home office. Preserve the Discovery Box product, price, shipping, and palette. Use prompt 14 and the supplied ad skill. Focus on copy and visual direction if image generation exceeds the time box. At minute six, compare every claim with the brief and choose one revision. At minute nine, prepare to explain how the audience change affected the concept.

### Classroom Action

Start the ten-minute timer. After two minutes, confirm everyone has the prompt and sources. Use the six-minute checkpoint to call the review step. Invite one or two examples during the final minute.

### Copyable Prompt 14

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the ad-creative skill and Discovery Box brief. Change the audience to people setting up their first home office while preserving the product, price, shipping, and palette. Draft one ad concept with headline, body copy, CTA, visual brief, image prompt, and alt text. Save it to campaigns/learner-exercise/. Check every claim against brand/context.md and explain the audience change. Use the existing artwork if image generation would exceed the classroom time box.
```

### Expected Result

One audience-specific ad concept with supported copy, CTA, image prompt, alt text, and review evidence.

### Teaching Time

Allow 10 minutes for teaching. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 24 · A review names the next revision

### Teaching Script

Use this five-point rubric to assess the draft. Each criterion receives one point when the evidence is visible. A useful review names the specific claim or design choice that needs revision. The example answer preserves product details and adapts the desk setting without promising productivity gains. This rubric checks a classroom output, while commercial performance needs an approved experiment and measurement.

### Classroom Action

Open the supplied exercise answer file. Compare one volunteer’s draft with the rubric and offer one supported revision.

### Recording Checklist

Suggested clip length 30 seconds.
Paste Prompt 15 with the supplied review package. Show a specific finding and its source. Explain the revision before considering launch.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/15-review-package.mp4.

### Copyable Prompt 15

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Use the campaign-review skill to inspect the new campaign outputs. Check offer consistency, supported claims, readable visuals, alt text, mobile layout, PDF links, and the metric denominators. Return a review checklist with evidence, defects, and required decisions. Keep scheduling, sending, deployment, and production lead collection as separate approvals.
```

### Expected Result

A review checklist with specific evidence and revisions.

### Teaching Time

Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

## Slide 25 · A launch proposal defines the next steps

### Teaching Script

For your next campaign, update the brand context and brief before running the skills. Keep supported claims, output paths, and review criteria consistent across the team. Select specialists when the goal needs judgment, and use a skill directly when the process already fits. The kit contains prompts and prepared outputs you can compare with a new run. Refresh tool access and product requirements before teaching this lesson again.

### Classroom Action

Point learners to README.md and the prompt index. End with one task they can adapt for their own brand.

### Recording Checklist

Suggested clip length 30 seconds.
Paste Prompt 16 into your project. Open the deployment proposal. Identify production integrations and requested approval. End the recording before publishing.
Record at 1920 by 1080. Hide account details and unrelated project files. Pause or cut generation waiting time. Leave the reviewed output visible for five seconds.

### Insert Recording

Select the large video frame and remove its label shapes. Use Insert > Video in Google Slides, select your recording from Google Drive, and size it to the marked 16:9 frame. Save the recording as recordings/16-sites-deployment-plan.mp4.

### Copyable Prompt 16

Paste into your selected ChatGPT Work or Codex project task. Select the text between the two markers.

```text
Inspect the approved website source and campaign brief. Prepare a deployment proposal for ChatGPT Sites with destination, visibility, source version, lead-data behavior, privacy requirements, and rollback approach. Explain the difference between a local download demo and a production form. Wait for approval of this specific proposal before deploying. After an approved launch, verify the live URL, mobile layout, form behavior, storage destination, and PDF delivery.
```

### Expected Result

A deployment proposal and an approval checkpoint.

### Teaching Time

Allow one minute for teaching. Reference slides sit outside the 60-minute lesson.
The clip plays within this teaching time. Explain the steps during playback, then pause for questions.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/sites

## Slide 26 · Account requirements and rollout

### Teaching Script

This reference records the current Dot eligibility described by OpenAI. Availability rolls out gradually, so an eligible plan can still lack a visible Dot. Enterprise administrators must enable access. Cloud tasks and local computer use have different availability requirements. Refresh these details before class.

### Classroom Action

Use setup-checklist.md and the linked official Dot guide.

### Expected Result

A completed instructor access checklist.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/dots/channels
https://learn.chatgpt.com/docs/sites

## Slide 27 · The complete teaching-kit inventory

### Teaching Script

This inventory maps the lesson to the files learners receive. The kit separates portable role cards from local Codex configuration and rehearsal outputs from new runs. Preserve the hidden folders during extraction. The file-to-slide manifest gives you the prompt and source for every teaching slide.

### Classroom Action

Open the file manifest and kit instructions.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 28 · Prompt sequence and demo shortcuts

### Teaching Script

Use the prompt index for the full tutorial or jump to the task you need. Prompt 14 supports the learner exercise. Prompts 11 and 16 prepare external actions but require a specific approval before a calendar write or launch. The rehearsal examples remain available when a live step is delayed.

### Classroom Action

Open prompts/README.md and the selected text file.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills

## Slide 29 · Agent roles and routing reference

### Teaching Script

This table assigns responsibility without implying every request needs all six roles. Name the outputs and approval boundary when delegating. Independent specialist tasks can run concurrently when the environment supports them. The lead still reviews the assembled result before returning it.

### Classroom Action

Read agents/README.md and AGENTS.md for the environment-specific handoff.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 30 · Troubleshooting and rehearsal paths

### Teaching Script

The troubleshooting guide provides a defined rehearsal path for each missing feature. Confirm the cause before changing instructions or tools. A prepared example can explain the workflow while an unavailable connector remains unchecked. Use the integration checklist before moving a local page into production.

### Classroom Action

Open troubleshooting.md and choose the matching scenario.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots
https://developers.openai.com/codex/skills
https://learn.chatgpt.com/docs/agent-configuration/subagents

## Slide 31 · Sources and adaptation credits

### Teaching Script

Grace’s tutorial supplies the demonstration order and agent-team pattern. This workshop rebuilds the examples with a fictional coffee brand and its own visual design. Official product guides supply current setup details. Coffee instructions provide qualified starting points, with equipment and taste affecting results. The synthetic campaign figures demonstrate arithmetic and decision boundaries.

### Classroom Action

Open sources.md for links, source timestamps, and the adaptation map.

### Expected Result

Learners can explain the distinction and identify the next step.

### Teaching Time

Use this slide for reference. Reference slides sit outside the 60-minute lesson.

### Sources

Grace Leung, ChatGPT Work + Dot, October 3, 2026. https://www.youtube.com/watch?v=BzS93V2zFTg
Official product guidance checked October 4, 2026. https://learn.chatgpt.com/docs/dots

