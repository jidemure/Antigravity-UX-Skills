---
name: ux-audit
description: Audit an existing interface for usability, consistency, accessibility, responsive behavior, and missing states. Use when asked to inspect, diagnose, or improve UX.
---
# UX Audit

Inspect the requested screen and its relevant source. Default to read-only diagnosis. If the user explicitly asks to fix findings, fix only agreed findings and report what changed.

Organize findings by severity: **Blocker** (task cannot be completed or serious harm/data loss), **High** (likely failure or costly error), **Medium** (friction or inconsistency), **Polish** (minor refinement). For every finding include location, observed evidence, user impact, and a concrete recommended change. Separate verified defects from risks inferred from incomplete context. Avoid generic advice and do not invent user research.

Check: task intent and primary action; hierarchy and scanning; content density; empty/loading/error/success states; form labels, validation and recovery; feedback and affordances; keyboard/focus/contrast; responsive layout and touch targets; consistency with existing tokens; motion and reduced-motion. Order findings by impact, not by visual preference. End with the smallest useful fix sequence. Read companion skills for detailed criteria when applicable.
