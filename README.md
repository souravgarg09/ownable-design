<div align="center">

# Ownable

**Art direction that makes AI design hard to logo-swap.**

Portable creative-direction and identity guidance for AI-built websites, apps, campaigns, portfolios, and digital experiences.

[![Version](https://img.shields.io/badge/version-3.0.0-111111)](./CHANGELOG.md)
[![License](https://img.shields.io/badge/license-MIT-111111)](./LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-111111)](https://github.com/vercel-labs/skills)

</div>

## What Ownable does

Ownable answers the question most frontend skills leave implicit:

> **What visual world should this particular subject become — and how do we keep that world intact through structure, media, interaction, responsiveness, and implementation?**

Its core test:

> If the logo and copy can be swapped for an unrelated competitor and most major visual decisions still work, the art direction is not finished.

Ownable is subject-first, reference-aware, action-first, capability-aware, provider-neutral, media-literate, and rendered-evidence driven.

It is **not** a generic frontend coding or QA mega-skill.

## v3 architecture

v3 is a full consolidation of the earlier rule set.

The core skill is now organized around:

1. **Ground** — user, task, truth, scope, subject.
2. **Discover** — reference universe and candidate visual worlds.
3. **Commit** — a compact direction contract.
4. **Produce** — structure, representation, media, motion, responsive art direction.
5. **Verify** — rendered evidence, asset validation, visitor-eye finishing, ownability.

It also adds a dedicated **media strategy** layer and a behavioral **eval suite**.

## Refine/extend vs new/replace

Ownable now protects visual authority explicitly.

- **new** — establish a world;
- **replace** — user authorized a new world;
- **extend** — add inside an existing world;
- **refine** — improve without replacing identity.

This prevents a “polish” request from silently turning into a redesign.

## Direction contract

For substantial new/replacement work, Ownable commits the chosen world before production:

- surface job;
- Creative North Star;
- visual thesis;
- identity carriers;
- composition grammar;
- type behavior;
- color/light/material behavior;
- media/proof stance;
- interaction thesis;
- responsive transformation;
- first-viewport strategy;
- anti-goals;
- must-preserve constraints.

When Impeccable already provides a direction contract, Ownable augments rather than duplicates it.

## Media strategy

Ownable distinguishes:

- documentary proof;
- subject artifacts;
- explanatory media;
- editorial/atmospheric media;
- interface/product representation;
- material/environmental media.

Then it decides whether to:

**source → edit → generate → construct semantically → remove**

Critical media is produced before layout lock when the composition depends on it.

Supported authored directions can include photography, watercolor, gouache, pencil, charcoal, ink, engraving, collage, editorial illustration, diagrams, textures, and stylized 3D when the role earns them.

Transparent cutouts require real alpha when the layout needs transparency.

See [media strategy](./skills/ownable-design/reference/media-strategy.md).

## Provider-neutral capabilities

Ownable does not depend on ChatGPT, Codex, Claude, Lovable, Higgsfield, Pollinations, or any other single provider.

It identifies the needed capability—image generation, editing/matting, web sourcing, rendering, video, 3D, motion, etc.—and uses an appropriate available native/local/MCP/connector tool.

See [capability routing](./skills/ownable-design/reference/capability-routing.md).

## Companion stack

Ownable is designed to complement:

- [Taste Skill](https://github.com/Leonxlnx/taste-skill) — frontend taste, anti-slop, composition heuristics, visual bias correction.
- [Impeccable](https://github.com/pbakaus/impeccable) — product/design methodology, visual authority, implementation, UX, accessibility, responsive discipline, verification, QA.
- [Emil Kowalski Skills](https://github.com/emilkowalski/skills) — motion and interaction craft.

The division is intentional:

**Ownable chooses and protects the world.**  
**Taste sharpens visual taste.**  
**Impeccable shapes/builds/verifies the product.**  
**Emil makes motion feel right.**

When one or more companions are missing, Ownable loads only the relevant compact fallback.

## Install

Any Agent Skills-compatible tool:

    npx skills@latest add souravgarg09/ownable-design

Install only Ownable:

    npx skills@latest add souravgarg09/ownable-design --skill ownable-design

Codex, user-wide:

    npx skills@latest add souravgarg09/ownable-design --skill ownable-design -g -a codex -y

Update:

    npx skills update ownable-design -g -y

## Use

New site:

> Use Ownable to discover and build the visual world for this subject. Ground it in real evidence, choose the strongest-fit direction, commit the direction contract, produce the media/structure the world needs, and verify the rendered result.

Existing site:

> Use Ownable in refine mode. Preserve the incumbent visual authority and required behavior, diagnose the highest-impact art-direction causes, execute justified fixes with available capabilities, re-render, and finish from a first-time visitor perspective.

Ownable does not require a special slash command.

## Repository

    ownable-design/
    ├── README.md
    ├── LICENSE
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── EVALS.md
    ├── examples/
    │   └── README.md
    └── skills/
        └── ownable-design/
            ├── SKILL.md
            └── reference/
                ├── capability-routing.md
                ├── direction-discovery.md
                ├── intervention-playbook.md
                ├── media-strategy.md
                └── standalone-quality-floor.md

## What Ownable deliberately avoids

- fixed “best UI for category X” tables;
- mandatory style recipes;
- price tiers as design-quality rules;
- framework-specific implementation recipes;
- provider-specific tool workflows;
- generic cold-audit commands;
- duplicate accessibility/performance/state/QA systems;
- duplicate detailed motion mechanics.

## Behavioral testing

See [EVALS.md](./EVALS.md). Rule changes should improve behavior on the eval set without creating a new universal style/default.

## Examples

See [examples/README.md](./examples/README.md).

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Version

Current release: **3.0.0**.

## License

[MIT](./LICENSE) © 2026 Sourav Garg
