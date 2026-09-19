<div align="center">

# Ownable

**Art direction that makes AI design hard to logo-swap.**

A portable Agent Skill for subject-specific, concept-led, truthful digital art direction.

[![Version](https://img.shields.io/badge/version-1.0.0-111111)](./CHANGELOG.md)
[![License](https://img.shields.io/badge/license-MIT-111111)](./LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-111111)](https://github.com/vercel-labs/skills)

</div>

## Why Ownable exists

AI can make a polished interface quickly. The harder problem is making the result feel like it could only belong to **this** brand, product, person, place, or story.

Ownable focuses on that problem.

Its core test is simple:

> If you can swap the logo and copy for an unrelated competitor and most of the design still works, the art direction is not finished.

Ownable pushes the agent to mine the subject itself before reaching for templates or trends, then turn that evidence into a Creative North Star, recognizable identity carriers, purposeful structure, coherent assets, truthful proof, and subject-specific signature moments.

## What Ownable adds

- **Subject before moodboard** — derive visual vocabulary from the real product, people, place, materials, process, culture, history, and proof.
- **Creative North Star** — define a project-specific thesis that actually changes the work.
- **Identity carriers** — create recognition beyond the logo through recurring but evolving cues.
- **Logo-swap / ownability test** — catch art direction that is polished but generic.
- **Structural economy** — every section, page, and major screen must earn its place.
- **Purpose-first assets** — never invent a section just to use an available image.
- **Why this? Why here?** — every important image must justify both selection and placement.
- **Image uniqueness** — avoid exact and perceptual repetition unless reuse has a real reason.
- **Asset language** — treat photography, illustration, 3D, video, cutouts, details, and responsive variants as one visual system.
- **Capability-aware asset transformation** — create cutouts, transparent assets, cleanup, reframing, relighting, compositing, and variants when the runtime can safely do so.
- **Truth-sensitive editing** — never turn visual polish into false product, medical, architectural, credential, or proof claims.
- **Real proof over decorative prestige** — trust should come from evidence, not just luxury styling.
- **Cross-output fingerprint checks** — avoid recognizable reuse of the same hero, nav, palette, card grammar, gallery, footer, or signature trick across unrelated projects.

## Install

### Any Agent Skills-compatible tool

```bash
npx skills@latest add souravgarg09/ownable-design
```

Install only Ownable explicitly:

```bash
npx skills@latest add souravgarg09/ownable-design --skill ownable-design
```

### Codex — user-wide on this computer

Use this when you want Ownable available across your Codex projects:

```bash
npx skills@latest add souravgarg09/ownable-design --skill ownable-design -g -a codex -y
```

### Codex — current project only

Run this from the project folder:

```bash
npx skills@latest add souravgarg09/ownable-design --skill ownable-design -a codex -y
```

The portable skill itself lives at:

```text
skills/ownable-design/SKILL.md
```

> Ownable is an **Agent Skill**, not a ChatGPT account preference. Local installation applies to supported coding/agent environments on that machine. In a normal ChatGPT conversation, provide the skill file or use an environment that supports Agent Skills.

## Use it

Once installed, ask your agent to use Ownable as the art-direction layer for the work:

```text
Use Ownable while designing this website. Mine the subject before choosing a visual direction, make every section and asset earn its place, and run the logo-swap test before finalizing.
```

For an existing design:

```text
Use Ownable to review the art direction. Keep the brief and required content intact, but find anything generic, structurally unnecessary, asset-led instead of purpose-led, visually repetitive, or transferable to an unrelated brand.
```

Ownable does not require special slash commands. It is designed to improve the agent's judgment while it performs the user's actual task.

## Companion stack

Ownable is intentionally complementary rather than a replacement for broader specialist skills.

When these are installed and applicable, they remain authoritative in their domains:

- [Taste Skill](https://github.com/Leonxlnx/taste-skill) — frontend taste, anti-slop, composition, design dials, and its scoped frontend heuristics.
- [Emil Kowalski Skills](https://github.com/emilkowalski/skills) — motion, interaction feel, timing, easing, gestures, springs, and animation craft.
- [Impeccable](https://github.com/pbakaus/impeccable) — product/design-world methodology, refinement vs redesign, design systems, accessibility, implementation craft, states, responsive/technical discipline, progressive enhancement, and QA.

Ownable adds the **subject-specific art-direction and ownability layer**.

None of those companion skills are required dependencies. Ownable works standalone.

## The logo-swap test

Imagine removing the real logo and brand name from a design and replacing them with a competitor's.

If the experience still feels completely natural, the design may be category-correct but not brand-specific.

A more ownable direction should draw from things competitors cannot casually inherit: a physical material, architectural rhythm, product mechanism, cultural context, photographic behavior, founder history, local environment, making process, signature object, archive, data pattern, or another truthful characteristic of the subject.

The goal is not novelty for novelty's sake. The goal is **specificity with coherence**.

## A few important principles

### Every section earns its place

A page should not grow because templates usually contain another section, because the page looks short, or because an unused asset exists. Each major block should add information, proof, task value, interaction, narrative progression, atmosphere, or conversion support.

Required content from the brief is protected: Ownable strengthens or reframes it instead of silently deleting it.

### Purpose first; asset second

Do not create a section just to use a photograph, illustration, video, 3D object, or other supplied asset.

If an asset does not strengthen a meaningful part of the experience, leave it out.

### Every important image answers “why this?” and “why here?”

A visually attractive image is not automatically relevant. The subject matter, evidence, emotion, context, and relationship to adjacent content matter more than palette matching.

### Consistency is not repetition

A coherent system can share typography, materials, spacing logic, hierarchy, and behavior while still changing composition and imagery as the content changes. Repeating the same card grid, crop, hero structure, or effect everywhere is not consistency.

## Examples

See [`examples/README.md`](./examples/README.md) for short examples of applying Ownable without turning it into a style preset.

## What Ownable deliberately does not contain

Ownable stays narrow on purpose. It does **not** add:

- generic “cold audit” commands;
- price tiers as design-quality rules;
- framework-specific recipes;
- Claude/Codex/ChatGPT/Figma-specific design philosophy;
- duplicate motion standards already handled better by motion specialists;
- duplicate accessibility/performance/state/QA systems;
- generic frontend advice a competent implementation skill already knows.

The value is not the number of rules. The value is a focused art-direction lens that other design and implementation skills can compose with.

## Repository structure

```text
ownable-design/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── examples/
│   └── README.md
└── skills/
    └── ownable-design/
        └── SKILL.md
```

## Versioning

Ownable follows semantic versioning for public releases. Rule changes that materially alter agent behavior are documented in [`CHANGELOG.md`](./CHANGELOG.md).

Current release: **1.0.0**.

## Contributing

Contributions are welcome when they make Ownable sharper without turning it into a generic mega-skill. See [`CONTRIBUTING.md`](./CONTRIBUTING.md).

## License

[MIT](./LICENSE) © 2026 Sourav Garg
