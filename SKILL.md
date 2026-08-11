---
name: minecraft-world
description: Reimagine an input photo as a coherent, cinematic scene that could genuinely exist inside a Minecraft-like game world. Use for portraits, animals, objects, architecture, landscapes, and travel photos when Codex should preserve only the source's defining subjects, colors, spatial relationships, and mood while rebuilding the subject, terrain, environment, lighting, and distance as one block-based world—not as a voxel sculpture, pixel filter, toy model, or photoreal scene.
---

# Minecraft World

Use an image-generation or image-editing tool to perform world reconstruction:

`photo → identify key subjects → remove clutter → simplify and recompose → rebuild one coherent Minecraft world`

## Workflow

1. Inspect the source for its 1–3 defining subjects, dominant colors, spatial relationships, viewpoint, and mood.
2. Remove incidental objects and detail. Preserve only cues required for recognition.
3. Recompose the selected content as a place inside a large, navigable game world. Integrate every subject with block terrain, vegetation, architecture, sky, and atmosphere at a consistent world scale.
4. Use large structural block geometry, stepped silhouettes, flat square faces, matte surface-mapped pixel textures, and block-native forms. Represent real curves through clear large-scale shape design, never dense arrays of tiny cubes.
5. Use a moderate or wide environmental camera, directional game lighting, ambient occlusion, and cinematic shader-like atmosphere.
6. Build depth in world space: keep the foreground sharp and textured; simplify and soften the midground; reduce contrast, saturation, texture definition, and detail toward a hazy horizon.
7. Generate and inspect the result. Revise unless it reads as a believable in-game screenshot inspired by the source.

## Non-negotiable checks

- Reconstruct the entire frame in one visual language; never retain a photographic background.
- Keep the main subject sharp; never use bokeh, shallow depth of field, macro framing, or product-photography staging.
- Never create LEGO, toy blocks, tabletop miniatures, MagicaVoxel-style art, glossy cubes, beveled blocks, or objects assembled from hundreds of visible cubelets.
- Treat blocks as structural units of the world, not as pixels for tracing source contours.
- Do not add unrelated focal subjects or text.

Read [references/style-guide.md](references/style-guide.md) before prompting. Read [references/examples.md](references/examples.md) to adapt world reconstruction to the source category or correct style drift.
