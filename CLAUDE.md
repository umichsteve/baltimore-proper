# baltimore-proper

Coming-soon page for Baltimore Proper, an independent guide to eating, drinking, and wandering well in Baltimore — a VELAR network publication launching 2026 (https://baltimoreproper.com/).

## Stack

- Static HTML, single small index.html (~4 KB), everything inline
- Deploy: Vercel (.vercel/project.json; no vercel.json)

## Conventions

- Cloud-only workflow: no local dev servers or venvs; verify via preview deploys.
- Editorial and brand quality is the default lens for changes here.
- The entire page (markup, styles, copy) lives inline in index.html.

## Non-goals

- Don't add frameworks, build steps, or dependencies not already present without asking.
- It's a placeholder page — don't build out full-site features without asking.

## Handoff protocol

If `HANDOFF.md` exists at the repo root: read it before anything else, treat its "Done when" as acceptance criteria and "Non-goals" as hard boundaries, run its Verify steps, and delete the file in the final commit. Format and full rules: `.claude/skills/pr-handoff/SKILL.md`.
