<div align="center">

# Ownable

**Art direction that makes AI design hard to logo-swap.**

A portable, capability-aware Agent Skill for subject-specific visual-world discovery, art direction, active intervention, media production, and rendered verification.

[![Version](https://img.shields.io/badge/version-2.1.0-111111)](./CHANGELOG.md)
[![License](https://img.shields.io/badge/license-MIT-111111)](./LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-111111)](https://github.com/vercel-labs/skills)

</div>

## Why Ownable exists

AI is good at producing polished interfaces. It is much worse at deciding **which visual world actually belongs to this subject** rather than to any competent competitor.

Ownable addresses that problem from direction selection through execution.

Its core test:

> If you can swap the logo and copy for an unrelated competitor and most of the design still works, the art direction is not finished.

## What 2.1 adds

Ownable now treats the runtime as a set of **capabilities rather than named vendors**. If a design needs image generation, background removal, a transparent cutout, video, 3D, web sourcing, rendering, or another intervention, the agent should use the best appropriate capability available in that environment—native tool, MCP/connector, local tool, or compatible provider.

This makes the same skill usable across ChatGPT/Codex, Claude environments, Lovable, and other agents without binding the design logic to any one of them.

It also adds a compact standalone quality floor for environments where Taste, Impeccable, or Emil are not installed, while preserving strict specialist precedence when they are.

Ownable now incorporates complementary strengths seen in strong public frontend-design skills: explicit user/task/context fit, a visual thesis, interaction thesis when warranted, deliberate typography, stronger anti-default detection, responsive/functional hard gates, commitment after direction selection, and honest rendered verification—without copying those skills' full implementation systems.

## What 2.0 changed

Ownable 2.0 is a consolidation release, not a bigger rule pile.

The previous 46-rule flat list has been reorganized into five phases:

1. **Ground** — subject, truth, constraints, North Star.
2. **Discover** — global reference discovery and visual-language selection.
3. **Architect** — content, structure, sequence, representation.
4. **Produce** — active, capability-aware intervention.
5. **Verify** — rendered evidence and first-time-visitor finishing.

The core skill is shorter and delegates detailed workflows to conditional references.

## Visual-language discovery

Ownable does not contain a fixed list of “best UI styles.”

Glassmorphism, bento, editorial, neo-brutalism, skeuomorphism, minimalism, futurism, and similar labels are **vocabulary**, not presets.

A direction can combine dimensions when coherent:

- bento-like structure + documentary photography;
- editorial composition + restrained translucent surfaces;
- tactile material cues + utilitarian typography;
- cinematic imagery + quiet product UI.

Or it can create a project-specific visual language with no useful trend name at all.

The agent searches globally across digital work and adjacent disciplines—editorial, architecture, packaging, industrial design, fashion, signage, maps, archives, film, photography, physical materials, and more—then chooses by fit rather than fashion.

See [direction discovery](./skills/ownable-design/reference/direction-discovery.md).

## Action-first behavior

For build/redesign/improvement tasks:

**audit is diagnosis; the fix is the deliverable.**

Ownable expects the agent to use available capabilities rather than stop at recommendations.

Examples:
- source a stronger legitimate real image;
- generate an earned watercolor, pencil, editorial, photographic, diagrammatic, or 3D asset;
- remove a background and create a true transparent cutout;
- clean/reframe/relight/composite imagery truthfully;
- merge or replace redundant sections;
- reorder navigation/tabs/content;
- change the representational medium;
- add, fix, simplify, or remove an interaction;
- re-art-direct mobile instead of merely shrinking desktop;
- render the result and inspect what actually shipped.

See [intervention playbook](./skills/ownable-design/reference/intervention-playbook.md).

For portable tooling behavior, see [capability routing](./skills/ownable-design/reference/capability-routing.md). For environments missing specialist companions, see [standalone quality floor](./skills/ownable-design/reference/standalone-quality-floor.md).

## Install

Any Agent Skills-compatible tool:

    npx skills@latest add souravgarg09/ownable-design

Install only Ownable:

    npx skills@latest add souravgarg09/ownable-design --skill ownable-design

Codex, user-wide:

    npx skills@latest add souravgarg09/ownable-design --skill ownable-design -g -a codex -y

Update an existing global install:

    npx skills update ownable-design -g -y

## Use it

For a new website:

> Use Ownable to discover and build a subject-specific visual world. Do not start from a named UI style. Research the subject and reference universe, choose the strongest-fit direction, execute it, and verify the rendered result.

For an existing site:

> Use Ownable to improve this site action-first. Preserve required truth/functionality, diagnose the highest-impact art-direction problems, execute the fixes with available tools, re-render, and finish from a first-time visitor perspective.

Ownable does not require special slash commands.

## Companion stack

Ownable is complementary to specialist skills:

- [Taste Skill](https://github.com/Leonxlnx/taste-skill) — frontend taste, anti-slop, composition, design dials, scoped visual heuristics.
- [Emil Kowalski Skills](https://github.com/emilkowalski/skills) — motion and interaction craft.
- [Impeccable](https://github.com/pbakaus/impeccable) — product/design-world methodology, refinement vs redesign, design systems, UX, accessibility, implementation craft, responsive/technical discipline, progressive enhancement, verification, and QA.

When installed and applicable, those skills remain authoritative in their domains.

Ownable adds the **subject-specific visual-world, reference-discovery, medium-choice, intervention, and ownability layer**.

## Core principles

### Subject before style

Mine the real product, people, place, process, materials, history, culture, artifacts, behavior, and proof before reaching for a trend.

### Style is vocabulary, not identity

A label such as glass, bento, editorial, brutalist, minimal, or skeuomorphic cannot be the Creative North Star by itself.

### References are a universe, not a template library

Search beyond UI galleries. The right direction may come from an archive, a building, a machine, packaging, an instrument, a map, an exhibition, or an audience's familiar visual culture.

### Content shapes composition

Do not pour every content type into the same card grid or split section.

### Every structural unit earns its place

Merge, split, reorder, replace, or remove optional structure when the experience improves.

### Medium choice is part of art direction

Text, image, illustration, diagram, chart, video, 3D, motion, interaction, sound, or silence are choices—not quotas.

### Weak assets are not sacred

Keep, reframe, transform, replace, generate, or remove based on what the concept actually needs.

### Truth outranks decorative prestige

Proof-sensitive moments use verified evidence. Generated atmosphere must not impersonate documentary proof.

### Visual claims require visual evidence

Code correctness is not proof that a page looks good. When preview/rendering exists, inspect the built experience.

### First-time visitor beats implementer bias

Finish by judging the actual opening impression, focal point, clarity, credibility, pacing, repetition, asset quality, transitions, action clarity, and unfinished/templated feel.

## Repository structure

    ownable-design/
    ├── README.md
    ├── LICENSE
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── examples/
    │   └── README.md
    └── skills/
        └── ownable-design/
            ├── SKILL.md
            └── reference/
                ├── direction-discovery.md
                ├── intervention-playbook.md
                ├── capability-routing.md
                └── standalone-quality-floor.md

## What Ownable deliberately does not contain

Ownable does not maintain:

- a fixed catalog of approved UI styles;
- price tiers as design-quality rules;
- generic cold-audit commands;
- framework-specific frontend recipes;
- platform-specific ChatGPT/Claude/Codex/Figma philosophy;
- duplicate motion rules already owned by motion specialists;
- duplicate accessibility/performance/state/QA systems;
- generic implementation guidance better handled by specialist skills.

## Examples

See [examples/README.md](./examples/README.md).

## Contributing

Contributions are welcome when they sharpen subject-specific art direction without turning Ownable into a generic mega-skill. See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Versioning

Ownable follows semantic versioning.

Current release: **2.1.0**.

## License

[MIT](./LICENSE) © 2026 Sourav Garg
