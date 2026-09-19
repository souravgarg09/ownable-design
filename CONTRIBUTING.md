# Contributing to Ownable

Ownable is intentionally narrow. Contributions should make the art-direction judgment sharper without turning the skill into a generic frontend handbook.

## Good contributions

- identify a repeatable art-direction failure mode that is not already covered;
- sharpen a rule so an AI agent can apply it more reliably;
- improve portability across Agent Skills-compatible tools;
- reduce ambiguity, contradiction, or accidental over-prescription;
- improve examples that teach the principle without creating a style preset;
- reduce overlap with specialist skills while preserving standalone usefulness.

## Please avoid

- framework-specific implementation recipes;
- generic frontend QA checklists;
- hard-coded visual trends presented as timeless rules;
- duplicate motion, accessibility, performance, state, or design-system guidance already owned by specialist skills;
- commands for tasks an agent can already infer from the user's request;
- rules added only to make the skill longer.

## Rule proposal checklist

Before proposing a new rule, ask:

1. Does it materially improve subject-specific art direction or ownability?
2. Is it general enough to work across brands and categories without becoming a style preset?
3. Is the same problem already handled better by Taste Skill, Emil Kowalski Skills, Impeccable, or another specialist?
4. Can the rule be expressed as a durable principle rather than a temporary trend?
5. Does it preserve the user's brief, verified product truth, and required functionality?

## Changes

For behavior-changing edits, update `CHANGELOG.md` and the version in `skills/ownable-design/SKILL.md` as appropriate.

A strong contribution should reinforce Ownable's central question:

> Does this design genuinely belong to its subject?
