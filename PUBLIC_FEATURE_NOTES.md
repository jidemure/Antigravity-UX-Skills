# What UX Engine publicly appears to do

Research date: 2026-10-22.

The product's official page describes UX Engine as a developer-agent plugin rather than a standalone visual editor. Its pitch is that it prompts an agent to reason about UX and visual decisions before writing UI. Publicly listed support includes Claude Code, Cursor, Codex, and OpenCode. Four named workflows are `/restyle`, `/ux-audit`, `/ux-design`, and `/ux-review`. Nine named capabilities are intent discovery, information hierarchy, state completeness, form UX, feedback and affordance, UX auditing, design system creation/application, visual character, and responsive behavior under 640px. The page also claims two sub-agents, but does not publicly identify or detail them.

The official pattern library provides 76 public breakdowns across fundamentals, system-level patterns, and component families. Examples include loading and error states, autosave, destructive actions, responsive navigation, form validation timing, reduced-context interaction patterns, and design tokens.

I inspected the TikTok profile, three individual posts, and a further indexed video page. The account's accessible videos are UX-pattern teaching clips, not clear screen recordings of someone invoking the paid UX Engine plugin. Their captions link the ideas to UX Engine, but that alone does not prove the plugin performed the changes shown. The icon clip says “Same icons. One stroke width. Suddenly expensive”; a visible frame shows an icon consistency example and calls out consolidating stroke weights, size variation, and accent usage. Another clip labels a “Floating card, gradient blob, three social buttons” hero as AI-made. A separate caption, “One drag. Five decisions nobody notices,” points toward detailed interaction breakdowns. The captions support treating these as design heuristics, not as exact hidden-plugin rules. These observations prompted additions to the bundle's visual-character and design-system skills.

The Antigravity official skills documentation says a skill is a folder with a `SKILL.md` file and YAML frontmatter. For Antigravity 2.0, workspace skills live under `<workspace-root>/.agents/skills/<skill-folder>/`; global skills live under `~/.gemini/config/skills/<skill-folder>/`. Skills can be invoked autonomously or using `/<skill-name>`. The bundle here follows that structure.

This is a public-feature-based independent implementation, not an exact copy of the paid download. The paid ZIP's source, internal prompts, and agent design are not public, so their exact behavior cannot be verified from the accessible information.

## Sources

- Product page: https://designmotionhq.com/
- Public pattern library: https://designmotionhq.com/patterns
- About and Design System Blueprint description: https://designmotionhq.com/about
- TikTok public profile: https://www.tiktok.com/@designmotionhq
- TikTok icon clip: https://www.tiktok.com/@designmotionhq/video/7689987121792372001
- TikTok visual-pattern clip: https://www.tiktok.com/@designmotionhq/video/7689051479688187169
- TikTok interaction-pattern clip: https://www.tiktok.com/@designmotionhq/video/7694000747322641697
- Google Antigravity agent skills docs: https://antigravity.google/docs/skills/
- Google Antigravity MCP docs: https://antigravity.google/docs/mcp/
