# Contributing to Ownable

Ownable is deliberately narrow: **subject-specific art direction, visual-language discovery, medium choice, intervention, and ownability**.

Contributions are welcome when they sharpen that purpose without turning the repository into a generic frontend mega-skill.

## Before proposing a rule

Ask these questions:

1. Is this fundamentally about subject-specific art direction or ownability?
2. Is the behavior already covered by an existing rule that should be clarified instead?
3. Would the detail fit better in a conditional reference file?
4. Is it already owned better by Taste, Emil Kowalski skills, Impeccable, or another specialist?
5. Is this a design principle, or merely a provider-specific tool recipe that belongs in capability routing?
6. Does the behavior remain valid if the image/browser/coding provider changes?
7. Does the proposal improve agent behavior in a concrete scenario?
8. Does it reduce template/default behavior rather than create a new default?

Prefer **merge/refine** over adding another flat rule.

## Do not add

Avoid proposals that primarily add:

- fixed style catalogs or “best UI for category X” tables;
- price tiers;
- framework-specific recipes;
- generic accessibility/performance/QA checklists;
- duplicated motion mechanics;
- tool-specific ChatGPT/Claude/Codex/Figma workflow philosophy;
- personal project names or user-specific context.

## Style references

Named aesthetics may appear as examples, but must never become mandatory presets.

A useful contribution should teach the agent to reason about **why** a visual language fits, how to transform references, or how to avoid default bias.

## Pull requests

A good PR should:

- state the behavior problem;
- explain why existing rules do not already solve it;
- identify any specialist-skill overlap;
- show before/after agent behavior;
- update examples/docs if public behavior changes;
- preserve the brief/truth/scope guards;
- avoid rule-count growth when a merge or reference-file change would be cleaner.

## Versioning

Behavioral changes should be documented in CHANGELOG.md.

Use semantic versioning:
- patch: wording/clarity without behavior change;
- minor: additive behavior that remains compatible;
- major: meaningful reorganization or contract change.
