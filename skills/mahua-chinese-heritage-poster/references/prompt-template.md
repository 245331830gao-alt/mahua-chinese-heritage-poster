# Image-Generation Prompt Template

Build the final prompt in this order and omit sections that do not apply.

```text
Use case: style-transfer or historical-scene
Asset type: premium vertical Chinese cultural heritage poster

Input image role:
State whether each image is an edit target, identity reference, architecture reference, composition reference, or supporting material reference.

Primary request:
Describe the poster purpose and cultural subject.

Subject fidelity:
List the exact architecture, person, artifact, animal, landscape, pose, object count, proportions, colors, materials, and relationships that must remain recognizable.

Composition:
Choose 裂境, 洞天, 山河建筑卷, or 古建切片. Specify visual axis, subject-to-canvas ratio, negative-space region, eye-leading path, foreground/middle/background, and optional human scale.

Environment:
Describe mountains, cave, desert, river, mist, sky, city, or interior as a physical layer rather than decoration.

Materials and textures:
Specify xuan paper, silk, mineral pigments, mural patina, carved stone, oxidized metal, old wood, dry brush, grain, and restrained imperfections as appropriate.

Color palette:
Name the base neutrals and no more than two accent colors.

Lighting and mood:
Specify museum light, dawn mist, desert glow, moonlit ink, or another restrained directional model.

Typography:
Quote every required string verbatim. Specify hierarchy, placement, spacing, and color. Do not invent dates, official claims, or slogans.

Rendering:
Premium museum exhibition poster, cinematic atmospheric perspective, sophisticated cultural branding, tactile physical materials, coherent structure, refined editorial composition.

Constraints:
Repeat all invariants, exact counts, identity requirements, landmark geometry, and text requirements.

Avoid:
List likely subject-specific failures plus the general negative constraints from the style reference.
```

After generation, inspect subject fidelity, architecture or anatomy, repeated geometry, reflections, text, logos, watermarks, and unintended additions. Correct one failure category per iteration.
