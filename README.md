# Claude-Design

`Claude-Design` is for design-heavy work in HTML, CSS, JavaScript, and React. It helps AI coding tools produce polished visual artifacts instead of generic mockups.

It is designed for work such as:

- landing pages
- slide decks
- interactive prototypes
- UI mockups
- product concept explorations
- animation studies
- side-by-side design variations

It guides the agent to:

- choose the right visual format for the task
- ask for missing design context when needed
- preserve existing brand or design-system language
- use fixed-size presentation canvases when appropriate
- build cleaner HTML/React artifacts with stronger visual direction
- avoid common low-quality design tropes

## When To Use This Skill

Use this skill when you want your AI coding tool to create visual deliverables in code, especially when the default output would otherwise be too plain, too generic, or too UI-framework-driven.

Typical prompts:

- "Use Claude-Design to build a polished landing page."
- "Use Claude-Design to create a clickable product prototype."
- "Use Claude-Design to turn this content into presentation slides in HTML."
- "Use Claude-Design to explore three visual directions for this dashboard."

## Install In Common AI Coding Tools

## Codex

Install:

```text
$skill-installer install https://github.com/Echoxiawan/Claude-Design/tree/main
```

Then restart Codex.

Use:

```text
Use the Claude-Design skill to create a high-fidelity landing page in HTML.
```

## Claude Code

Install:

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/Echoxiawan/Claude-Design.git ~/.claude/skills/Claude-Design
```

Then restart Claude Code.

Use:

```text
Use Claude-Design to create an interactive onboarding prototype.
```

## Claude Web / Claude Desktop

Install:

1. Download `https://github.com/Echoxiawan/Claude-Design`
2. Zip the skill folder
3. In Claude, open `Customize > Skills`
4. Choose `Upload a skill`
5. Upload the ZIP and enable it

Use:

Mention `Claude-Design` directly in your prompt when needed.

## Other Tools

If another AI coding tool supports the Agent Skills / `SKILL.md` pattern, install this folder according to that tool's local skills directory or skill import workflow.

If a tool does not support native skills, use the contents of `SKILL.md` as a reusable project rule or system instruction.
