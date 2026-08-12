---
name: minecraft-world
description: Reconstruct an input photo as a coherent, cinematic scene that could genuinely exist inside a Minecraft-like game world. Use for portraits, animals, objects, architecture, landscapes, and travel photos when Codex should preserve recognizable subjects, composition, environment identity, dominant colors, time of day, and mood while rebuilding every layer with block-world geometry, designed block clouds, game lighting, and atmospheric depth—not creating a voxel sculpture, pixel filter, toy model, or photoreal scene.
---

# Minecraft World

Use an image-generation or image-editing tool to perform world reconstruction:

`photo → identify key subjects → remove clutter → simplify and recompose → rebuild one coherent Minecraft world`

## Workflow

1. Inspect the source for its 1–3 defining subjects, spatial relationships, viewpoint, environment identity, dominant colors, time of day, and mood.
2. Remove incidental objects and detail. Preserve only cues required for recognition.
3. Recompose the selected content as a place inside a large, navigable game world. Integrate every subject with block terrain, vegetation, architecture, sky, and atmosphere at a consistent world scale.
4. Use large structural block geometry, stepped silhouettes, flat square faces, matte surface-mapped pixel textures, and block-native forms. Represent real curves through clear large-scale shape design, never dense arrays of tiny cubes.
5. Preserve the source's dominant hue families, lighting direction, season, weather impression, and time of day by default. Apply restrained game-shader grading without changing the scene identity. Make major palette or time changes only when the user requests reinterpretation.
6. Rebuild the sky with flat, stepped, rectangular block-cloud layers. Use clean graphic masses and limited tones; never reproduce realistic cloud anatomy, soft photographic cloud volumes, or naturalistic storm texture.
7. Use a moderate or wide environmental camera, directional game lighting, ambient occlusion, and cinematic shader-like atmosphere.
8. Build depth in world space: keep the foreground sharp and textured; simplify and soften the midground; reduce contrast, saturation, texture definition, and detail toward a hazy horizon.
9. Generate and inspect the result beside the source. Revise unless the subject placement, background, palette, and spatial composition remain clearly recognizable while the rendering reads as an in-game screenshot.

## Non-negotiable checks

- Reconstruct the entire frame in one visual language; never retain a photographic background.
- Never retain realistic clouds. Make every visible cloud explicitly block-built, planar, stepped, and graphic.
- Do not replace the source background, biome, season, time of day, dominant palette, or major terrain/building silhouettes unless requested.
- Keep the main subject sharp; never use bokeh, shallow depth of field, macro framing, or product-photography staging.
- Never create LEGO, toy blocks, tabletop miniatures, MagicaVoxel-style art, glossy cubes, beveled blocks, or objects assembled from hundreds of visible cubelets.
- Treat blocks as structural units of the world, not as pixels for tracing source contours.
- Do not add unrelated focal subjects or text.

Read [references/style-guide.md](references/style-guide.md) before prompting. Read [references/examples.md](references/examples.md) to adapt world reconstruction to the source category or correct style drift.
