---
name: state-completeness
description: Define and implement realistic UI states, including loading, empty, error, success, partial, offline, and disabled states where relevant.
---
# State Completeness

For each interactive component, enumerate applicable states: idle, loading, empty/no results, populated, invalid, error, success, disabled, stale/partial, and offline. Do not mechanically add every state where it makes no sense. For every state specify what the user sees, what actions remain possible, and how they recover or continue. Loading should prevent duplicate submissions where needed and communicate progress; errors should explain the issue and next step; empty states should explain how to begin; success should confirm the result. Preserve user-entered work when retry is possible. Ensure state changes are announced accessibly when necessary.
