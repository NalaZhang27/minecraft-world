# Style guide

## World construction

- Build expansive, navigable space from large block-based terrain, structures, vegetation, water, and sky.
- Use stepped landforms and silhouettes, flat square faces, and cohesive Minecraft-world scale.
- Convert source subjects into block-native world forms; do not wrap them in cubes or trace their curves with cubelets.
- Reconstruct foreground, ground, environment, and background together. Nothing remains photographic.

## Texture and rendering

- Map low-resolution pixel textures onto broad surfaces instead of exposing every block as a separate shiny cube.
- Use matte materials, restrained texture variation, directional game-engine light, readable cast shadows, and ambient occlusion.
- Use cinematic shader qualities such as warm sun, colored sky light, reflective water, distance haze, or dusk glow to reinterpret the source mood.

## Sky and clouds

- Replace every photographic sky with a designed game sky.
- Build clouds as broad rectangular slabs, stepped horizontal bands, or sparse block clusters with flat undersides and crisp silhouettes.
- Use a limited cloud palette shaped by the lighting: for example cream and peach at sunset, blue-gray in rain, or lavender in dusk.
- Keep cloud edges graphic even when distance haze softens contrast. Never create fluffy, billowing, wispy, turbulent, or photoreal volumetric clouds.

## Color direction

- Preserve the source's dominant hue families, warm/cool relationship, season, weather impression, and time of day unless the user asks for reinterpretation.
- Consolidate the source into 2–4 dominant game-render hues without replacing its background identity or major color fields.
- Use restrained shader grading: clearer light/shadow separation, controlled saturation, cohesive ambient color, and distance-tinted haze.
- Allow major shifts to sky gradient, foliage, water, fog, or time of day only when explicitly requested.

## Atmospheric depth

Make distance legible through the environment, never lens blur:

- **Foreground:** sharp edges, strongest texture definition, contrast, and local detail.
- **Midground:** simpler forms, softer texture definition, lower contrast.
- **Far distance:** broad silhouettes, reduced saturation and contrast, strong haze, gradual merger with sky.

Keep the focal subject sharp. Use a moderate or wide field of view, environmental perspective, an expansive horizon, and enough visible ground or terrain to establish scale.

## Category translation

- **Portraits:** Recast the person as a player-scale character inhabiting a matching block environment; preserve pose, silhouette, clothing colors, and a few identity cues.
- **Animals:** Recast the animal as a world-native creature at believable environmental scale; preserve species, posture, and markings without cubelet sculpting.
- **Objects:** Turn the object into a world-scale landmark, structure, vehicle, resource, or environmental feature while preserving signature form and color.
- **Architecture:** Rebuild the structure from broad block modules and integrate it with terrain, paths, vegetation, and horizon.
- **Landscapes and travel:** Preserve terrain profile, route or water shape, landmark placement, weather impression, mood, and broad warm/cool relationships; redesign the final palette and simplify secondary scenery by distance.

## Reject

Literal pixel conversion; dense visible cubelets; LEGO or toy-block cues; miniature dioramas; tabletop staging; MagicaVoxel-style sculpture; glossy, rounded, or beveled cubes; smooth generic 3D; photoreal backgrounds or clouds; naturalistic cloud volumes; unrequested background replacement or radical recoloring; shallow depth of field; camera bokeh; macro or catalog photography.
