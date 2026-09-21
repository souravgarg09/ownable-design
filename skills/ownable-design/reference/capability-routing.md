# Capability routing

Load this reference for active production when the work may require external tools, media generation/editing, sourcing, rendering, or implementation.

Ownable routes by **what needs to be done**, not by which vendor happens to provide the tool.

## 1. Inventory capabilities, not brands

Determine which of these are available in the current environment:

- code/file editing;
- browser or app rendering;
- screenshot/visual inspection;
- web/reference search;
- real-asset retrieval or connected brand libraries;
- image generation;
- image editing, masking, matting, or background removal;
- vector/SVG/diagram creation;
- data visualization;
- animation/motion implementation;
- video generation/editing;
- 3D/spatial generation or rendering;
- audio generation/editing;
- external MCP/connector/plugin tools;
- local tools that can safely produce the required artifact.

Do not assume a capability is unavailable just because one named provider is absent.

## 2. Provider-neutral routing

Translate the art-direction need into a capability request.

Examples:

- transparent product/person cutout → image editing/matting with alpha output;
- authored watercolor memory → image generation in a watercolor medium;
- strong real hero photo with distracting background → image editing rather than regeneration;
- real facility/product/person proof → verified real-asset sourcing, not synthetic generation;
- spatial product/object story → 3D/spatial capability if available, otherwise an honest alternate representation;
- continuity/state-change motion → motion implementation, then specialist motion craft if available;
- visual-quality claim → render/screenshot/visual-inspection capability.

A native image tool, a connected service such as Higgsfield or Pollinations, another MCP/connector, a local image pipeline, or a future provider may fulfill the same image-capability role. Provider names do not change the design rule.

## 3. Select the capability by role and output requirements

When multiple tools can do the job, prefer the one that best satisfies:

1. truth/provenance requirements;
2. required medium and controllability;
3. output quality;
4. required transparency/alpha or file characteristics;
5. consistency with existing assets;
6. iteration/inspection support;
7. user constraints such as allowed services, privacy, time, or cost when known.

Do not choose a familiar tool when another available capability better fits the output.

## 4. Generate versus edit versus source

Use **source** when authenticity/proof is the reason the visual matters.

Use **edit** when the underlying real asset is already right but presentation is weak.

Use **generate** when authored/synthetic media is truthful for the role and a new visual is genuinely needed.

Use **remove/no media** when neither real nor generated media improves the experience.

Do not regenerate a real person/product/place merely because editing is less convenient.

## 5. Image-generation behavior

When generation is justified and available, the agent should actually generate the needed asset instead of stopping at a prompt suggestion.

The generation request should specify the role in the interface, composition, subject, medium, background behavior, crop/aspect needs, and truth boundaries.

Possible media include photographic, watercolor, gouache, pencil, charcoal, ink, engraving, collage, mixed-media, editorial illustration, diagrammatic illustration, texture/material study, and stylized 3D.

Do not generate generic filler to make a page look more visual.

## 6. Image editing and transparency

When the job is cleanup or transformation, prefer editing over replacement.

For cutouts/background removal:
- produce real transparency/alpha when supported;
- preserve fine edges and internal holes;
- do not fake organic contours with circles/polygons/gradient masks;
- do not mistake white, checkerboard, or visually empty pixels for actual transparency;
- inspect the result against the intended light/dark/material background.

If the first available generator cannot output the required alpha, route to another available editing/matting capability rather than silently shipping an opaque approximation.

## 7. Capability fallback

If a preferred capability is unavailable:

1. look for another available tool or connector that provides the same capability;
2. choose an alternate medium that preserves the concept when possible;
3. continue every useful intervention that remains possible;
4. disclose only the materially blocked part.

Do not make the user perform a task manually when another available capability can safely complete it.

## 8. Inspect what the tool actually produced

A successful tool call is not a successful asset.

Inspect generated/edited output for:
- correct subject and semantics;
- crop and composition;
- edge quality;
- actual alpha/transparency when required;
- artifacts, extra objects, malformed anatomy/geometry, text corruption;
- coherence with the chosen visual world;
- truth/proof boundary;
- performance/resolution suitability;
- behavior in the real layout.

Reject, regenerate, edit, or remove weak output.

## 9. Rendering is also a capability

When the environment can run or preview the site/app, use that capability before claiming visual success.

If it cannot render, use the strongest available evidence such as screenshots, design files, or supplied captures and state the verification limitation.

## 10. Portability

Ownable's rules are portable. The loading mechanism is not necessarily universal.

- In Agent Skills-compatible environments, install/load the skill normally.
- In environments with project/system instruction files, include Ownable there.
- In chat products without native skill loading, provide SKILL.md and relevant references as project context/files/instructions.
- In environments with MCPs/connectors/plugins, let those tools satisfy capabilities without changing Ownable's reasoning.

Never write core art-direction logic that requires a specific provider to exist.
