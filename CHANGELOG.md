# Changelog

All notable changes to Ownable are documented here.

## 2.1.0 — 2026-09-21

- made Ownable explicitly provider-neutral and capability-aware across agent environments;
- added capability discovery/routing for code editing, rendering, screenshots, web/reference search, real-asset retrieval, image generation, image editing/matting/background removal, diagrams, motion, video, 3D, audio, MCP/connectors, and local tools;
- added portable image-generation behavior so Ownable uses an available native tool, MCP/connector, or compatible provider rather than depending on a named service;
- added real-alpha/background-removal guidance and output validation, including edge/holes checks and fallback to another editing/matting capability when a generator cannot produce correct transparency;
- added generated/edited asset inspection as a required step rather than trusting successful tool calls or prompts;
- added a standalone quality floor for environments where Taste, Impeccable, or Emil are partially or wholly unavailable;
- strengthened companion mode so Taste owns detailed anti-slop/composition heuristics, Impeccable owns product/system/execution/verification methodology, and Emil owns motion mechanics;
- integrated complementary principles from strong public frontend-design skills: explicit user/task/context fit, visual thesis, optional interaction thesis, deliberate typography, functional/accessibility hard gates in standalone mode, stronger anti-default checks, bounded rendered verification, and commitment after direction selection;
- strengthened the anti-default check against common generated-design fingerprints while preserving that any pattern can be valid when the brief truly earns it;
- added a commitment rule preventing selected visual directions from being averaged back into generic “premium” design during implementation;
- kept provider names out of core design logic; named tools/services may appear only as interchangeable portability examples.

## 2.0.0 — 2026-09-21

Major architecture release.

- replaced the 46-rule flat structure with a five-phase operating system: Ground → Discover → Architect → Produce → Verify;
- added explicit visual-language discovery and best-fit direction selection rather than relying on the agent's first familiar aesthetic;
- added global reference-universe guidance spanning digital work, subject evidence, competitors, audience culture, editorial/print, packaging, architecture/interiors, industrial/automotive design, fashion, photography, film/titles, signage/wayfinding, exhibitions, maps, archives, technical graphics, physical materials, games/performance, and other relevant disciplines;
- added “style is vocabulary, not identity”: named aesthetics such as glass, bento, minimal, editorial, brutalist, skeuomorphic, futuristic, etc. can describe dimensions but cannot serve as the Creative North Star by themselves;
- added visual-language decomposition across composition, typography, color/light, material, geometry/chrome, imagery/illustration, density/rhythm, information representation, motion/interaction, and responsive transformation;
- added candidate-world exploration for open directions, with Impeccable's current direction-selection workflow taking precedence when available and a compact Ownable fallback otherwise;
- added explicit fit-over-fashion and familiarity-bias checks;
- added reference-abstraction-depth guidance to encourage principle translation instead of surface cloning;
- added coherent-hybrid rules while rejecting “Frankenstyle” trend stacking;
- preserved and consolidated content-led composition, structural economy/surgery, sequence/flow, representation choice, responsive re-art-direction, visual economy, repetition discipline, and cross-project fingerprint checks;
- preserved action-first execution: audit is diagnosis and the changed artifact is the deliverable when tools/scope allow;
- consolidated asset rules into a clearer source-pool/intervention model while preserving web sourcing, generation, watercolor/gouache/pencil/charcoal/ink/engraving/collage/editorial/3D possibilities, true alpha cutouts/background removal, truthful editing, responsive variants, proof/provenance guards, and image-repetition discipline;
- preserved motion as an art-direction material while deferring motion mechanics to Emil Kowalski skills;
- preserved rendered-evidence requirements, high-impact-first triage, first-time visitor finishing, and no-fake-capability behavior;
- moved detailed direction discovery and intervention ladders into conditional reference files so the core skill stays readable and composable;
- updated contributing and GitHub templates to prefer rule consolidation, specialist deference, and anti-default behavior over rule-count growth.

## 1.6.0 — 2026-09-21

- changed Ownable's default modification behavior from critique-capable to explicitly action-first: diagnosis chooses the intervention; the changed artifact is the deliverable;
- added a default execution loop: understand → inspect rendered evidence → prioritize → execute → re-render → fix remaining high-impact issues → finish;
- requires agents to use available capabilities to perform justified fixes instead of handing executable work back to the user as recommendations;
- explicitly covers capability-triggered sourcing, image generation, background removal/alpha cutouts, cleanup, reframing, relighting, compositing, responsive variants, structural edits, diagrams, motion/interaction implementation, video/3D treatments, and other supported interventions;
- added rendered-evidence-before-visual-claims: source inspection alone cannot prove composition, crop, polish, atmosphere, responsiveness, or visual impact;
- added representative visual inspection for substantial web work, while deferring detailed verification mechanics to Impeccable when active;
- added high-impact-first triage so concept/first impression/structure/major media/proof/hierarchy are fixed before micro-polish;
- added a first-time visitor-eye finish pass covering opening impression, focal point, clarity, credibility, pacing, repetition, dead areas, asset quality, section transitions, delight, action clarity, templatedness, and unfinished feel;
- requires bounded finishing rather than endless subjective tweaking;
- preserves no-fake-capability behavior: Ownable must not claim an asset, edit, animation, or visual verification was completed when the environment could not actually perform it.

## 1.5.0 — 2026-09-20

- generalized Ownable from image/structure/motion intervention into medium-agnostic art-direction intervention;
- explicitly treats typography, color/material language, content framing, imagery, illustration, iconography/graphic marks, diagrams, information graphics, data visualization, motion, interaction, video, 3D/spatial media, sound, backgrounds/environmental layers, proof presentation, and responsive presentation as editable art-direction materials;
- added the universal medium test: “why this medium, why here, and why this treatment?”;
- added representation-before-decoration: agents may change the representational form itself when another medium communicates the content more clearly or more meaningfully;
- explicitly allows diagrams, timelines, maps, comparisons, charts, process graphics, interactive explainers, video, 3D/spatial views, audio moments, or deliberate absence of media when they are the right representation;
- added truth guards for information graphics so agents do not invent data, precision, geography, causality, or relationships for visual sophistication;
- added responsive re-art-direction: supported contexts may use different crops, assets, media types, sequencing, interaction models, detail levels, signature moments, or emphasis while preserving identity and truth;
- preserves specialist boundaries: Taste/Impeccable own detailed typography, color, layout, UX, system, and responsive execution; Emil owns motion mechanics; Ownable owns medium choice, conceptual role, and subject-specific fit.

## 1.4.0 — 2026-09-20

- promoted motion and interaction to first-class Ownable art-direction materials alongside imagery and structure;
- expanded active intervention to audit meaningful motion/interaction moments in scope, not only sections and imagery;
- added a motion intervention ladder: keep → retarget/resequence → simplify → replace → add → remove;
- explicitly allows Ownable to add, remove, simplify, replace, or conceptually redesign animations/interactions when they strengthen identity, hierarchy, explanation, continuity, pacing, feedback, narrative, or an earned signature moment;
- allows proactive creation/specification of motion forms such as animated illustration, image sequences, kinetic type, SVG/canvas motion, 3D motion, state transitions, or scroll-linked storytelling when conceptually justified;
- added the motion placement test: “why this motion, on this element, at this moment?”;
- explicitly rejects animation quotas and generic reveal/preset motion as automatic premium treatment;
- preserves specialist boundaries: Ownable owns motion intent and conceptual fit, while Emil Kowalski skills own timing, easing, springs, gestures, interruptibility, transform origins, reduced-motion behavior, and motion craft;
- keeps Taste and Impeccable authoritative for their broader visual, UX, system, accessibility, and implementation domains.

## 1.3.0 — 2026-09-20

- added active art-direction intervention: on modification tasks, Ownable now audits every major section and visible image/media moment in scope instead of waiting for the user to identify each problem;
- added root-cause diagnosis so structural, sequencing, proof, asset, content, and concept problems are fixed at the level where they actually occur;
- added an asset intervention ladder: keep → reframe → transform → replace with a stronger real asset → generate → remove;
- explicitly allows proactive web sourcing of stronger real imagery when tools permit, with production-use provenance/permission guardrails and verified-real preference for proof-sensitive roles;
- clarified that weak photography and supplied media are not sacred when a stronger truthful replacement exists;
- added structural surgery authority to sort, reorder, regroup, relabel (when copy scope permits), merge, split, replace, or remove navigation items, tabs, sections, and content groups;
- explicitly allows replacing an entire section concept when the structure itself is the problem rather than polishing a weak shell;
- protects required IA, routes/deep links, legal/safety content, SEO/navigation obligations, product semantics, brief-mandated functionality, and refinement-vs-redesign scope;
- requires local interventions to improve the whole experience rather than creating new repetition, imbalance, or visual drift;
- keeps detailed layout/UX execution with Taste/Impeccable and motion/interaction consequences with Emil Kowalski skills when those companions are active.

## 1.2.0 — 2026-09-20

- added content-led composition: content, evidence, imagery, task, and hierarchy shape form instead of being forced into predetermined section shells;
- added concept-led asset commissioning: the supplied asset pack is not the ceiling when a truthful concept genuinely needs a missing visual role;
- expanded identity carriers into distributed identity so brand character survives beyond the hero, logo treatment, or one signature interaction;
- expanded category-cosplay guidance into cultural specificity without cultural costume;
- clarified that cultural cues should come from relevant materials, rituals, language, craft, places, objects, archives, and history rather than token “heritage” styling;
- explicitly defers detailed layout/system execution to Taste or Impeccable when those specialist skills are active;
- explicitly defers asset provenance/verification workflow to Impeccable when active;
- updated the final ownability check to cover distributed identity, cultural specificity, content-to-form fit, and missing-but-earned asset roles.

## 1.1.0 — 2026-09-20

- added bespoke illustrative asset generation as a first-class art-direction capability;
- explicitly supports hand-drawn, painting-like, watercolor/gouache, sketch, etched/engraved, collage, textured editorial, diagrammatic, mixed-media, stylized 3D, and other subject-appropriate generated visuals;
- requires every generated illustration to pass the existing “earn its place,” purpose-first, and “why this? / why here?” tests;
- clarifies that visual style must have a semantic role rather than acting as a generic premium preset;
- distinguishes illustrative/atmospheric imagery from documentary and proof-critical imagery;
- prevents agents from creating filler sections or unnecessary artwork merely to showcase generated assets.

## 1.0.0 — 2026-09-19

Initial public release.

- explicit brief/truth operating guard;
- subject-first art-direction framework;
- evidence-before-aesthetics and constraint-as-authorship principles;
- Creative North Star plus anti-literalization guard;
- identity-carrier framework and ownability / logo-swap test;
- structural economy: every major section/page/screen earns its place while brief-required content is protected;
- purpose-first asset curation: never invent a section merely to use an asset;
- “why this?” + “why here?” semantic image-placement test;
- image uniqueness and perceptual-repetition discipline;
- coherent asset-language and asset-scarcity guidance;
- capability-aware transparent/cutout and asset-transformation guidance;
- truth-sensitive visual-editing rules;
- real-proof-over-decorative-prestige principle;
- sequence/flow, subject-specific signature moments, and cross-output fingerprint checks;
- optional specialist precedence for Taste Skill, Emil Kowalski Skills, and Impeccable.
