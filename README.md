# Antigravity UX Skills

An independently authored Antigravity skill bundle inspired by the publicly documented UX Engine feature set. It is not the paid UX Engine product, does not contain its private ZIP/source, and does not claim to reproduce its undisclosed two sub-agents. It adapts the visible workflows to Google's documented Antigravity skill format.

## Included

Four explicit workflows (each invokable as a skill slash command): `/ux-design`, `/ux-audit`, `/ux-review`, and `/restyle`.

Nine focused specialist skills, available for autonomous invocation: `intent-discovery`, `information-hierarchy`, `state-completeness`, `form-ux`, `feedback-affordance`, `ux-auditor`, `design-system`, `visual-character`, and `responsive-ux`.

## Install in Antigravity 2.0

**For one project:** copy the included `.agents/skills/` directory into the root of the project you open in Antigravity. These workspace skills can be committed and shared with that project.

**For all projects:** copy each skill folder into `~/.gemini/config/skills/` on your computer. Antigravity's Customizations panel can show discovered skills. Start a new conversation or reload customizations if they do not appear immediately.

Each skill is a folder containing `SKILL.md`, following the format in Google's Agent Skills documentation. Invoke the four workflows by typing `/ux-design`, `/ux-audit`, `/ux-review`, or `/restyle`. Specialist skills can be invoked explicitly by name or applied by the agent when relevant.

## Suggested first use

Open an existing UI project, install the skills, then ask: “Use `/ux-audit` to inspect the settings page. First report findings only; do not edit.” For implementation, try: “Use `/ux-design` to add an invite-member flow. Inspect the existing design system, cover all states, and preserve current architecture.”

## Important limits

This is a prompt-and-instruction skill pack. It does not add a UI, custom MCP server, paid plugin loader, external model, or guaranteed two-agent orchestration. Agent results depend on Antigravity's model, project context, permissions, and available browser/test tools. It uses original wording and practical behaviors derived from public product descriptions, not proprietary paid contents.
