# Dev Log — Artifact 1: Portfolio

Running log of AI interactions and the modifications made while building this site, for TCSS 490.

## 2026-10-11

**Tool used:** Claude (Claude Code CLI)

**Prompt / interaction:**
- Shared the assignment page (TCSS 490 Artifact 1 spec) and asked Claude to fetch and summarize the requirements.
- Claude identified the assignment: a front-end-only portfolio with 5 artifact cards (1 live, 4 placeholders), a personal intro, and a dev log — due the same day.
- Claude asked for: display name / GitHub username, intro content, and hosting preference.
- Provided: name (Saeed Esparza), GitHub username (`saeedesparza`), hosting choice (GitHub Pages), and a short personal bio (CS senior at UW Tacoma, into full-stack dev and AI, hobbies: hiking, gym, music).

**What Claude built:**
- `index.html` — full page structure: masthead with name/intro, five artifact cards (card 1 live with links + reflection; cards 2–5 as placeholder project ideas), footer.
- `styles.css` — custom "field notes / trail log" visual theme (hand-picked to tie together hiking + coding + music interests) using Fraunces, Source Serif 4, and JetBrains Mono from Google Fonts; a topographic-contour background texture; staggered card reveal animation; postcard-style card treatment with rotation and stamp badges for "live" vs "planned" status.
- This `devlog.md` file.
- `README.md` with setup/deploy notes.

**Modifications made after AI output:**
- (fill in here as I tweak copy, colors, or placeholder ideas before/after submission)

**Reflection:**
- The actual work was less about writing code and more about being specific with Claude about who I am and what the site should feel like — generic prompts would've gotten a generic result.
- Next step: replace placeholder ideas for Artifacts 2–5 with real projects as they're built throughout the quarter, and log each change here.

## 2026-10-18 — Artifact 2

**Tool used:** Claude Code CLI

**Interaction:** Shared the Artifact 2 spec ("Something You Will Use") and told Claude to do whatever was needed. Claude built the Trailhead Gym Log idea from card 02 in its own repo: [saeedesparza/trailhead-gym-log](https://github.com/saeedesparza/trailhead-gym-log). That repo's `LOG.md` has the full plan and change log.

**Changes here:** Card 02 went from "planned" to "live", with links to the app, repo, and log, plus a reflection.

## 2026-10-24 — Artifact 3

**Tool used:** Claude Code CLI

**Interaction:** Shared the Artifact 3 spec ("AI Inside It"). Chose to extend the gym log with a weekly coach that runs Claude Code headless (`claude -p`), so it costs nothing beyond my plan. It's built in the gym-log repo under [`coach/`](https://github.com/saeedesparza/trailhead-gym-log/tree/main/coach). That repo's `LOG.md` has the plan, the changes, and the verification.

**Changes here:** Card 03 swapped the Riff Sketchpad placeholder for Trailhead Coach (live), with links to the code, a sample review, and the log.
