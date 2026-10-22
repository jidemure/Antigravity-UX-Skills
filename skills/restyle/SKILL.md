---
name: restyle
description: Improve the visual character of an existing interface while preserving its behavior, information architecture, and semantics.
---
# Restyle Existing UI

This workflow is for visual refinement, not a feature rewrite. Inspect the target screen and existing tokens/components first. Preserve route behavior, state logic, content, form semantics, and interaction outcomes.

Assess four axes: **type** (hierarchy, scale, line length, weight), **color** (roles, contrast, emphasis), **space** (rhythm, grouping, density), and **finish** (surfaces, borders, radii, shadows, icon consistency). Identify which choices are intentional and which are accidental defaults. Use the project's existing DESIGN.md if present; otherwise derive a compact system from existing code, or create a restrained DESIGN.md before restyling. Never fall back to a framework palette by habit.

Apply a coherent set of visual decisions rather than isolated decoration. Keep accessibility and responsive behavior intact. Explain the changes by axis and disclose if a true before/after screenshot comparison was unavailable. Do not claim behavior stayed unchanged without inspecting the affected code.
