---
name: ux-review
description: Review a proposed UI change or code diff against the user's intent and the existing product, reporting concrete UX defects before release.
---
# UX Review

Review the relevant diff and surrounding UI. Do not edit files unless asked. Start by reconstructing the intended user task from the request and code context. Look for behavior and interaction risks, not stylistic preferences alone.

Report only actionable findings, highest impact first. Each finding needs severity (Blocker/High/Medium/Polish), file or screen location, specific evidence, user consequence, and a practical correction. Check incorrect or ambiguous action hierarchy, missing state transitions, destructive-action safety, form error/retry behavior, keyboard and focus handling, mobile overflow/reachability, contrast, motion sensitivity, and departures from documented project tokens. Check whether the change preserves data and existing behavior. If no meaningful issue is found, say so and identify what you did not verify; do not manufacture issues.
