# Contributing to Ownable

Ownable is deliberately narrow: **subject-specific art direction, visual-world discovery, direction commitment, medium choice, intervention intent, and ownability**.

Contributions are welcome when they improve those behaviors without turning Ownable into a generic frontend mega-skill.

## Before proposing a rule

Ask:

1. Is this fundamentally an art-direction / ownability behavior?
2. Is the problem already covered by an existing core rule that should be clarified instead?
3. Does the detail belong in a conditional reference rather than core?
4. Does Taste, Impeccable, Emil, or another specialist already own it better?
5. Is it a design principle or merely a provider/framework recipe?
6. Would the behavior remain valid if the runtime/tools changed?
7. Which behavioral eval in EVALS.md should improve?
8. Could this proposal accidentally create a new universal design default?

Prefer **merge, tighten, or move** over adding another flat rule.

## Core vs references

Put only cross-project art-direction judgment in SKILL.md.

Use references for:
- direction discovery;
- media strategy;
- intervention ladders;
- capability routing;
- standalone specialist fallbacks.

Do not place provider-specific commands or framework recipes in core.

## Companion discipline

Do not shadow-copy:
- Taste's detailed frontend taste heuristics;
- Impeccable's product/system/QA methodology;
- Emil's motion mechanics.

Ownable should tell the agent **what belongs and why**; specialists should own detailed execution in their domains.

## Do not add

Avoid:
- fixed style catalogs;
- “best style for industry X” tables;
- mandatory palettes/fonts/layout recipes;
- fixed price-quality tiers;
- generic QA/accessibility/performance checklists;
- arbitrary animation timing rules;
- project-specific/client-specific rules;
- personal user context.

## Pull requests

A good PR should:
- identify a reproducible agent behavior problem;
- show why existing rules are insufficient;
- state whether scope is core or reference;
- identify companion overlap;
- identify the eval case(s) improved or add a new eval;
- show before/after expected behavior;
- preserve truth/scope/accessibility/safety guards;
- reduce defaults rather than create a new one;
- update README/examples/changelog when public behavior changes.

## Versioning

- patch — wording/clarity, no behavior change;
- minor — compatible new behavior/reference;
- major — architecture/contract change.
