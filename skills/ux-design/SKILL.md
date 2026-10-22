---
name: ux-design
description: Design and implement a user interface feature by reasoning from user intent, hierarchy, states, forms, feedback, design tokens, visual character, and responsive behavior. Invoke for new or substantially changed UI.
---
# UX Design

Deliver working UI, not just advice. First inspect the repository, the existing UI, framework conventions, and any DESIGN.md or token files. Preserve the project's architecture and existing visual language unless the user asks for a redesign.

## Workflow
1. Establish the user, their main task, context of use, and the most costly likely error. If the request omits details, infer reasonable assumptions and state them briefly; ask only when an unknown would materially change the design.
2. Define the page's primary action, supporting actions, content order, and density before editing. Make the most important next step visually and semantically clear.
3. Identify applicable states before implementation: initial/loading, empty, populated, validation, error/recovery, success, disabled, and partial/offline where relevant. Avoid decorative placeholders masquerading as real states.
4. Inspect and reuse the current design tokens and components. If absent, make a small coherent token set and document it in DESIGN.md rather than choosing arbitrary values per element.
5. Implement with semantic HTML, keyboard access, visible focus, accessible names, useful validation, and appropriate contrast. Forms must preserve entered data on recoverable errors.
6. Cover narrow screens and touch input; do not merely shrink desktop layouts. Respect reduced-motion preferences.
7. Summarize the decisions, changed files, assumptions, and any limitations. Do not claim visual verification unless it was actually performed.

Read the relevant companion skills when useful: information-hierarchy, state-completeness, form-ux, feedback-affordance, design-system, visual-character, responsive-ux.
