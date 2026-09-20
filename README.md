<div align="center">

# Ownable

**Art direction that makes AI design hard to logo-swap.**

A portable Agent Skill for subject-specific, concept-led, truthful digital art direction.

[![Version](https://img.shields.io/badge/version-1.4.0-111111)](./CHANGELOG.md)
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
- **Distributed identity carriers** — create recognition beyond the logo and carry it past the hero into quieter surfaces through recurring but evolving cues.
- **Logo-swap / ownability test** — catch art direction that is polished but generic.
- **Cultural specificity without costume** — use real materials, rituals, language, craft, places, objects, archives, and history instead of token “heritage” motifs.
- **Content-led composition** — let the real content, evidence, imagery, task, and hierarchy determine form instead of pouring everything into predetermined section shells.
- **Active art-direction intervention** — inspect every major section, visible image/media moment, and meaningful motion/interaction moment in scope, then keep, fix, replace, restructure, add, simplify, or remove what the experience actually needs.
- **Root-cause diagnosis** — fix the real structural, content, proof, sequencing, asset, or concept problem instead of decorating the symptom.
- **Structural economy** — every section, page, and major screen must earn its place.
- **Structural surgery and ordering** — reorder, regroup, merge, split, replace, or remove sections, tabs, navigation items, and content groups when the hierarchy or flow genuinely improves.
- **Purpose-first assets** — never invent a section just to use an available image.
- **Why this? Why here?** — every important image must justify both selection and placement.
- **Asset intervention ladder** — keep, reframe, transform, replace with a stronger real asset, generate, or remove according to the actual problem.
- **Motion intervention ladder** — keep, retarget/resequence, simplify, replace, add, or remove animation according to its real role.
- **Web-sourced real imagery when appropriate** — proactively find better real assets when needed, while preserving provenance, truth, and usage rights.
- **Image uniqueness** — avoid exact and perceptual repetition unless reuse has a real reason.
- **Asset language** — treat photography, illustration, 3D, video, cutouts, details, and responsive variants as one visual system.
- **Concept-led asset commissioning** — the supplied asset folder is not the ceiling; create, source, or clearly request missing assets that a strong concept genuinely needs.
- **Bespoke illustrative generation** — proactively create hand-drawn, painted, etched, collage, textured editorial, mixed-media, stylized 3D, or other subject-appropriate visuals when they genuinely earn the role.
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
Use Ownable to actively improve the art direction, not just critique it. Keep the brief and required content intact, audit every major section, visible image/media moment, and meaningful motion/interaction moment in scope; replace or remove weak imagery; simplify, replace, add, or remove motion where needed; merge or replace redundant sections; reorder structure when the flow improves; and run the logo-swap test before finalizing.
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

### Ownable acts, not only critiques

When the user has asked for modification and the runtime can edit the work, Ownable should not stop after saying that an image or section is weak.

For every major section and visible image/media moment in scope, the agent makes an explicit art-direction decision. A weak photo can be reframed, cleaned, replaced with a stronger real source, regenerated in a suitable medium, or removed. A weak structural block can be refined, regrouped, reordered, merged, split, replaced, or removed.

The goal is **not maximum change**. The goal is the least destructive intervention that solves the real problem and improves the whole experience.

### Asset intervention ladder

A useful default decision order is:

1. keep;
2. reframe;
3. transform;
4. replace with a stronger real asset;
5. generate a better-fitting asset;
6. remove the image.

The ladder is not mechanical. Proof-sensitive moments prefer verified real imagery. Illustration or generated photography is used only when truthful for the role.

When web access is available, the agent may search for stronger real imagery. For production use, web visibility alone is not permission: prefer official, owned, appropriately licensed, public-domain, or otherwise approved assets.

### Motion is art direction too

Ownable treats animation and interaction as another authored material, not as automatic polish.

The agent may add, remove, simplify, replace, or redirect motion when doing so improves identity, hierarchy, explanation, continuity, pacing, feedback, or a genuinely earned signature moment.

A useful motion intervention ladder is:

1. keep;
2. retarget or resequence;
3. simplify;
4. replace;
5. add;
6. remove.

Every meaningful motion moment should answer:

- **Why this motion?**
- **Why this element?**
- **Why now?**

Ownable decides whether the motion belongs and what conceptual role it serves. Emil Kowalski skills remain authoritative for the actual craft of motion — timing, easing, springs, gestures, interruptibility, origins, reduced motion, and related mechanics.

### Structural surgery and ordering

Ownable may reorder or regroup sections, tabs, navigation items, and content groups when the current sequence is weak. It may merge two sections serving the same job, split an overloaded one, or replace an entire section concept when polishing the existing shell would preserve the wrong structure.

Required content, routes, functionality, legal/safety material, and other brief constraints remain binding. In task-oriented products, usability and native expectations outrank storytelling.

### Every section earns its place

A page should not grow because templates usually contain another section, because the page looks short, or because an unused asset exists. Each major block should add information, proof, task value, interaction, narrative progression, atmosphere, or conversion support.

Required content from the brief is protected: Ownable strengthens or reframes it instead of silently deleting it.

### Purpose first; asset second

Do not create a section just to use a photograph, illustration, video, 3D object, or other supplied asset.

If an asset does not strengthen a meaningful part of the experience, leave it out.

### Every important image answers “why this?” and “why here?”

A visually attractive image is not automatically relevant. The subject matter, evidence, emotion, context, and relationship to adjacent content matter more than palette matching.

### Content should shape composition

Do not start with a reusable section formula and pour every kind of content into it. The actual content should influence the form: copy length, proof, imagery, product behavior, hierarchy, task, and narrative all matter.

A repeated layout is useful when the content really has the same job. Repeating it because it is convenient is template behavior.

### The supplied asset folder is not the ceiling

Ownable does not require the agent to accept an incomplete asset pack as the limit of the concept. If a meaningful section needs a missing cutout, detail, contextual scene, diagram, illustration, texture, crop, or other visual role, the agent should create it when safe, source a truthful real asset when authenticity matters, or specify/request it clearly.

The inverse rule still applies: do not commission new visuals just because empty space exists. Every commissioned asset must earn its role.

### Bespoke illustration is a first-class tool, not filler

Ownable can proactively use AI-generated or agent-created non-photographic imagery when the concept calls for it: hand-drawn work, painting-like treatments, etching, collage, textured editorial art, diagrammatic visuals, stylized 3D, and other authored directions.

The test is not “would this look beautiful?” It is the same test applied to every asset:

- **Why this?**
- **Why here?**
- What does this visual communicate that the surrounding content needs?

A stylized illustration should reinforce the subject, North Star, atmosphere, symbolism, process, memory, ritual, or narrative. It should not exist merely because a section looks empty. Proof-critical moments still use truthful documentary imagery.

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

Current release: **1.4.0**.

## Contributing

Contributions are welcome when they make Ownable sharper without turning it into a generic mega-skill. See [`CONTRIBUTING.md`](./CONTRIBUTING.md).

## License

[MIT](./LICENSE) © 2026 Sourav Garg
