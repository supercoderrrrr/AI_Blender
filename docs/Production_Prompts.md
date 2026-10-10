# Production refinement prompts

Original project instructions, organized for reading. These are prompts, including experiments and corrections; the final choices are explained in [the workflow](Workflow_EN_CN.md). Full conversation transcripts are not included. Local machine paths are replaced with `<local asset path>` where present.

[Prompt index](Prompt_Index_EN_CN.md)

<a id="make-p01"></a>

## MAKE-P01 — Bunker Weathering, Lighting Interaction, and Ring Accent Polish

```text
Proceed to a focused polish pass for the approved hero scene.

PASS NAME:
Bunker Weathering, Lighting Interaction, and Ring Accent Polish

SCENE CONTEXT:
This is the established cinematic environment with the bunker embedded in the left hillside and the giant ring structure in the right background basin. The ring remains the primary visual subject, and the bunker remains the secondary subject. The composition, camera framing, scale relationships, terrain layout, fog mood, path, human figure, lake position, and overall scene structure are already approved and must remain unchanged.

REFERENCE IMAGE ROLES:
- Image A = overall approved camera view and scene composition.
- Image B = close-up reference of the bunker front area that needs better weathering realism and better lighting interaction.
- Image C = close-up reference of the ring, especially the yellow accent panels, the inner illuminated ring, and the center hanging furnace/core area.
- Image D = visual reference for black-yellow hazard stripe treatment.

GOAL:
Improve the bunker’s realism and readability through stronger weathering and better interaction with the scene lighting, and refine selected ring accent details without changing the approved overall design.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the bunker’s overall shape, silhouette, proportions, and placement.
- Keep the ring’s overall structure, silhouette, proportions, and approved attachments.
- Keep the existing atmosphere, fog layering, landscape layout, and the overall cold cinematic mood.
- Keep the ring as the dominant visual focal point and the bunker as the secondary focal point.
- Keep all modifications editable and non-destructive where practical.
- Save the result as a new version file; do not overwrite the last approved version.

CHANGE — BUNKER WEATHERING:
1. Strengthen the bunker’s aged concrete appearance so the weathering reads clearly in the final camera, not just in extreme close-up.
2. The current aging is too faint. Increase the visibility and realism of:
   - vertical rain streaks and water runoff stains,
   - darker water accumulation traces under ledges and edges,
   - subtle mineral streaking and dirt deposits,
   - slightly darker grime concentration near joints, recessed areas, and water flow paths,
   - realistic tonal variation in the concrete surface.
3. Focus especially on the frontal face of the bunker, where the current weathering feels too weak and not fully believable.
4. Make the weathering physically plausible and directional, following gravity, runoff paths, exposed surfaces, and sheltered areas.
5. Avoid generic procedural noise pasted everywhere. The weathering should feel like large-scale concrete aging, not random texture breakup.

CHANGE — BUNKER LIGHTING INTERACTION:
1. The bunker currently reads a bit too dark and somewhat detached from the scene lighting.
2. Improve the bunker’s interaction with the current lighting so the front surfaces read more naturally in the final shot.
3. Introduce better large-form light response across the bunker planes:
   - clearer but subtle value separation between light-facing and shadow-facing planes,
   - improved soft shading transitions,
   - enough illumination to read form and weathering,
   - maintain the moody look, but do not let the bunker flatten into a dark mass.
4. Preserve the cinematic atmosphere. Do not make the bunker bright, glossy, or overly contrasty.
5. The goal is better readability and realism, not a new lighting setup.

CHANGE — RING YELLOW ACCENT PANELS:
1. Inspect the yellow horizontal accent areas/panels on the ring and attached structures.
2. For any yellow panel or strip that has enough length and readable surface area, convert it from solid yellow to a black-yellow hazard stripe treatment inspired by Image D.
3. The stripe treatment should be clean, industrial, and legible from the final camera.
4. Use the hazard stripes selectively and only where the panel size and proportions support it.
5. If a yellow accent area is too short, too small, or would become visually messy, keep it as a solid yellow accent instead of forcing stripes.
6. Do not overuse hazard stripes. They should remain accents, not dominate the ring.

CHANGE — RING CENTER FURNACE / CORE:
1. The hanging center furnace/core should read as hotter than it does now.
2. Push its color temperature toward a richer red / orange-red glow so it suggests higher heat.
3. This hotter coloration should be concentrated in the furnace/core area and any directly related emissive details.
4. Preserve the established warm inner ring lighting, but make the center furnace read as a hotter and more intense focal sub-accent within the ring.
5. Do not turn the whole ring interior red. Keep the red-hot emphasis localized to the center furnace/core.

CHANGE — ADDITIONAL RING LIGHT ACCENTS:
1. Add a small number of subtle extra light accents on other parts of the ring structure.
2. These lights should be sparse, intentional, and believable as industrial indicator lights, maintenance lights, or small functional illumination points.
3. Keep them low-density and visually restrained.
4. They should enrich the realism and mechanical complexity without cluttering the design.
5. Do not create a busy sci-fi light show. The ring must remain elegant, massive, and readable.

DO NOT:
- Do not change the approved composition or camera.
- Do not move the bunker, ring, lake, path, or terrain.
- Do not redesign the bunker or ring.
- Do not add large new structures or change silhouette hierarchy.
- Do not over-brighten the bunker.
- Do not cover the bunker in uniform noise or fake grunge.
- Do not overuse hazard stripes.
- Do not add too many lights or dense emissive patterns on the ring.
- Do not reduce the ring’s dominance in the frame.
- Do not alter the fog mood except as needed for the lighting/material polish to read correctly.

TECHNICAL EXECUTION NOTES:
- Work primarily through material/shader refinement, controlled texture layering, roughness/value variation, and small lighting/material interaction adjustments.
- Keep the result physically plausible and visually grounded.
- Ensure the bunker weathering remains readable in the approved final camera view.
- Ensure any new ring accents are also readable in the final camera, not only in close-up.
- Preserve editability and clean scene organization.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final approved camera render.
2. One closer render focused on the bunker front weathering and lighting interaction.
3. One closer render focused on the ring yellow accent panels / hazard stripe treatment.
4. One closer render focused on the ring center furnace/core and added light accents.
5. A short summary of exactly what was changed, including:
   - bunker weathering improvements,
   - bunker lighting interaction improvements,
   - which yellow accents were converted to hazard stripes and which were intentionally left solid yellow,
   - how the furnace/core color was adjusted,
   - where extra ring lights were added.

STOP FOR REVIEW after producing the updated previews. Do not continue to any new pass until the results are reviewed and approved.
```

<a id="make-p02"></a>

## MAKE-P02 — Bunker Weathering Correction, Inner Ring Furnace Heat, and Fog Redistribution

```text
Proceed to a focused correction and polish pass for the approved hero scene.

PASS NAME:
Bunker Weathering Correction, Inner Ring Furnace Heat, and Fog Redistribution

SCENE CONTEXT:
This is the approved cinematic environment with the bunker embedded in the left hillside and the giant ring structure in the right background basin. The ring remains the primary subject and the bunker remains the secondary subject. The camera, composition, terrain layout, path, human figure, lake position, overall scale relationships, and general lighting mood are already approved and must remain unchanged.

REFERENCE IMAGE ROLES:
- Image A = approved main composition and overall scene.
- Image B = bunker close-up reference, especially the concrete face and sloped surfaces.
- Image C = ring close-up reference, especially the illuminated inner ring, the hanging platform/core, and the yellow accent areas.
- Image D = black-yellow hazard stripe reference.
- Image E = current result, showing partial success: keep the hanging platform’s added red-hot accent, but refine the true target areas described below.

GOAL:
Correct the interpretation of the previous pass. The main heat emphasis should not be limited to the hanging platform only. The illuminated inner ring itself, especially its middle zone around the central hanging assembly, should read more like an active high-temperature furnace region. Also correct the bunker weathering style and improve the fog placement.

KEEP:
- Keep the approved camera and final composition exactly the same.
- Keep the ring as the primary visual focus and the bunker as the secondary focus.
- Keep the bunker’s overall shape, silhouette, and placement.
- Keep the ring’s overall structure, silhouette, scale, and approved attachments.
- Keep the hanging platform’s current added red-hot accent; it is a good addition and should remain.
- Keep the overall cold cinematic mood, foggy basin atmosphere, and large-scale realism.
- Keep all edits non-destructive and editable where practical.
- Save the result as a new version file; do not overwrite the previous approved version.

CHANGE — INNER RING FURNACE HEAT (MAIN CORRECTION):
1. The main target is the illuminated inner ring, not only the hanging platform.
2. The inner illuminated ring already has warm/yellow light. Push the middle portion of this inner ring toward a hotter furnace-like look.
3. Specifically, the inner ring area surrounding and visually framing the central hanging assembly should show a stronger high-temperature character:
   - shift part of the light color from pale warm yellow toward orange-red / red-hot tones,
   - keep the effect concentrated mainly in the central zone of the inner ring,
   - create the feeling that this is the hottest active working region of the ring.
4. The transition should feel physically plausible:
   - central sections = hotter, richer orange-red / red-hot,
   - surrounding sections = still warm, but slightly less hot and closer to the current warm/yellow tone.
5. Do NOT turn the entire inner ring uniformly red.
6. Keep the hanging platform’s current red-hot accent and integrate it as part of the same thermal logic.
7. The result should suggest a functioning industrial furnace / energy-processing zone inside the ring.

CHANGE — BUNKER WEATHERING CORRECTION:
1. Correct the current weathering on the bunker’s sloped face and front concrete surfaces.
2. The existing weathering is too speckled / spotty in places. Reduce random blotchy breakup and small scattered specks.
3. Replace that look with more realistic elongated streak-based weathering:
   - vertical rain streaks,
   - gravity-driven runoff marks,
   - subtle but readable long drips,
   - layered dirt/mineral deposits that flow downward,
   - darker streak concentration beneath edges, joints, recesses, and water collection points.
4. The weathering direction must follow gravity and the actual plane orientation of the bunker faces.
5. On the sloped faces, ensure runoff direction is believable relative to the surface angle; avoid broken fragmented stain patterns.
6. The bunker material should feel more like large-scale aged concrete with streaking, not noisy procedural grunge.
7. In darker zones, corners, recessed edges, and less sun-exposed areas, increase the depth and visibility of these streak-like stains.
8. Keep the effect controlled and realistic. Do not turn the whole bunker into a dirty mess.

CHANGE — BUNKER MATERIAL READABILITY:
1. Improve the realism of the bunker’s concrete material while preserving the current design.
2. Favor broad tonal variation, runoff streaking, subtle surface aging, and structural weathering patterns.
3. Avoid overusing tiny high-frequency detail.
4. Keep the material grounded, heavy, and believable in the final camera view.

CHANGE — HAZARD STRIPES:
1. Keep the current logic for hazard stripes on selected ring yellow accents.
2. Only use black-yellow hazard stripes where the panel length and readability support it.
3. If a panel is too short or too small, keep it solid yellow.
4. Do not expand hazard stripes unnecessarily.

CHANGE — EXTRA RING LIGHTS:
1. Keep the previous idea of a small number of extra light accents on the ring.
2. Maintain them as sparse and restrained industrial light points.
3. Do not increase their number significantly.
4. The ring must remain elegant and readable, not busy.

CHANGE — FOG REDISTRIBUTION:
1. Refine the higher fog layer around the ring.
2. The current upper fog feels too high and not obvious enough.
3. Move this fog layer slightly downward so it sits more around the ring’s mid-to-upper area, especially around the upper half of the structure.
4. Reduce its density slightly compared to a heavy opaque fog bank.
5. Make it uneven and natural:
   - soft drifting patches,
   - subtle layered variation,
   - not a flat uniform band.
6. Preserve the basin fog near the ground, but let the higher fog become a lighter, less uniform atmospheric veil around the ring’s middle and upper region.
7. Do not make the entire scene milkier. This is a placement and shaping adjustment, not a global fog increase.

DO NOT:
- Do not change the approved camera, composition, or focal hierarchy.
- Do not redesign the bunker or ring.
- Do not move the ring, bunker, terrain, lake, path, or figure.
- Do not turn bunker weathering into random speckling or noisy dirt.
- Do not make the bunker excessively bright or glossy.
- Do not turn the whole ring inner light uniformly red.
- Do not remove the hanging platform’s new red-hot accent.
- Do not add too many extra ring lights.
- Do not make the fog uniform or overly dense.
- Do not reduce the readability of the ring silhouette.

TECHNICAL EXECUTION NOTES:
- Prioritize material refinement, controlled texture layering, roughness/value control, emissive color shaping, and fog placement adjustments.
- Evaluate all changes primarily from the approved final camera, and secondarily in closer inspection renders.
- Ensure the bunker weathering remains readable in the main shot.
- Ensure the inner ring’s hotter central furnace region reads clearly in the final camera without overwhelming the rest of the ring.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final approved camera render.
2. A close-up render of the bunker front and sloped concrete faces showing corrected streak-based weathering.
3. A close-up render of the ring inner illuminated band showing the hotter central furnace region.
4. A close-up render of the hanging platform/core area showing how it now integrates with the hotter inner ring.
5. A render highlighting the redistributed mid-upper fog around the ring.
6. A short change summary describing:
   - how bunker weathering was corrected,
   - how random speckling was reduced,
   - how the inner ring central heat zone was changed,
   - how the hanging platform red-hot accent was preserved,
   - how the mid-upper fog was repositioned and reshaped.

STOP FOR REVIEW after producing the updated previews. Do not continue to any new pass until the results are reviewed and approved.
```

<a id="make-p03"></a>

## MAKE-P03 — Background Depth, Distant Mountains, and Sky Atmosphere Enhancement

```text
Proceed to a focused environment background enhancement pass for the approved hero scene.

PASS NAME:
Background Depth, Distant Mountains, and Sky Atmosphere Enhancement

SCENE CONTEXT:
This is the approved cinematic environment with the bunker embedded in the left hillside and the giant ring structure in the right background basin. The ring remains the primary visual subject and the bunker remains the secondary subject. The composition, camera framing, scale relationships, terrain layout, path, human figure, lake position, and the major foreground/midground structures are already approved and must remain unchanged.

REFERENCE IMAGE ROLES:
- Image A = current approved working render (current scene state).
- Image B = background / atmosphere reference image showing the desired sense of distant mountains, sky clarity, and large-scale environmental depth.

GOAL:
Improve the background world-building and environmental depth so the scene feels more complete and more aligned with the reference image, without redesigning the main scene. Focus specifically on distant mountains, sky quality, and layered atmospheric depth.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the main visual subject and the bunker as the secondary subject.
- Keep the bunker, ring, path, figure, lake, and terrain layout unchanged.
- Keep the overall cinematic realism and large-scale mood.
- Keep the current scene identity; this is a background enhancement pass, not a redesign pass.
- Keep all edits non-destructive and editable where practical.
- Save the result as a new version file; do not overwrite the last approved version.

CHANGE — DISTANT MOUNTAINS:
1. Add a believable far-background mountain range along the distant horizon.
2. The mountain range should feel natural, large-scale, and geographically grounded.
3. These mountains should remain background elements only:
   - low contrast,
   - desaturated,
   - softened by atmospheric perspective,
   - readable but not dominant.
4. Their purpose is to complete the world space and add depth, not to compete with the ring or bunker.
5. The far mountains may include subtle snowy or lighter-toned distant peaks if appropriate, but keep them understated and far away.
6. Ensure the silhouette rhythm is interesting but restrained.

CHANGE — SKY:
1. Improve the sky so it has more depth and realism.
2. Replace the current relatively flat grey-blue background feeling with a clearer, more dimensional sky treatment.
3. Introduce a more natural sky gradient:
   - richer and slightly deeper blue higher in the sky,
   - lighter and softer toward the horizon.
4. Add a small amount of subtle high-altitude cloud structure if needed:
   - thin wispy clouds,
   - sparse streaks,
   - light and elegant, not dramatic.
5. The sky should feel expansive and cinematic, but still restrained and believable.

CHANGE — ATMOSPHERIC DEPTH / BACKGROUND HAZE:
1. Improve the atmospheric layering between foreground, midground, ring basin, and far background.
2. Use atmospheric perspective to better separate:
   - foreground terrain,
   - middle-distance basin,
   - ring zone,
   - far horizon,
   - distant mountain range.
3. Keep the basin fog and existing mood, but shape the haze so it supports spatial depth more clearly.
4. The distant mountains should sit naturally behind a soft layer of atmospheric haze.
5. Add a subtle mid-to-upper atmospheric veil around the ring region if needed, but keep it soft and non-uniform.
6. Avoid a uniform blanket of fog. The atmosphere should feel layered and natural.

CHANGE — BACKGROUND WORLD COMPLETENESS:
1. Improve the sense that the scene exists in a larger world beyond the main subjects.
2. Refine the distant horizon and far landscape transitions so the background no longer feels empty.
3. Ensure the background remains visually quiet and secondary to the ring and bunker.

LIGHTING / MOOD GUIDANCE:
1. Do not redesign the whole lighting setup in this pass.
2. However, allow small adjustments to sky brightness, background haze, and atmospheric clarity if needed so the background reads more like a real large-scale environment.
3. The goal is a cleaner, more open, and more spatially convincing background, not a radical lighting change.
4. Preserve the cinematic mood and the approved focal hierarchy.

DO NOT:
- Do not change the approved composition or camera.
- Do not move or redesign the bunker or ring.
- Do not alter the path, figure, stream, or lake layout.
- Do not introduce dramatic storm clouds or overly stylized skies.
- Do not make the distant mountains too dark, too sharp, or too contrasty.
- Do not allow the background to steal focus from the ring.
- Do not turn the scene into a completely different time of day.
- Do not globally increase fog density in a uniform way.

TECHNICAL EXECUTION NOTES:
- Prioritize world-building through background geometry, matte/background treatment, atmospheric perspective, and sky refinement.
- Evaluate all changes primarily from the approved final camera.
- The background must feel more complete, more believable, and more spacious, while remaining subordinate to the hero subjects.
- Preserve clean scene organization and editability.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One render focused on the sky and distant horizon.
3. One render showing the ring against the new background atmosphere.
4. A short summary explaining:
   - how the distant mountain range was added/refined,
   - how the sky was improved,
   - how atmospheric depth was adjusted,
   - how focus was kept on the ring and bunker.

STOP FOR REVIEW after producing the updated previews. Do not continue to any new pass until reviewed and approved.
```

<a id="make-p04"></a>

## MAKE-P04 — Distant Mountain Separation and Atmospheric Perspective Refinement

```text
Proceed to a focused refinement pass for the far background mountains.

PASS NAME:
Distant Mountain Separation and Atmospheric Perspective Refinement

SCENE CONTEXT:
This is the approved cinematic scene with the bunker on the left and the giant ring in the right background basin. A previous pass added distant mountain layers and improved the sky. The current issue is that the distant mountains still read too close. They need to feel much farther away and more integrated into the atmospheric depth of the world.

GOAL:
Refine the newly added far mountains so they read as true distant background mountains rather than mid-distance terrain. The result should create a stronger sense of large-scale depth and a more convincing far horizon.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary subject and the bunker as the secondary subject.
- Keep the ring, bunker, path, figure, lake, stream, and foreground/midground terrain unchanged.
- Keep the recently improved sky direction and overall background concept.
- Keep the mountains as a subtle background layer only.
- Save the result as a new version file; do not overwrite v089.

CHANGE — MAKE THE MOUNTAINS FEEL FARTHER AWAY:
1. Refine the distant mountains so they appear significantly farther away.
2. Reduce their visual weight by adjusting:
   - contrast,
   - saturation,
   - clarity,
   - edge sharpness.
3. Shift them toward a lighter, cooler, more atmospheric grey-blue tone so they sit closer to the sky color.
4. Avoid making them look like solid dark mountain silhouettes.

CHANGE — ATMOSPHERIC PERSPECTIVE:
1. Strengthen atmospheric perspective on the far mountain layers.
2. The farther the mountain layer is, the lighter, softer, and less contrasty it should become.
3. The mountain bases should fade gently into haze rather than reading as sharply grounded terrain.
4. Use soft atmospheric separation so the far horizon feels expansive and believable.

CHANGE — MOUNTAIN LAYERING:
1. Build a more convincing layered mountain read using 2 to 4 subtle background layers if needed.
2. The nearest of these far layers may be slightly more visible, while the farthest layers should be more washed out and faint.
3. Keep the layering understated and elegant.
4. The mountain silhouettes should be broad and low-frequency, not busy or highly detailed.

CHANGE — SILHOUETTE AND SCALE FEEL:
1. Refine the mountain skyline so it feels like a very distant range rather than nearby rugged hills.
2. Avoid sharp, aggressive peaks or highly readable local detail unless very subdued.
3. If needed, slightly reduce the apparent scale or prominence of the current mountains so they sit farther back in the scene.

CHANGE — HORIZON INTEGRATION:
1. Improve the transition between the basin, distant haze, and the far mountain range.
2. Make the horizon feel deep and continuous, not like a hard cutout.
3. Keep the mountains clearly behind the ring’s atmospheric envelope.

DO NOT:
- Do not change the camera.
- Do not redesign or move the bunker or ring.
- Do not add dramatic or dark mountain forms that compete with the ring.
- Do not increase background contrast.
- Do not make the mountains too sharp or too detailed.
- Do not create a hard silhouette line at the mountain bases.
- Do not let the mountains pull attention away from the main subjects.

TECHNICAL EXECUTION NOTES:
- Prioritize atmospheric perspective, haze integration, tonal compression, and subtle silhouette control over adding more detail.
- The correct result should read as “far away world depth,” not as a new landscape hero element.
- Evaluate primarily from the approved final camera.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. A background-focused render showing the distant mountain layers and horizon treatment.
3. A short summary explaining:
   - how the mountains were pushed farther visually,
   - how atmospheric perspective was strengthened,
   - how the horizon integration was improved.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p05"></a>

## MAKE-P05 — Cinematic Directional Lighting and Scene Integration

```text
Proceed to a controlled cinematic lighting refinement pass.

PASS NAME:
Cinematic Directional Lighting and Scene Integration

CURRENT STATE:
The distant mountains and sky have recently been refined. The scene composition, bunker, giant ring, terrain, vegetation, stream, and atmospheric layout are established.

The remaining issue is that the overall scene lighting still feels somewhat flat and overcast. The bunker, ring, and landscape need stronger but natural light interaction.

PRIMARY GOAL:
Improve the cinematic readability of the entire scene through controlled directional sunlight, realistic sky illumination, and better light-shadow separation.

Do not redesign the scene.

KEEP:
- Approved camera and composition.
- Existing geometry and all object positions.
- Current distant mountains and sky structure.
- Existing materials and weathering patterns.
- Ring backlighting concept.
- Current fog layers and overall atmosphere.
- Existing warm ring illumination and bunker entrance lights.

CHANGE:

1. SUNLIGHT DIRECTION
- Establish a more readable directional sunlight component.
- Introduce a subtle warm-versus-cool lighting relationship.
- Keep the ring backlit or partially backlit.
- Do not turn the scene into harsh midday sunlight.
- Preserve the established cinematic mood.

2. BUNKER LIGHTING
- Improve light interaction with the bunker’s large concrete planes.
- Create clearer separation between illuminated and shadowed faces.
- Use natural grazing light where appropriate to reveal concrete weathering.
- Keep recessed entrance areas suitably dark.
- Avoid excessive fill lighting and artificial-looking illumination.

3. RING LIGHTING
- Maintain the ring as the primary visual subject.
- Improve subtle rim lighting and structural depth.
- Preserve readable mechanical details on the front-facing surfaces.
- Do not overexpose the illuminated inner ring.
- Do not change the ring’s existing emissive colors.

4. LANDSCAPE LIGHTING
- Improve natural light variation across the grassland and terrain.
- Introduce better ground-plane depth through directional illumination.
- Preserve current vegetation geometry and materials.
- Avoid making the entire foreground uniformly brighter.

5. ATMOSPHERIC INTEGRATION
- Ensure sunlight interacts naturally with the existing haze and fog.
- Keep atmospheric perspective and distant mountain separation intact.
- Avoid excessive volumetric beams or dense global haze.
- Preserve the ring silhouette and its lower support readability.

TECHNICAL RESTRICTIONS:
- Do not change the approved camera.
- Do not alter object geometry, scale, or placement.
- Do not rebuild the landscape.
- Do not add decorative light sources unrelated to the environment.
- Avoid destructive changes to existing World and lighting nodes.
- Inspect the existing lighting configuration before editing.
- Save all changes to a new version.

PREVIEW REQUIREMENTS:
Create two subtle lighting variations:

Variation A:
Conservative cinematic lighting.
Preserve most of the current cold, atmospheric appearance while improving directional light readability.

Variation B:
Slightly stronger directional sunlight.
Introduce more pronounced warm highlights and cooler shadows without changing the scene's time-of-day identity.

Render both variations from the exact approved camera with identical exposure and color-management settings.

OUTPUT:
1. Full-scene render of Variation A.
2. Full-scene render of Variation B.
3. A brief explanation of light direction, intensity, sky illumination, and atmospheric adjustments.
4. A comparison with the previous approved version.

Do not finalize either variation automatically.

STOP FOR HUMAN REVIEW.
```

<a id="make-p06"></a>

## MAKE-P06 — Moody Overcast with Selective Sunlight Fusion

```text
Proceed to a focused lighting mood refinement pass.

PASS NAME:
Moody Overcast with Selective Sunlight Fusion

SCENE CONTEXT:
This is the approved cinematic environment with the bunker embedded in the left hillside and the giant ring structure in the right background basin. The ring remains the primary visual subject and the bunker remains the secondary subject. The composition, camera, terrain layout, ring placement, bunker placement, path, figure, stream, lake, distant mountains, and current environment structure are already approved.

We want to explore a lighting mood that blends two qualities:
1. a moody, cool, slightly overcast atmosphere,
2. but with real luminous presence and selective brighter light, so the image does not become too dark or flat.

The target is not a fully dark storm scene, and not a fully bright golden-sun scene. It should feel restrained, cinematic, atmospheric, and believable.

REFERENCE IMAGE ROLES:
- Image A = current approved working render of the scene.
- Image B = mood reference for darker, cooler, moody overcast atmosphere.
- Image C = mood reference for luminous warm light, atmospheric glow, and selective brighter illumination.

PRIMARY GOAL:
Create a balanced lighting mood that feels slightly somber and cool overall, but still contains controlled brighter light and atmospheric illumination. The result should preserve mood while improving visual drama and readability.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary subject and the bunker as the secondary subject.
- Keep all approved geometry, object positions, and scale relationships unchanged.
- Keep the current distant mountains and general environmental layout.
- Keep the current ring emissive logic and bunker entrance lights.
- Keep the overall realistic cinematic tone.
- Save the result as a new version file; do not overwrite the previous approved version.

CHANGE — OVERALL LIGHTING MOOD:
1. Shift the scene toward a moodier overcast atmosphere, but do not make it as dark as the darker reference.
2. Preserve a cool environmental base, with slightly subdued sky illumination.
3. Introduce selective brighter light so the image still feels alive, readable, and cinematic.
4. The scene should feel like a cloudy day with partial sunlight breaking through thinner cloud cover or a soft opening in the clouds.

CHANGE — DIRECTIONAL LIGHT:
1. Add or refine a controlled directional sunlight component.
2. This light should be soft but clearly directional.
3. It should not look like harsh midday sun.
4. It should feel filtered by atmosphere and cloud cover.
5. Use it to create better visual hierarchy and shape on major forms.

CHANGE — BUNKER LIGHTING:
1. Let the bunker receive some controlled brighter light on selected large planes so its monumental form reads more clearly.
2. Maintain the bunker’s heavy, austere mood.
3. Do not fully flood the bunker with light.
4. Preserve darker recessed regions, especially the entrance cavity.
5. Aim for a believable interaction between cool ambient light and slightly warmer selective sunlight.

CHANGE — RING LIGHTING:
1. Keep the ring as the visual hero.
2. Allow selective brighter light to catch parts of the ring, especially its upper or outward-facing structure where appropriate.
3. Preserve the current emissive inner ring and center heat accents.
4. Avoid flattening the ring by over-brightening all front-facing surfaces.
5. Use light and atmosphere to enhance silhouette readability and scale.

CHANGE — LANDSCAPE AND GRASSLAND LIGHTING:
1. Introduce more natural light variation across the ground plane.
2. Allow some areas of the grassland and basin floor to catch a little more light, while other areas remain more subdued.
3. Keep the landscape grounded and realistic.
4. Do not make the whole foreground uniformly brighter.

CHANGE — SKY AND ATMOSPHERE:
1. Adjust the sky toward a more moody overcast structure while keeping it believable and readable.
2. Preserve a soft sky gradient and subtle cloud structure.
3. Allow the atmosphere and haze to interact with the brighter light.
4. Some fog and haze can catch light softly, but avoid dramatic god rays or exaggerated volumetric beams.
5. Keep the atmosphere layered and non-uniform.

COLOR AND VALUE RELATIONSHIP:
1. Keep shadows and ambient areas cool.
2. Allow brighter lit areas to become slightly warmer, but only subtly.
3. Avoid strong orange/gold dominance.
4. The final palette should remain restrained, elegant, and cinematic.

DO NOT:
- Do not change the approved camera or composition.
- Do not redesign the scene.
- Do not move the ring, bunker, mountains, terrain, or water.
- Do not make the scene as dark as the darkest mood reference.
- Do not make the scene into a bright golden-hour image.
- Do not create extreme god rays or theatrical lighting.
- Do not overexpose the sky or ring emissive areas.
- Do not remove the cold atmospheric character of the environment.

TECHNICAL EXECUTION NOTES:
- Prioritize lighting, sky, atmosphere, and exposure relationships rather than geometry changes.
- Preserve editability and clean scene organization.
- Evaluate primarily from the approved final camera.
- The correct result should feel like a restrained blend of moody overcast atmosphere and controlled luminous light.

PREVIEW REQUIREMENTS:
Create two lighting variations:

Variation A:
More restrained and moodier.
Cool overcast base with subtle selective light.

Variation B:
Slightly more luminous.
Still moody overall, but with a somewhat stronger selective bright light and clearer warm-cool contrast.

Render both variations from the exact approved final camera.

OUTPUT:
1. Final camera render for Variation A.
2. Final camera render for Variation B.
3. A short summary describing:
   - sky and atmosphere adjustments,
   - directional light adjustments,
   - bunker lighting behavior,
   - ring lighting behavior,
   - which variation is darker and which is more luminous.

STOP FOR REVIEW.
Do not continue to another pass until the lighting direction is reviewed and approved.
```

Additional original instruction / concept note:

```text
电影感超写实科幻环境概念图，广角构图，巨大机械圆环装置位于画面右侧远处低地盆地中，左侧是嵌入山体的粗野主义混凝土地堡，前景有一条通向远方的小路和一个很小的人物作为尺度参照，右下前景有一条浅浅的小溪流过草地。整体构图保持稳定，圆环是第一视觉主体，地堡是第二主体。

画面气氛是冷调、略阴天、克制而肃穆的电影化光影，不要纯黑暗暴风雨，也不要晴朗金色日落。天空大部分被厚重冷灰色云层覆盖，但在圆环的右后上方有一个明显的破云亮口，阳光从这个位置穿透云层，沿着“右后上 -> 左前下”的方向照向圆环前方区域。这个光源方向必须统一、明确、真实。

圆环上缘、右上外缘和部分前侧结构被这束破云光挑亮，形成清晰但克制的受光层次；圆环内圈保留暖色发光结构，中心吊台下方保留轻微红热感。圆环底部前方保留一束穿过雾气的可见光束，这束光是一个局部亮点，雾中可见，氛围感强，但不要过度夸张成舞台灯光。

地堡整体仍然较暗、冷峻、沉稳，只接受较弱的次级散射光和环境补光，不要比圆环更亮；地堡入口内部保留暖色线性灯光，入口凹陷区域保持较深阴影。远处有淡化的远山和低对比背景山脉，山体要远、浅、被大气透视削弱，不要抢主体。

前景草地偏干黄和深橄榄色，略带湿润感；小溪和地面局部有潮湿反射；盆地和圆环周围有贴地薄雾和低空雾，雾要分层、不均匀，并且能够接住从右后上方射来的光线。整体色彩关系是冷灰蓝环境 + 克制的暖光点缀，电影感，真实感，巨构尺度感，史诗感，超写实，细节丰富，空气透视明显。
```

Additional original instruction / concept note:

```text
不要纯黑暴风雨，不要全画面过暗，不要金色夕阳，不要正午强光，不要多个互相冲突的光源方向，不要夸张神圣光，不要过强上帝光，不要高饱和度，不要卡通感，不要低清晰度，不要画面发灰发糊，不要让地堡比圆环更亮，不要把远山做得太近，不要让雾均匀铺满整个画面，不要让圆环底部光束消失。
```

<a id="make-p07"></a>

## MAKE-P07 — Physically Coherent Overcast Lighting, Volumetric Beam Repair, and Scene Readability

```text
Proceed to a corrective cinematic lighting and atmospheric realism pass.

PASS NAME:
Physically Coherent Overcast Lighting, Volumetric Beam Repair, and Scene Readability

SCENE CONTEXT:
The current Blender scene is an approved cinematic environment featuring a massive mechanical ring in a distant right-side basin, a brutalist concrete bunker embedded in the left hillside, a foreground path and figure, a shallow stream, and distant mountains.

The previous lighting pass introduced a dark overcast sky, a cloud break near the ring, and stronger volumetric beams. However, the result looks somewhat artificial. The scene is now too dark in important areas, the beams appear as repeated stage spotlights, and the lighting relationships are not sufficiently physically coherent.

REFERENCE ROLES:
Image A = the latest actual Blender render, showing the problems to correct.
Image B = the previously generated cinematic lighting reference, for target mood only.
Image C, if provided = the earlier close-up showing the subtle lower-ring fog beam we liked.

Do NOT copy Image B's geometry, mountains, terrain, clouds, or light shafts literally. Preserve the real Blender scene.

PRIMARY GOAL:
Achieve a believable, slightly dark, cool overcast environment with one coherent sun break behind and above the ring toward camera-right, selective natural illumination, readable shadow detail, and a restrained localized fog-light effect near the ring base.

The desired look is cinematic but photographic, not theatrical or stylized.

PHASE 0 — INSPECT BEFORE EDITING:
1. Inspect the existing Sun lights, supplementary lights, World shader, cloud/sky setup, volumetric fog objects/materials, compositor, color management, and render settings.
2. Identify the source of the repeated diagonal beams beneath the ring. Determine whether they come from multiple lights, shadow patterns, volumetric geometry, or another cause.
3. Identify why the bunker and foreground are under-illuminated.
4. Identify why the foreground stream has extremely bright, noisy specular highlights.
5. Preserve the existing scene and make reversible changes.
6. Do not assume any object names, shader node names, or current settings. Inspect the actual scene.

PHASE 1 — UNIFY SKY AND SUN DIRECTION:
1. Establish one dominant directional sunlight source.
2. The intended position is behind the ring, elevated, and toward camera-right.
3. From the approved camera, the visible cloud opening should appear above and to the right of the ring.
4. Determine the actual 3D sunlight direction from the scene and camera transforms rather than assuming world-axis coordinates.
5. Align the cloud opening, ring highlights, cast shadows, and volumetric scattering with this single physical direction.
6. Keep the majority of the sky overcast, cold, and slightly dark.
7. Shape the clouds into believable broad masses with varying thickness, not uniform high-frequency procedural noise.
8. The opening should be luminous with soft transitions through thinner cloud layers, not an overexposed white patch.

PHASE 2 — REPAIR VOLUMETRIC LIGHT BEAMS:
1. Remove or disable the artificial appearance of the repeated, evenly spaced diagonal shafts beneath the ring.
2. Do not use a row of parallel spotlights to imitate sunlight.
3. Rebuild the atmospheric light effect using the established key light direction and physically plausible volumetric scattering.
4. Preserve a localized luminous fog effect near and beneath the ring. This is an approved visual feature.
5. Prefer one broad, softly differentiated light region with limited irregular substructure over many identical beams.
6. Let the rays have variable visibility, soft boundaries, and gradual falloff.
7. Ensure that any visible shafts can be traced back to a plausible source and are consistent with scene occlusion.
8. If the original lower-ring accent is produced by a separate functional light, preserve that local source while making its scattering restrained and physically distinguishable from sunlight.
9. Avoid theatrical god rays, hard-edged light cones, and artificially uniform shafts.

PHASE 3 — RESTORE BUNKER READABILITY:
1. The bunker has become too dark and visually flat.
2. Improve its readability without introducing an opposing artificial key light.
3. Adjust sky ambient illumination, indirect bounce, and physically justified atmospheric fill as needed.
4. Restore subtle value separation between the major concrete planes.
5. Preserve readable weathering on the front and sloped surfaces.
6. Keep the recessed entrance naturally dark and preserve the existing warm strip lights.
7. Do not turn the bunker into a brightly illuminated focal subject.
8. The bunker should remain secondary to the ring, but not disappear into the shadows.

PHASE 4 — RING LIGHTING AND FOG:
1. Keep the ring as the primary subject.
2. Preserve the warm inner-ring emission, existing industrial accents, hazard stripes, and hanging platform red-hot detail.
3. Improve subtle highlight and shadow relationships across the ring's upper and outer structure.
4. Do not artificially brighten the entire camera-facing ring surface when the main sun is positioned behind it.
5. Use plausible cool skylight and indirect illumination to retain mechanical readability.
6. Break up the overly uniform fog wall near the ring base.
7. Preserve low-lying basin fog while introducing controlled spatial variation and height-dependent falloff.
8. Allow selected portions of the lower supports and base to remain visible through the fog.
9. Preserve the distant mountains' atmospheric separation.

PHASE 5 — FOREGROUND LIGHT AND WATER REFLECTION CORRECTION:
1. Remove the impression of an isolated, unnaturally warm light pool across the foreground grassland.
2. Ensure landscape illumination follows the same key-light direction.
3. Preserve the established dry-yellow and olive grass materials and geometry.
4. Investigate the extremely bright, sparkling foreground stream.
5. Correct overbright or noisy reflections through physically plausible lighting, shader roughness/normal response, and appropriate render sampling or denoising.
6. Preserve realistic water reflections; do not make the water uniformly matte or artificially dark.
7. Do not remodel the stream or banks during this lighting pass.

PHASE 6 — FINAL COLOR AND EXPOSURE:
1. Preserve a cool grey-blue overcast atmosphere.
2. Keep slightly warmer sunlight and warm industrial emissive accents.
3. Maintain readable detail in both bright and dark regions.
4. Avoid crushed black shadows and clipped white highlights.
5. Do not solve the scene by simply raising global exposure or adding excessive contrast.
6. Maintain the same color-management settings between comparison renders.

STRICT KEEP:
- Approved camera and focal length
- Composition and focal hierarchy
- Ring, bunker, support structures, and all geometry
- Path, human figure, stream, lake, terrain, and vegetation positions
- Distant mountains and horizon design
- Existing bunker weathering and main materials
- Warm architectural lights and ring emission
- Overall cold cinematic identity

STRICT DO NOT:
- Do not move or redesign hero assets.
- Do not introduce competing sunlight directions.
- Do not add repeated fake god-ray spotlights.
- Do not darken the entire scene just to create mood.
- Do not introduce a second sun to brighten the bunker.
- Do not erase the localized lower-ring fog-light accent.
- Do not rebuild vegetation, water geometry, or terrain.
- Do not copy background geometry from the reference image.
- Do not overwrite any approved Blender version.

PREVIEW VARIATIONS:
Produce two controlled alternatives from the same camera.

Variation A — Natural Overcast:
Physically restrained, softer light shafts, greater diffuse sky fill, good structural readability, atmospheric but realistic.

Variation B — Cinematic Overcast:
Same physical sun direction and cloud opening, slightly stronger localized light and volumetric contrast, while avoiding theatrical beams.

Do not make the two versions differ primarily through global exposure. Explore actual lighting and atmospheric differences.

RENDER AND REVIEW:
1. Save reversible scene states for both variations.
2. Render both from the exact approved final camera.
3. Use consistent exposure, view transform, and comparable render settings.
4. Provide a close-up of the lower ring and repaired volumetric lighting.
5. Provide a close-up of the bunker to verify shadow detail.
6. Provide a close-up of the stream to verify controlled specular highlights.
7. Report the key-light direction, changed World settings, fog changes, lighting changes, and water-reflection adjustments.
8. Explain which original lights or volumetric effects caused the artificial repeated beams.
9. Save a new version; preserve previous working files.

STOP FOR HUMAN REVIEW.
Do not automatically approve either variation or proceed to other passes.
```

<a id="make-p08"></a>

## MAKE-P08 — Stream Realism and Bunker Concrete Weathering Correction

```text
Proceed to a focused realism refinement pass for the approved daytime version of the hero scene.

PASS NAME:
Stream Realism and Bunker Concrete Weathering Correction

SCENE CONTEXT:
This is the approved daytime version of the cinematic environment. The ring remains the primary visual subject, and the bunker remains the secondary subject. The brighter daytime atmosphere, current composition, camera framing, terrain layout, distant mountains, stream placement, ring placement, bunker placement, path, and human figure are already approved and must remain unchanged.

IMPORTANT:
Do not shift the scene toward the darker stormy lighting direction explored previously. Keep the current daytime atmosphere and overall lighting character. This pass is not about changing the global mood. It is about improving local realism in the stream/riverbank area and the bunker concrete material/weathering.

REFERENCE IMAGE ROLES:
- Image A = current approved daytime working render.
- If available, Image B = close-up of the stream / riverbank area.
- If available, Image C = close-up of the bunker front concrete faces.

PRIMARY GOAL:
Improve two major realism issues:
1. the stream and riverbank integration,
2. the bunker concrete material and weathering, especially on the front sloped face.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the current daytime atmosphere and lighting direction.
- Keep the ring as the primary focal point and the bunker as the secondary focal point.
- Keep the stream path and overall terrain layout.
- Keep the bunker’s overall geometry, silhouette, and placement.
- Keep the ring, path, human figure, distant mountains, and vegetation layout broadly intact.
- Save the result as a new version file. Do not overwrite the previous approved version.

SECTION A — STREAM / RIVERBANK REALISM

GOAL:
Make the stream feel physically integrated into the ground instead of looking like a simple material strip placed in a trench.

CHANGE — STREAM GEOMETRY AND BANK SHAPE:
1. Refine the stream banks so they feel more natural and eroded.
2. Avoid overly smooth, clean, evenly cut edges.
3. Introduce subtle irregularity to the bank profile:
   - small erosion notches,
   - softened collapses,
   - uneven curvature,
   - slightly varied slope angles.
4. Preserve the overall stream layout and width logic, but improve local realism.

CHANGE — BANK MATERIAL TRANSITIONS:
1. Create a more believable transition between water, wet bank, and dry terrain.
2. Add a darker damp soil / wet mud zone near the water edge.
3. This wet zone should transition gradually into drier ground and grassland.
4. Avoid sharp material borders between water and land.
5. Improve roughness, value, and color variation near the shoreline so it feels naturally wet.

CHANGE — ROCKS AND EMBEDDED CONTACT:
1. Add or refine a small number of rocks and stones along the stream edge and in shallow water where useful.
2. These rocks should feel partially embedded into the soil or riverbed, not simply placed on top.
3. Add believable contact:
   - partial burial,
   - damp darkening near water,
   - wet-line variation,
   - small sediment buildup where appropriate.
4. Avoid overpopulating the stream with rocks.

CHANGE — VEGETATION ALONG WATER:
1. Introduce modest local vegetation variation near the stream.
2. Allow some grass clumps or small waterside plants to approach or slightly overlap the banks.
3. Keep it natural and restrained.
4. Do not turn the stream into a lush green river corridor. This should remain consistent with the current overall environment.
5. The purpose is to soften the artificial edge and improve ecological realism.

CHANGE — WATER SURFACE / SHALLOW WATER READ:
1. Improve the stream water so it feels shallow, grounded, and physically integrated.
2. Preserve the current overall calm character, but make the water read more naturally through:
   - subtle depth variation,
   - better shoreline contact,
   - controlled reflectivity,
   - more believable shallow-water behavior.
3. Avoid mirror-like or over-bright highlights.
4. Ensure the water is not just a flat ribbon of grey material.

SECTION B — BUNKER CONCRETE AND WEATHERING CORRECTION

GOAL:
Correct the bunker concrete so it feels like monumental weathered concrete rather than stylized procedural streaking.

CHANGE — BASE CONCRETE MATERIAL:
1. Improve the concrete material itself before adding more dirt or streaks.
2. The bunker should read as heavy, cast, weathered concrete.
3. Introduce subtle large-scale tonal variation and restrained material richness.
4. The surface should not feel flat, plastic, or overly procedural.
5. Keep it realistic and grounded.

CHANGE — REMOVE UNNATURAL STREAK LOGIC:
1. The current weathering on the bunker, especially the front sloped faces, feels too artificial and too streak-driven in the wrong way.
2. Reduce the unnatural long, dark, overly strong vertical or near-vertical striping.
3. Remove or soften any streaks that:
   - are too long,
   - too dark,
   - too uniform,
   - too repetitive,
   - or do not follow believable runoff logic.
4. The front sloped face is a priority area for correction.

CHANGE — REBUILD WEATHERING WITH REALISTIC LOGIC:
1. Rebuild the weathering using more believable concrete aging logic.
2. Focus on:
   - gravity-driven runoff marks,
   - subtle rain staining,
   - dirt accumulation near edges, joints, recesses, and transitions,
   - slightly darker aging in protected corners and damp-prone areas,
   - soft surface variation rather than graphic stripe patterns.
3. The weathering should feel like real long-term exposure, not decorative streaks.
4. Keep the effect readable, but restrained.

CHANGE — SLOPED FRONT FACE:
1. The large front sloped concrete face needs special attention.
2. It currently lacks convincing concrete realism and the current streak pattern feels wrong.
3. Make this face feel more like:
   - massive poured concrete,
   - aged by rain and time,
   - subtly stained,
   - slightly varied in tone,
   - with believable runoff patterns that respect the face orientation.
4. Avoid dramatic dark striping or obviously fake procedural lines.

CHANGE — WEATHERING DISTRIBUTION:
1. Increase realism by varying where aging is stronger or weaker.
2. Some zones should be cleaner, some more worn, especially:
   - under edges,
   - around joints,
   - in creases,
   - near darker sheltered recesses.
3. Avoid making every concrete plane weathered in the same way.
4. The result should feel more nuanced and less synthetic.

DO NOT:
- Do not change the approved camera or composition.
- Do not alter the daytime atmosphere into a stormy or moody overcast scene.
- Do not redesign the ring or bunker.
- Do not move the stream path significantly.
- Do not overfill the stream with rocks or plants.
- Do not make the stream too lush, too green, or too busy.
- Do not cover the bunker in heavy dramatic grime.
- Do not use exaggerated long dark streaks as the main weathering language.
- Do not make the concrete surface noisy or overly high-frequency.
- Do not let the bunker become visually more dominant than the ring.

TECHNICAL EXECUTION NOTES:
- For the stream, prioritize a combined solution using local geometry refinement, material transition improvements, selective rock placement, and restrained vegetation integration.
- For the bunker, prioritize material realism, large-scale concrete behavior, and physically believable weathering logic.
- Avoid solving either problem with a single texture swap alone.
- Preserve editability and clean scene organization.
- Evaluate primarily from the approved final camera, but use local inspection views if necessary to correct realism.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One closer render focused on the stream and its bank integration.
3. One closer render focused on the bunker front faces and concrete weathering.
4. A short summary explaining:
   - how the stream banks were improved,
   - what was done with wet transitions, rocks, and vegetation,
   - how the bunker concrete was corrected,
   - which unrealistic streaks were removed or reduced,
   - how the sloped front face was improved.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p09"></a>

## MAKE-P09 — Stream Physical Integration Repair

```text
Proceed to a focused realism repair pass for the stream only.

PASS NAME:
Stream Physical Integration Repair

SCENE CONTEXT:
This is the approved daytime version of the hero scene. The overall composition, daytime atmosphere, lighting direction, ring, bunker, path, grassland, distant mountains, and stream placement are already approved. The main remaining realism issue is now the stream and its immediate banks.

IMPORTANT:
Do not change the global lighting mood.
Do not redesign the environment.
This pass is specifically about making the stream feel physically real and integrated into the terrain.

PRIMARY GOAL:
The stream currently reads too much like a smooth trench with a water material strip placed inside it. Rework it so it feels like a shallow natural stream with believable banks, wet transitions, shallow-water behavior, and realistic contact with soil, rocks, and nearby vegetation.

KEEP:
- Keep the approved camera and overall composition exactly the same.
- Keep the current daytime atmosphere.
- Keep the stream’s overall location and path logic.
- Keep the ring as primary focal point and bunker as secondary focal point.
- Keep the overall grassland character and terrain layout.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — STREAM SHAPE AND BANK PROFILE

1. Refine the stream cross-section so it feels naturally eroded rather than artificially cut.
2. Break up the current overly smooth and uniform bank edges.
3. Introduce subtle natural irregularity:
   - uneven slope angles,
   - small erosion notches,
   - local soft collapses,
   - slight width variation,
   - more believable asymmetry between left and right banks.
4. Preserve the overall stream layout, but make the local shape more natural and less like a designed trench.

SECTION B — WATER-TO-BANK TRANSITION

1. This is a high priority issue.
2. The boundary between the water and the banks currently feels too clean and too abrupt.
3. Create a believable wet transition zone along the water edge:
   - darker damp mud / wet soil,
   - gradual transition into drier soil and grass,
   - irregular edge width,
   - softer material blending.
4. Avoid a clean hard border between water and land.
5. The stream should feel embedded into the terrain, not cut out and filled.

SECTION C — SHALLOW WATER REALISM

1. Rework the water shading so the stream reads as shallow natural water.
2. Add more believable variation in:
   - depth,
   - transparency,
   - reflectivity,
   - roughness,
   - subtle flow surface behavior.
3. Let the center channel feel slightly deeper and the edges shallower where appropriate.
4. Allow some parts of the stream bed to influence the read of the water.
5. Avoid mirror-like reflections and avoid a flat uniform grey ribbon look.
6. The water should feel calm to gently flowing, not turbulent.

SECTION D — STREAM BED, ROCKS, AND CONTACT

1. Improve the relationship between water, stream bed, and rocks.
2. Add or refine a small number of partially embedded rocks and stones where useful.
3. These rocks should feel grounded:
   - partially buried,
   - darkened by wetness,
   - integrated with sediment,
   - interacting naturally with the water edge.
4. Introduce subtle stream-bed realism:
   - shallow sediment variation,
   - gentle bed unevenness,
   - small contact changes around rocks.
5. Do not overpopulate the stream with stones.

SECTION E — VEGETATION NEAR WATER

1. Add restrained local vegetation variation near the banks.
2. Allow some grass clumps or sparse stream-edge plants to soften the bank edges.
3. Keep this subtle and consistent with the existing dry grassland environment.
4. Do not turn the stream into a lush green riverbank.
5. The purpose is to improve realism and soften the artificial cut-edge feel.

SECTION F — REALISM GUIDANCE

1. The stream should feel like part of the landscape system, not a separate graphic element.
2. Prioritize physical integration over decorative detail.
3. Solve the problem through a combination of:
   - local geometry refinement,
   - wet/dry material transitions,
   - shallow-water shading,
   - embedded contact detail,
   - restrained vegetation support.
4. Do not try to solve the problem with a texture swap alone.

DO NOT:
- Do not change the approved camera or composition.
- Do not alter the daytime mood.
- Do not redesign the ring or bunker.
- Do not move the stream path significantly.
- Do not make the stream much wider or dramatically different in shape.
- Do not overdo rocks or vegetation.
- Do not create glossy mirror-water.
- Do not create a uniformly muddy trench.
- Do not add overly busy micro-detail that distracts from the scene.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One close render focused on the foreground stream and banks.
3. One medium-distance render showing how the stream integrates into the wider landscape.
4. A short summary explaining:
   - how the bank profile was improved,
   - how wet/dry transitions were handled,
   - how water shading was corrected,
   - what was done with rocks and vegetation.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p10"></a>

## MAKE-P10 — Stream Water Readability Recovery

```text
Proceed to a focused correction pass for the stream water only.

PASS NAME:
Stream Water Readability Recovery

SCENE CONTEXT:
This is the approved daytime version of the hero scene. In the previous stream realism pass, the banks and terrain integration were improved, but the water itself was over-corrected. The stream now reads too much like a damp trench or partially dried channel rather than shallow flowing water.

IMPORTANT:
Do not redo the whole stream from scratch.
Do not change the global lighting, atmosphere, or composition.
This pass is specifically about restoring the visual readability of the water while keeping the improved bank integration.

PRIMARY GOAL:
Make the stream clearly read as shallow natural water again, while preserving the more grounded banks and terrain integration from the previous pass.

KEEP:
- Keep the approved camera and overall composition exactly the same.
- Keep the current daytime atmosphere.
- Keep the stream path and the broader bank shape improvements.
- Keep the overall terrain and vegetation layout.
- Keep the existing wet-bank concept.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — RESTORE WATER IDENTITY

1. The stream currently looks too dry, muddy, and visually flat.
2. Restore a clear water read so it no longer feels like a damp ditch.
3. The stream should visibly read as shallow water, not just wet ground.
4. Reintroduce a more convincing distinction between:
   - actual water surface,
   - wet bank / mud transition,
   - dry surrounding terrain.

SECTION B — WATER SURFACE RESPONSE

1. Add subtle but visible water-surface behavior.
2. Introduce gentle small-scale surface variation using restrained water normal detail.
3. The water should show:
   - soft directional surface breakup,
   - mild flow-oriented texture behavior,
   - subtle micro-ripples,
   - calm-to-gently-flowing character.
4. Avoid large waves or stylized ripple patterns.

SECTION C — REFLECTION AND SHALLOW WATER READ

1. Reintroduce believable reflection response so the water catches the sky and light naturally.
2. This should remain subtle and physically plausible:
   - not mirror-like,
   - not overly glossy,
   - but clearly more reflective than the current version.
3. The stream should show a believable balance of:
   - shallow transparency,
   - muted reflection,
   - soft water-surface sheen.
4. Let some areas reflect the sky slightly more, especially at view angles where shallow water would naturally pick up light.

SECTION D — DEPTH VARIATION

1. Improve the read of water depth.
2. The stream should not look like a uniformly filled channel.
3. Introduce subtle depth variation:
   - slightly deeper center channel,
   - shallower edges,
   - occasional slight changes along the flow path.
4. Use shading, roughness, color, and transparency differences to support this read.

SECTION E — WATER VS. WET MUD SEPARATION

1. Preserve the improved wet-bank transition, but do not let the wet bank visually merge into the water too much.
2. The waterline should still feel naturally blended, but the viewer must be able to tell where actual water is present.
3. Keep the transition soft and natural, but restore clearer water-body readability.

SECTION F — INTERACTION WITH ROCKS AND BED

1. Keep the rocks integrated and partially embedded.
2. Let the water feel like it flows around or past them subtly.
3. Preserve natural contact logic, but allow the water surface to react more visibly around stones and shallow bed variation.
4. Do not overcomplicate the stream with too many disturbances.

DO NOT:
- Do not change the overall stream path.
- Do not redesign the banks again from scratch.
- Do not remove the wet-bank realism.
- Do not turn the water into a mirror.
- Do not make the water bright, glossy, or artificial.
- Do not make the stream turbulent.
- Do not let the stream go back to looking like a flat material strip.
- Do not leave it looking like a dried mud trench.

TECHNICAL EXECUTION NOTES:
- Focus mainly on shader/material correction for the water, plus only small supporting adjustments where necessary.
- Recover water readability through a better balance of reflection, roughness, normals, transparency, and shallow depth cues.
- Preserve the improved terrain integration, but restore the water’s visual identity.
- Evaluate primarily from the approved final camera, but also inspect the stream in closer preview views if needed.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One close render of the foreground stream.
3. One medium-distance render showing the stream in context.
4. A short summary explaining:
   - how water readability was restored,
   - how reflection and shallow-water cues were adjusted,
   - how bank realism was preserved while separating water from wet mud.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p11"></a>

## MAKE-P11 — Stream Flow Read Enhancement

```text
Proceed to a focused refinement pass for the stream water motion read.

PASS NAME:
Stream Flow Read Enhancement

SCENE CONTEXT:
This is the approved daytime version of the hero scene. The overall composition, lighting, atmosphere, ring, bunker, terrain, stream path, and bank integration are already approved. The stream now reads more clearly as water than before, but it still feels too static. The remaining issue is that it does not convincingly feel like gently flowing shallow water.

IMPORTANT:
Do not redesign the stream again.
Do not change the global lighting, composition, or overall daytime mood.
Do not undo the improved bank integration.
This pass is specifically about restoring a believable sense of gentle water flow.

PRIMARY GOAL:
Make the stream feel like shallow water that is actively but gently flowing through the landscape, while preserving the current bank realism and overall scene balance.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the current daytime atmosphere and lighting.
- Keep the current stream path and overall bank shape.
- Keep the existing wet-bank logic.
- Keep the current rock placement and vegetation logic broadly intact.
- Keep the stream calm and shallow in character.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — ADD GENTLE FLOW READ

1. The stream currently reads too static.
2. Introduce a clearer sense of gentle flow along the stream direction.
3. The water should feel like it is slowly moving downstream, not sitting still.
4. This should be subtle and realistic, not exaggerated.

SECTION B — SURFACE MOTION LANGUAGE

1. Refine the water surface so it has directional flow-oriented surface behavior.
2. Add subtle small-scale ripple and normal variation that follows the stream direction.
3. Avoid random or isotropic surface noise.
4. The surface should show a quiet but readable flow structure.
5. The water should remain calm to gently flowing, not choppy or turbulent.

SECTION C — FLOW VARIATION ACROSS THE CHANNEL

1. Introduce a more believable flow hierarchy across the stream width.
2. The center of the stream may feel slightly more active / slightly smoother-faster in flow character.
3. The edges should feel slightly slower and shallower.
4. Allow subtle variation along the stream path depending on width, bend, and depth changes.
5. Do not make the stream behavior uniform from end to end.

SECTION D — INTERACTION WITH ROCKS AND BED

1. Improve how the water behaves around stones and embedded forms.
2. Allow rocks to create subtle flow disturbance:
   - small ripple breakup,
   - slight wake / deflection feeling,
   - local surface variation around contact areas.
3. Keep this understated and realistic.
4. Avoid obvious stylized whitewater or dramatic turbulence.

SECTION E — SHALLOW WATER DYNAMICS

1. Preserve the shallow-water readability.
2. Let subtle depth changes influence the water read:
   - some areas slightly smoother,
   - some areas slightly more broken,
   - some areas slightly clearer or slightly more reflective.
3. Support the sense that shallow flowing water is interacting with the stream bed.
4. Keep everything restrained and physically plausible.

SECTION F — WATER READABILITY VS. MOTION

1. Preserve the current recovery of water identity.
2. Do not lose the clear distinction between:
   - water,
   - wet bank,
   - dry terrain.
3. The stream must still clearly read as water.
4. This pass should add flow feeling, not reduce water readability.

DO NOT:
- Do not redesign the banks again.
- Do not remove the current wet-bank integration.
- Do not make the water turbulent.
- Do not add strong waves.
- Do not add stylized white foam or rapids.
- Do not make the water highly reflective or mirror-like.
- Do not turn the stream into a motion-effects shot.
- Do not make the entire water surface uniformly noisy.
- Do not lose the calm, natural, shallow-stream character.

TECHNICAL EXECUTION NOTES:
- Focus mainly on water shader refinement, directional normal behavior, subtle flow cues, and local interaction around rocks and shallow-bed variation.
- Solve this through restrained surface dynamics, not through exaggerated effects.
- Preserve editability and clean scene organization.
- Evaluate primarily from the approved final camera, but use close review renders to confirm the flow read.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One close render focused on the foreground stream surface.
3. One medium-distance render showing the stream flow read in context.
4. A short summary explaining:
   - how the sense of flow was added,
   - how directional surface behavior was improved,
   - how rocks and shallow bed affect the water read,
   - how calm realism was preserved.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p12"></a>

## MAKE-P12 — Stream Surface Correction and Bunker Readability Check

```text
Proceed to a focused correction pass for the approved daytime hero scene.

PASS NAME:
Stream Surface Correction and Bunker Readability Check

SCENE CONTEXT:
This is the approved daytime version of the scene. The giant ring remains the primary visual subject. The bunker remains the secondary subject. The camera, composition, terrain layout, ring placement, bunker placement, distant mountains, path, human figure, and overall daytime mood are already approved and must remain unchanged.

IMPORTANT:
Do not shift the scene toward the darker stormy lighting direction explored earlier.
Keep the current brighter daytime atmosphere.
This pass has one primary task and one secondary task:

PRIMARY TASK:
Correct the stream water so it reads as believable shallow flowing water.

SECONDARY TASK:
Check and lightly improve the bunker’s lighting readability so its major planes read more clearly, while keeping it secondary to the ring.

REFERENCE IMAGE ROLES:
- Image A = current full-scene render.
- Image B = close crop of the stream showing the current water issue.
- Image C (if provided) = bunker crop for lighting/readability inspection.

PRIMARY GOAL:
The stream currently does not look physically convincing. Its surface reads too much like a uniform brushed or stretched material pattern rather than real shallow flowing water. Correct this while preserving the improved stream placement, bank integration, and current scene balance.

SECONDARY GOAL:
The bunker still reads as underlit and visually flattened. Check the current sunlight/environment-light behavior and improve the readability of the bunker’s main concrete planes, without making the bunker brighter than the ring or changing the overall daytime setup.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the current daytime atmosphere and overall lighting mood.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current stream path and bank shape.
- Keep the current rock placement and overall vegetation layout broadly intact.
- Keep the ring’s emissive lighting and center hanging platform accent.
- Keep the lower fog beam beneath the ring.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — STREAM SURFACE CORRECTION (PRIMARY TASK)

A1. CORE DIAGNOSIS
The stream currently reads too much like a uniform stretched/dragged texture or brushed surface pattern.
It has directional noise, but it does not convincingly read as actual shallow flowing water.

A2. WATER SURFACE LANGUAGE
Rebuild the water-surface read so it feels like calm-to-gently-flowing shallow water.
The surface should show:
- subtle directional flow behavior,
- gentle small-scale ripple structure,
- restrained surface variation,
- slight differences across the stream width and along the stream path.

Avoid a single uniform streaked pattern repeated across the whole stream.

A3. FLOW STRUCTURE
The stream should feel like it is gently moving downstream.
Introduce more believable flow structure:
- center channel slightly more active / slightly smoother-faster,
- edges slightly shallower and quieter,
- mild variation around bends, narrowing/widening, and depth changes,
- subtle interaction with the channel form.

Do not make the water turbulent or stylized.

A4. REFLECTION / TRANSPARENCY / SHALLOW WATER BALANCE
Correct the balance between reflection and transparency.
The stream should not look like a flat grey-white strip.
It should show a believable shallow-water mix of:
- soft sky reflection,
- visible but restrained shallow-bed influence,
- subtle water-surface sheen,
- physically plausible Fresnel response.

Avoid mirror-like water.
Avoid overly muddy opaque water.
Avoid losing water readability.

A5. ROCK INTERACTION
Improve the local water behavior around rocks and embedded forms.
The current rocks are present, but the water does not interact with them strongly enough.
Add subtle local flow disturbance:
- mild directional breakup,
- tiny wake/deflection feeling,
- small local surface variation around stones,
- slight change in water behavior where it passes obstacles.

Keep this subtle and realistic. No foam or whitewater.

A6. BANK RELATION
Preserve the current improved wet-bank idea and bank integration.
Do not redesign the stream banks from scratch.
Do not remove the wet soil transition.
But ensure that the water body remains visually distinct from the wet bank.

A7. STREAM PRIORITY SUMMARY
The stream must stop looking like a stretched textured ditch and start reading as believable shallow flowing water embedded in the landscape.

SECTION B — BUNKER READABILITY CHECK (SECONDARY TASK)

B1. DIAGNOSIS
The bunker still reads as visually underlit and flattened.
This appears to be caused by a combination of:
- current sun angle,
- terrain/shadowing from the hillside,
- low contrast from the atmospheric conditions,
- and limited material response.

B2. GOAL
Improve the readability of the bunker’s main concrete planes without changing the scene’s approved daytime mood and without making the bunker compete with the ring.

B3. LIGHTING CHECK
Inspect the current sun direction and environment light behavior.
If necessary, make only small controlled adjustments so the bunker’s major planes read more clearly.
The purpose is not to re-light the whole scene, but to slightly improve form readability.

B4. BUNKER PLANE READABILITY
Create better separation between the bunker’s major surfaces:
- front-facing planes,
- sloped planes,
- recessed entrance area,
- side transitions near the hillside.

Keep the recessed entrance appropriately darker.
Allow some subtle light response on the large concrete surfaces so they no longer feel too flat.

B5. MATERIAL RESPONSE
If needed, make small controlled adjustments so the bunker material responds to light more naturally.
Do not redesign the bunker material in this pass.
Do not start a full bunker weathering pass again.
This is only a readability/support correction.

B6. HIERARCHY RESTRICTION
The bunker must remain secondary.
Do not brighten it enough to rival the ring.
Do not add fake fill lights that break the scene logic.

SECTION C — DO NOT

Do not change the approved camera or composition.
Do not alter the current daytime mood into a darker moody-overcast scene.
Do not redesign the stream path or widen it dramatically.
Do not redesign the banks again from scratch.
Do not solve the stream with one uniform directional noise texture.
Do not make the stream mirror-like, plastic, or overly glossy.
Do not make the stream turbulent.
Do not add foam, rapids, or dramatic water effects.
Do not re-stage the ring lighting.
Do not make the bunker a brighter focal point than the ring.
Do not perform a full bunker material overhaul in this pass.

SECTION D — TECHNICAL EXECUTION NOTES

For the stream:
- Focus on water shader correction, flow-oriented but non-uniform surface behavior, reflection/transparency balance, and local interaction around rocks and shallow-bed changes.
- The result should feel like gentle real flow, not animated stylization.

For the bunker:
- Focus on readability, not a full redesign.
- Prefer small adjustments to light direction, light balance, and material response rather than adding artificial-looking extra lights.

Evaluate all decisions primarily from the approved final camera, and secondarily through closer inspection views.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One close render focused on the stream surface and its interaction with rocks/banks.
3. One medium-distance render showing the stream integrated in the wider landscape.
4. One closer render focused on the bunker showing improved plane readability.
5. A short summary explaining:
   - how the stream surface was corrected,
   - how the stretched/dragged fake-water look was reduced,
   - how flow structure was improved,
   - whether any small lighting adjustments were made for the bunker,
   - how the bunker was kept secondary while improving readability.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p13"></a>

## MAKE-P13 — Final Water Reflection and Sky Layering Refinement

```text
Proceed to a final refinement pass for the approved daytime hero scene.

PASS NAME:
Final Water Reflection and Sky Layering Refinement

SCENE CONTEXT:
This is the approved daytime version of the scene. The giant ring remains the primary visual subject and the bunker remains the secondary subject. The camera, composition, terrain layout, ring placement, bunker placement, stream path, distant mountains, vegetation distribution, and overall daytime mood are already approved.

IMPORTANT:
This is a controlled final polish pass.
Do not redesign the scene.
Do not shift the image toward the darker moody-overcast lighting explored in earlier versions.
The current scene lighting direction, exposure logic, and daytime atmosphere remain the master condition.

The sky must be refined to support the already approved scene lighting, not the other way around.

REFERENCE IMAGE ROLES:
- Image A = current approved daytime working render.
- Image B = v093 sky reference. Use it only for cloud richness, layering, and sky structure inspiration.
Do NOT copy Image B’s darker mood or allow the whole scene lighting to drift toward it.

PRIMARY GOALS:
1. Slightly improve the stream so the water reflection is clearer and the water reads a bit more cleanly.
2. Improve the sky so it has richer cloud layering and less empty blank space, while still matching the current approved lighting and daytime feel.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the current brighter daytime atmosphere.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current terrain, stream path, rocks, vegetation, distant mountains, and fog layout broadly intact.
- Keep the current scene lighting logic as the master reference.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — STREAM WATER REFLECTION REFINEMENT

A1. GOAL
The stream is close, but the water can still read slightly more clearly.
Increase water readability by making the reflection response a little clearer and more natural.

A2. REFLECTION ADJUSTMENT
Refine the water so it catches the sky and light a little more clearly.
This should be subtle and controlled:
- slightly clearer soft reflection,
- slightly better surface sheen,
- a cleaner shallow-water read,
- improved readability from the approved camera.

A3. RESTRICTIONS
Do not turn the stream into a mirror.
Do not make it glossy or metallic.
Do not lose the shallow-water transparency and stream-bed influence.
Do not increase turbulence.
Do not redesign the banks again.

A4. BALANCE
Keep the current calm shallow-stream character.
The result should feel like the same stream, but with a slightly cleaner and more legible water surface.

SECTION B — SKY LAYERING REFINEMENT

B1. CORE GOAL
The current sky lacks structure and has too much empty space.
Enrich the sky so it feels more dimensional, layered, and believable.

B2. USE OF V093 REFERENCE
Use the v093 reference sky only as inspiration for:
- richer cloud layering,
- more interesting cloud mass distribution,
- better large-to-medium cloud structure,
- a more complete sense of atmospheric depth.

Do NOT copy:
- the darker storm mood,
- the heavier contrast,
- the overall darker lighting balance,
- or the older version’s lighting dominance.

B3. SKY MUST FOLLOW CURRENT SCENE LIGHTING
This is critical:
The sky must be designed to match the current approved scene lighting and atmospheric condition.
Do not relight the scene to match the sky.
Instead, shape the sky so it feels naturally consistent with:
- the current scene brightness,
- the current direction and softness of light,
- the current haze/fog behavior,
- and the current cool daytime atmosphere.

B4. CLOUD STRUCTURE
Add more cloud hierarchy and structure:
- broad soft cloud masses,
- mid-scale variation,
- subtle thinner layers where appropriate,
- gentle value variation across the sky.

Reduce the sense of blank empty space.
Make the sky feel more complete and intentional.

B5. VALUE AND MOOD CONTROL
Keep the sky within the current approved lighting range.
Do not make it dramatically darker.
Do not add theatrical storm drama.
Do not create strong god rays or a new dominant weather event.
Keep the result elegant, restrained, and believable.

B6. HORIZON / ATMOSPHERIC INTEGRATION
Ensure the sky still integrates naturally with the existing fog, distant mountains, and atmospheric perspective.
The sky should support the scene’s scale and openness without overpowering the ring.

SECTION C — GLOBAL RESTRICTIONS

Do not change the approved camera or composition.
Do not shift the scene toward stormy overcast lighting.
Do not redesign the ring, bunker, terrain, or stream path.
Do not make the water mirror-like or overly bright.
Do not let the sky become the dominant subject.
Do not significantly alter the overall exposure of the scene.
Do not re-stage the lighting to imitate v093.
Do not darken the bunker or landscape in order to match the new sky.

SECTION D — TECHNICAL EXECUTION NOTES

For the stream:
- Use small controlled shader/material adjustments to improve reflection readability and surface clarity.
- Preserve the current shallow-water logic and bank integration.

For the sky:
- Focus on cloud composition, layering, structure, and tonal variation.
- Treat the current scene lighting as the governing condition.
- The sky should be richer, but still clearly belong to the current version of the scene.

Evaluate all changes primarily from the approved final camera.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One closer render focused on the stream showing the improved water reflection.
3. One sky-focused render showing the refined cloud layering.
4. A short summary explaining:
   - how the stream reflection was refined,
   - how the sky layering was improved,
   - how the v093 sky qualities were translated without changing the current scene lighting,
   - and how the sky was kept subordinate to the approved scene mood.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p14"></a>

## MAKE-P14 — Sky Mood Compression and Controlled Breakthrough Light

```text
Proceed to a controlled final sky refinement pass for the approved daytime hero scene.

PASS NAME:
Sky Mood Compression and Controlled Breakthrough Light

SCENE CONTEXT:
This is the approved daytime version of the scene. The giant ring remains the primary visual subject and the bunker remains the secondary subject. The camera, composition, terrain layout, ring placement, bunker placement, stream, distant mountains, and overall daytime mood are already approved.

IMPORTANT:
This pass is focused mainly on the sky.
Do not redesign the scene.
Do not shift the image into a full storm or dark overcast version.
Do not relight the whole scene to follow a new sky concept.
The current scene lighting and overall daytime atmosphere remain the governing condition.

PRIMARY GOALS:
1. Keep the current sky direction from Image A, but make the overall mood slightly darker / slightly more subdued.
2. Add a believable controlled light breakthrough in the upper-right-rear sky area behind the ring.
3. The breakthrough light must feel natural and cloud-driven, not like an artificial opening or hard spotlight.
4. Use Image C as inspiration for the cloud-light interaction logic.

REFERENCE IMAGE ROLES:
- Image A = current approved working render.
- Image B = previous problematic version showing the kind of breakthrough area that feels incorrect / too artificial.
- Image C = reference for the desired cloud-edge / filtered-light behavior.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current daytime scene identity.
- Keep the terrain, stream, fog, and distant mountains broadly unchanged.
- Keep the current overall lighting direction logic.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — OVERALL SKY MOOD

1. Compress the sky mood slightly compared with Image A.
2. The sky should become a little more subdued, a little more overcast, and slightly less open/bright.
3. This is only a subtle reduction in brightness and openness.
4. Do not turn the scene into a dark storm scene.
5. The result should still feel like the same daytime version, just with a little more atmosphere and a little less flat brightness.

SECTION B — CONTROLLED BREAKTHROUGH LIGHT BEHIND THE RING

1. Introduce a controlled sunlight breakthrough area in the sky behind and above the ring, slightly toward the ring’s upper-right rear side.
2. This breakthrough area should suggest that sunlight is partially hidden behind thicker cloud masses and is leaking through selectively.
3. The light must feel filtered by cloud volume, not like a clean cut-out in the sky.
4. Avoid a hard “hole in the clouds” look.
5. Avoid obvious theatrical god rays.
6. The effect should feel atmospheric, natural, and restrained.

SECTION C — USE IMAGE C AS THE BEHAVIOR REFERENCE

1. Use Image C only as a reference for the cloud-light interaction behavior:
   - thicker cloud masses partially obscuring the sun,
   - brighter cloud edges / subtle silver-lining behavior,
   - soft filtered light leakage,
   - gradual cloud density transition,
   - believable atmospheric depth.
2. Do not copy Image C’s color palette literally if it conflicts with the current scene.
3. Do not turn the scene golden, sunset-like, or painterly.
4. Translate the cloud-light logic into the current cooler daytime scene.

SECTION D — AVOID THE PROBLEMS SEEN IN IMAGE B

1. Do not create an artificial-looking bright opening.
2. Do not create sharply defined spotlight-like beams.
3. Do not create multiple unrelated breakthrough regions.
4. Do not make the sky feel like it was designed only to force a dramatic effect.
5. The cloud opening must feel like a natural variation in cloud thickness, not a geometric gap.

SECTION E — CLOUD STRUCTURE AND LAYERING

1. Add richer structure in the sky overall, but especially around the upper-right region near the breakthrough light.
2. Use a combination of:
   - broad cloud mass organization,
   - medium-scale variation,
   - subtle edge softness,
   - gradual tonal transitions.
3. Reduce blank empty sky feeling.
4. Keep the cloud system believable and coherent across the whole image.
5. Preserve a clean cinematic look rather than an over-detailed noisy sky.

SECTION F — RELATION TO THE CURRENT SCENE LIGHTING

1. This is critical: the sky must follow the current approved scene lighting, not the reverse.
2. The sky refinement may slightly support the ring area with atmospheric plausibility, but it must not force a full scene relight.
3. Do not significantly darken the landscape or bunker to “match” the new sky.
4. Do not brighten the ring unnaturally.
5. Any sky-lighting influence on the scene should remain subtle and consistent with the current approved daytime setup.

SECTION G — GLOBAL RESTRICTIONS

Do not change the approved camera or composition.
Do not redesign the ring, bunker, terrain, or stream.
Do not turn the scene into a dramatic storm image.
Do not create harsh god rays.
Do not create an obvious hard-edged hole in the sky.
Do not make the sky the dominant subject.
Do not significantly alter the approved exposure balance of the scene.

SECTION H — TECHNICAL EXECUTION NOTES

- Focus primarily on sky composition, cloud mass shaping, tonal organization, and filtered-light behavior.
- Treat the current scene as locked and adjust the sky to fit it.
- The desired effect is a more nuanced sky with a believable upper-right light breakthrough.
- Keep the final result elegant, restrained, realistic, and cinematic.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One sky-focused crop showing the refined upper-right cloud/light breakthrough area.
3. A short summary explaining:
   - how the overall sky was slightly subdued,
   - how the upper-right breakthrough light was created,
   - how Image C influenced the cloud-edge behavior,
   - and how the sky was kept subordinate to the approved scene lighting.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p15"></a>

## MAKE-P15 — Sky Volumetric Mass Enhancement

```text
Proceed to a focused final sky refinement pass for the approved daytime hero scene.

PASS NAME:
Sky Volumetric Mass Enhancement

SCENE CONTEXT:
This is the approved daytime version of the scene. The giant ring remains the primary visual subject and the bunker remains the secondary subject. The camera, composition, terrain layout, ring placement, bunker placement, stream, distant mountains, and overall daytime atmosphere are already approved and must remain unchanged.

IMPORTANT:
This pass is specifically about improving the sky.
Do not redesign the scene.
Do not shift the image into a dark storm scene.
Do not relight the whole scene to match a new sky concept.
The current approved scene lighting and daytime mood remain the governing condition.

PRIMARY GOALS:
1. Replace the current thinner sky treatment with more substantial large cloud masses.
2. Increase the sense of volumetric cloud presence, depth, and cloud-body thickness.
3. Keep the sky consistent with the current approved daytime scene.
4. Preserve a controlled filtered-light area behind and above the ring toward the upper-right, but make it feel driven by thick cloud volume rather than a thin bright patch.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current terrain, stream, fog, distant mountains, and overall lighting logic.
- Keep the current daytime identity of the image.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — CORE SKY ISSUE

The current sky feels too thin and lacks enough volumetric cloud mass.
It has surface variation, but the clouds do not yet feel like large physical cloud bodies.
The goal is to make the sky feel more three-dimensional and substantial.

SECTION B — LARGE CLOUD MASS DESIGN

1. Introduce clearer large-scale cloud forms.
2. Build several broad, soft, volumetric cloud masses rather than relying mostly on thin cloud texture.
3. The sky should read as organized by a few major cloud bodies with supporting mid-scale variation.
4. Avoid a uniformly textured ceiling of thin clouds.

SECTION C — VOLUMETRIC FEEL

1. Increase the sense of cloud thickness and depth.
2. The clouds should feel like they occupy space, with:
   - visible mass,
   - layered depth,
   - soft overlap,
   - thickness variation,
   - clearer front/back cloud relationships.
3. Preserve softness and realism.
4. Do not make the sky overly noisy or hyper-detailed.

SECTION D — CLOUD HIERARCHY

Build cloud hierarchy using:
- large primary cloud masses,
- medium internal structure,
- restrained small-scale edge detail.

The sky should feel composed and cinematic, not procedurally busy.

SECTION E — UPPER-RIGHT FILTERED LIGHT AREA

1. In the upper-right-rear sky region behind and above the ring, preserve a controlled light breakthrough area.
2. This should feel like sunlight filtering from behind thicker cloud masses.
3. The light must be shaped by cloud thickness and cloud-edge behavior.
4. Avoid a hard opening in the sky.
5. Avoid obvious theatrical god rays.
6. The effect should feel like heavy cloud volume with selective soft leakage of light.

SECTION F — MOOD CONTROL

1. Keep the scene within the current approved daytime mood.
2. The sky may be slightly more subdued and atmospheric than before, but do not turn the whole image into a storm scene.
3. Do not dramatically darken the landscape.
4. Do not make the sky the dominant subject.
5. The final result should feel more weather-rich and more physically present, but still restrained.

SECTION G — RELATION TO SCENE LIGHTING

This is critical:
The sky must support the current approved scene lighting.
Do not significantly alter the ground lighting, bunker lighting, or ring lighting in order to accommodate the sky.
Only allow subtle atmospheric support if needed.
The scene lighting remains locked; the sky must conform to it.

SECTION H — DO NOT

Do not change the approved camera or composition.
Do not redesign the ring, bunker, stream, or terrain.
Do not create only thin cloud texture.
Do not create a flat overcast sheet.
Do not make the sky look like a dramatic apocalypse storm.
Do not create hard-edged bright holes in the clouds.
Do not add exaggerated god rays.
Do not make the sky more visually dominant than the ring.

SECTION I — TECHNICAL EXECUTION NOTES

- Focus on cloud massing, broad volumetric structure, depth layering, and filtered-light behavior.
- The key improvement is cloud body volume, not just extra texture.
- Keep the sky elegant, coherent, and realistic.
- Evaluate primarily from the approved final camera.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One sky-focused crop showing the new cloud mass structure.
3. A short summary explaining:
   - how cloud volume was increased,
   - how large cloud masses were introduced,
   - how the upper-right filtered-light area was handled,
   - and how the current scene lighting was preserved.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p16"></a>

## MAKE-P16 — Natural Cloud Mass Reconstruction and Sky Scale Correction

```text
Proceed to a corrective sky cloud-design pass.

PASS NAME:
Natural Cloud Mass Reconstruction and Sky Scale Correction

SCENE CONTEXT:
The current scene is the approved cool daytime cinematic environment featuring the giant mechanical ring on the right and the brutalist bunker on the left.

The previous cloud enhancement pass produced an unsatisfactory result.

The clouds now appear too large, too close to the camera, and unnaturally inflated. Several cloud undersides contain repetitive, rounded, blue-grey forms resembling giant cotton balls or hanging foam.

This does not look like a believable expansive sky.

IMPORTANT:
Do not continue adding detail to the current cloud formations without first inspecting their implementation.

If the current cloud system is fundamentally unsuitable, revert the sky to the last stable version before the latest large-cloud enhancement and rebuild only the cloud treatment.

Do not revert any approved scene improvements unrelated to the sky.

REFERENCE ROLES:
Image A = current unsatisfactory cloud result.
Image B = previous approved daytime sky before the oversized cloud enhancement.

Use Image B as the baseline for brightness, daytime identity, and atmospheric integration.

PRIMARY GOAL:
Replace the oversized artificial cloud formations with a believable, expansive, naturally layered daytime sky featuring broad broken stratocumulus cloud banks and restrained cumulus structure.

The sky should gain depth and visual richness without appearing overcrowded, stormy, or excessively volumetric.

PHASE 1 — INSPECT THE CURRENT CLOUD SYSTEM

1. Inspect the existing sky and cloud implementation.
2. Identify whether the oversized appearance is caused by cloud geometry placement, volume density, procedural noise, cloud scale, shading, or camera proximity.
3. Determine why the cloud undersides exhibit repeated round or bulbous patterns.
4. Do not assume the current volumetric approach must be preserved.
5. Compare the current sky with the last stable daytime sky.

If necessary, restore the earlier sky as the working baseline before rebuilding the cloud structure.

PHASE 2 — CORRECT CLOUD SCALE AND SPATIAL DEPTH

1. Clouds should feel geographically expansive and appropriately distant.
2. Avoid giant individual cloud bodies appearing directly above the bunker or camera.
3. Build broad cloud banks with natural horizontal extension and varied vertical thickness.
4. Preserve believable perspective and atmospheric scale.
5. Avoid oversized hanging cloud bottoms or exaggerated downward bulges.

IMPORTANT:
Large-scale cloud coverage does not mean enormous foreground cloud blobs.

PHASE 3 — NATURAL CLOUD MORPHOLOGY

1. Favor broad broken stratocumulus and layered cumulus forms.
2. Create believable large-scale organization:
   - broad cloud banks,
   - irregular medium-scale structures,
   - soft smaller details near selected cloud edges.
3. Avoid repeated spherical or cauliflower-like shapes.
4. Avoid uniform rounded cavities on cloud undersides.
5. Avoid excessively dark blue cloud interiors.
6. Cloud bottoms should have soft irregular shading and naturally varying thickness.
7. Use smooth, multi-scale density variation rather than dominant high-frequency procedural noise.

PHASE 4 — CLOUD DISTRIBUTION

1. Distribute cloud structures naturally across the visible sky.
2. Avoid crowding all large formations along the top of the frame.
3. Preserve some natural blue-grey sky openings between cloud banks.
4. Create gradual transitions from thicker clouds to thinner atmospheric layers.
5. Keep the lower sky and distant horizon relatively soft and open.
6. Ensure the sky feels continuous and spacious rather than filled with isolated floating objects.

PHASE 5 — UPPER-RIGHT SUNLIGHT REGION

1. Preserve the existing approved scene lighting direction.
2. Behind and above the ring, toward camera-right, introduce a subtle region of thinner cloud coverage.
3. The existing sunlight should appear to filter naturally through or around the clouds.
4. Use soft cloud-edge illumination and gradual density transitions.
5. Avoid sharp openings, artificial glowing circles, or hard volumetric shafts.
6. The sunlight effect must follow the existing scene lighting, not force a new lighting direction.

PHASE 6 — PRESERVE SCENE LIGHTING

CRITICAL:
The current cool daytime lighting is approved.

Do not significantly modify:
- Sun direction
- Main light intensity
- World illumination
- Exposure
- Color management
- Bunker lighting
- Ring lighting
- Terrain lighting
- Existing basin fog

If clouds are currently driving unwanted changes to scene illumination, investigate a controlled separation between visible cloud appearance and environment illumination where appropriate.

Any such separation must remain visually coherent and must not introduce contradictory lighting.

The sky must support the existing scene, not control a new lighting setup.

PHASE 7 — TECHNICAL APPROACH

Choose the most suitable approach after inspecting the current implementation.

Possible methods include:
- refined distant volumetric cloud banks,
- layered sky textures or cloud planes with convincing depth,
- a hybrid sky treatment combining broad background clouds and selected volumetric formations.

Do not use expensive volumetric geometry merely because the reference requests "volumetric clouds."

The priority is realistic final-camera appearance, stable rendering, and editability.

PHASE 8 — STRICT PRESERVATION

Do not change:
- Approved camera or composition
- Giant ring geometry or materials
- Bunker geometry or materials
- Terrain and vegetation
- Stream and lake
- Distant mountains
- Existing atmospheric basin fog
- Warm industrial lighting
- Current cool daytime scene identity

Do not introduce:
- Giant cotton-ball clouds
- Repeated rounded cloud cavities
- Extremely low hanging cloud masses
- Dark storm-cloud ceilings
- Artificial god rays
- Multiple competing sunlight regions
- Excessive cloud detail or visual noise

OUTPUT AND REVIEW:

Create two restrained alternatives.

Variation A:
Broad, natural, relatively thin stratocumulus cloud banks with clear atmospheric depth.

Variation B:
Slightly thicker cloud masses and richer layering, but still distant, soft, and natural.

For both versions:
- Preserve the exact approved camera.
- Preserve scene lighting and exposure.
- Produce the full-scene render.
- Produce a sky-focused comparison.
- Report the actual cloud implementation method.
- Explain what caused the previous oversized cloud appearance.
- Compare against the earlier approved daytime sky.

Save new versions without overwriting previous approved work.

STOP FOR HUMAN REVIEW.
Do not finalize either variation automatically.
```

<a id="make-p17"></a>

## MAKE-P17 — Distant Mountain Depth Enhancement and Fog Clarity Adjustment

```text
Proceed to a focused background-depth refinement pass for the approved daytime hero scene.

PASS NAME:
Distant Mountain Depth Enhancement and Fog Clarity Adjustment

SCENE CONTEXT:
This is the approved cool daytime version of the scene. The giant ring remains the primary visual subject and the bunker remains the secondary subject. The camera, composition, terrain layout, ring placement, bunker placement, stream, vegetation, and overall daytime mood are already approved.

IMPORTANT:
Do not continue pushing the sky/cloud complexity as the main solution.
This pass should improve background depth primarily by enhancing the distant mountain structure and slightly reducing the obscuring effect of the background fog.

PRIMARY GOALS:
1. Add taller and more convincing distant mountain forms in the far background.
2. Increase the readability of the far mountains so the scene gains more depth and large-scale environmental presence.
3. Slightly reduce the density of the mid/far atmospheric fog so the mountains can be seen more clearly.
4. Keep the current cool daytime scene identity and do not redesign the overall lighting.

REFERENCE IMAGE ROLE:
Use the reference image only for the compositional idea of distant higher mountains and layered landscape depth.
Do NOT copy its painterly brush style, color palette, forest design, or seasonal appearance.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current stream, terrain, and vegetation layout broadly unchanged.
- Keep the current overall daytime lighting and cool atmosphere.
- Keep the existing low fog beam beneath the ring.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — DISTANT MOUNTAIN ENHANCEMENT

1. Add taller far-background mountain silhouettes behind the basin and behind / around the ring region.
2. These mountains should feel significantly farther away than the current terrain.
3. They should read as large distant landforms, not nearby steep hills.
4. Introduce layered mountain depth:
   - one or more very far mountain masses,
   - subtle intermediate ridgelines where useful,
   - atmospheric separation between layers.
5. The mountains should help extend the world and increase the scene’s scale.

SECTION B — MOUNTAIN SHAPE AND READABILITY

1. The mountain silhouettes should be elegant and believable.
2. Avoid making them too sharp, too graphic, or too dominant.
3. Preserve atmospheric perspective:
   - lower contrast,
   - softer edges,
   - lighter value shift with distance,
   - cooler distant coloration.
4. The mountains should remain clearly readable, but secondary.

SECTION C — FOG CLARITY ADJUSTMENT

1. Slightly reduce the density of the mid/far fog and atmospheric haze so the new distant mountains read more clearly.
2. This is only a modest reduction.
3. Preserve the scene’s existing sense of atmosphere and basin depth.
4. Keep the fog under and around the ring functioning as part of the environment.
5. Do not remove the fog entirely.
6. The goal is slightly better background clarity, not a fully clear dry day.

SECTION D — SKY STRATEGY

1. Do not continue pushing large volumetric cloud masses as the main solution.
2. The sky should remain supportive and relatively restrained.
3. If any cloud adjustments are needed, keep them subtle and subordinate.
4. The main background improvement should come from distant mountains plus clearer atmospheric layering.

SECTION E — COMPOSITION AND HIERARCHY

1. Ensure the new mountains support the composition without competing with the ring.
2. The ring must remain the dominant background subject.
3. The mountains should provide context, scale, and depth, not become the new focal point.
4. Keep the bunker visually subordinate but readable.

SECTION F — GLOBAL RESTRICTIONS

Do not change the approved camera or composition.
Do not redesign the ring, bunker, stream, terrain, or path.
Do not introduce painterly or stylized interpretation.
Do not make the mountains too dark or too close.
Do not make the sky dramatically stormy.
Do not eliminate the existing atmospheric softness.
Do not over-clarify the scene to the point of losing mood.

SECTION G — TECHNICAL EXECUTION NOTES

- Focus on distant mountain layering, atmospheric perspective, and subtle fog-density adjustment.
- Prioritize large-scale environmental depth over sky spectacle.
- Use the reference image conceptually for background structure only.
- Evaluate primarily from the approved final camera.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One crop focused on the distant mountain region.
3. A short summary explaining:
   - how the distant mountains were added or strengthened,
   - how atmospheric depth was preserved,
   - how the fog density was slightly reduced,
   - and how the ring remained the dominant subject.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p18"></a>

## MAKE-P18 — Giant Off-Frame Planet Addition

```text
Proceed to a controlled background-sky enhancement pass.

PASS NAME:
Giant Off-Frame Planet Addition

SCENE CONTEXT:
This is the approved cool daytime hero scene. The giant ring remains the primary focal point and the bunker remains the secondary focal point. The camera, composition, terrain, stream, distant mountain layering, and overall daytime atmosphere are already approved.

IMPORTANT:
This pass is not about adding a new dominant subject.
It is about introducing a very subtle gigantic celestial body in the upper-left portion of the sky to strengthen composition, world scale, and science-fiction atmosphere.

The celestial body must feel extremely large, extremely distant, and outside the atmosphere, with very low contrast and very soft visual integration.

PRIMARY GOAL:
Add a huge off-frame planet so that only the lower-right portion of that planet is visible entering from the upper-left part of the image.

The viewer should feel the impression of standing on one planet and looking up at another enormous world in the sky.

REFERENCE ROLE:
Use the provided reference only for the conceptual idea of a gigantic planetary body dominating the sky from off-frame.
Do NOT copy its sunset lighting, ocean setting, or painterly style.

KEEP:
- Keep the approved camera and composition exactly the same.
- Keep the ring as the primary focal point.
- Keep the bunker as the secondary focal point.
- Keep the current terrain, stream, fog, distant mountains, and sky mood broadly unchanged.
- Save the result as a new version file. Do not overwrite the current approved version.

SECTION A — PLANET PLACEMENT

1. Place the planet in the upper-left part of the sky.
2. The planet should be mostly off-frame.
3. Only the lower-right section / arc of the planet should be visible.
4. The visible curvature should be large enough to imply an enormous planetary scale.

SECTION B — SCALE AND PRESENCE

1. The planet must feel colossal.
2. It should not read as a small moon or nearby object.
3. The visual impression should be that of a massive world occupying the sky beyond the atmosphere.
4. The effect should convey awe and large-scale planetary context.

SECTION C — VISUAL SUBTLETY

1. Keep the planet very subtle.
2. It should be faint, soft, and low-contrast.
3. Reduce saturation significantly.
4. The planet should feel partially veiled by the atmosphere and integrated into the sky.
5. Avoid hard edges, high contrast, or sharp cutout appearance.

SECTION D — SURFACE TREATMENT

1. The planet may have very soft, broad surface variation or gentle banding / terrain-like tonal variation.
2. Keep the detail minimal and large-scale only.
3. Avoid dense high-frequency texture.
4. Avoid making the planet more detailed than the ring.

SECTION E — ATMOSPHERIC INTEGRATION

1. Integrate the planet with the current sky using atmospheric fading.
2. Its visibility should feel affected by the scene’s haze and sky brightness.
3. The planet should sit behind the atmospheric layer visually.
4. Its edge may have a very subtle rim or soft tonal falloff, but do not create a strong glowing outline.

SECTION F — COMPOSITIONAL HIERARCHY

1. The ring must remain the main focal point.
2. The bunker must remain secondary.
3. The planet is a tertiary worldbuilding element only.
4. It should enrich the upper-left composition without stealing attention.

SECTION G — TECHNICAL APPROACH

Because this is a fixed-camera hero frame, it is acceptable and recommended to solve this using a 2.5D or compositing-based approach rather than a full scene-scale planetary simulation.

Acceptable methods include:
- compositing a high-quality planet render or PNG with atmospheric adjustment,
- a camera-facing image plane,
- or a simple rendered sphere pass composited into the sky.

Choose the most controllable and efficient method.

SECTION H — DO NOT

Do not make the planet too dark.
Do not make it too sharp.
Do not make it too saturated.
Do not place the full planet fully inside frame.
Do not allow it to dominate over the ring.
Do not change the approved scene lighting.
Do not turn the sky into a dramatic space scene.

OUTPUT:
After finishing, save a new version and provide:
1. The updated final camera render.
2. One sky-focused crop showing the added planet.
3. A short summary explaining:
   - what method was used (composite / plane / sphere pass),
   - how the planet was integrated into the atmosphere,
   - and how hierarchy was preserved so the ring remains dominant.

STOP FOR REVIEW after producing the previews. Do not continue to another pass until reviewed and approved.
```

<a id="make-p19"></a>

## MAKE-P19 — Giant Planet Silhouette and Atmospheric Compositing Repair

```text
Proceed to a focused correction pass for the newly added giant planet.

PASS NAME:
Giant Planet Silhouette and Atmospheric Compositing Repair

CURRENT PROBLEM:
The previous pass attempted to add a huge, faint planet in the upper-left sky.

However, the current result does not read as a spherical celestial body.

It looks like a large diagonal grey-blue overlay across the sky, with almost no readable planetary curvature or surface information.

This is not the intended result.

REFERENCE ROLES:
Image A = latest Blender render showing the incorrect planet.
Image B = previous approved daytime scene before the planet was added.
Image C = giant planet artistic reference, for celestial scale and atmosphere only.

PRIMARY GOAL:
Create a believable, extremely large, distant planetary body that is mostly outside the upper-left frame.

Only a portion of its lower-right limb should be visible.

The viewer must recognize the subtle curvature of an enormous planet beyond the atmosphere, without the planet becoming a dominant visual subject.

PHASE 1 — DIAGNOSE THE CURRENT RESULT

1. Inspect the current planet implementation.
2. Identify whether it uses an image plane, PNG texture, compositor, or 3D sphere.
3. Check the alpha channel, blend mode, material setup, scale, and placement.
4. Determine why the current result appears as a straight diagonal overlay instead of a spherical limb.
5. If the current asset or setup is unsuitable, replace only the planet implementation.

Do not rebuild the entire scene.

PHASE 2 — CORRECT THE PLANETARY CURVATURE

1. Position the planet's center well outside the upper-left frame.
2. Keep most of the planetary disc outside the image.
3. Show a partial lower-right limb entering the upper-left sky.
4. The visible limb must have a recognizable curved silhouette.
5. Avoid making the planet so oversized that its local arc appears completely straight.
6. Ensure the planet does not overlap the giant mechanical ring.
7. Avoid covering the bunker or important foreground objects.

PHASE 3 — ADD SUBTLE PLANETARY DETAIL

1. Introduce very faint large-scale surface variation.
2. Possible details include:
   - broad atmospheric bands,
   - soft cloud formations,
   - subtle planetary tonal variations.
3. These details should be barely visible.
4. Avoid sharp terrain textures, obvious craters, or excessive detail.
5. Maintain a cool grey-blue palette matching the existing sky.
6. Preserve a believable spherical shading gradient.

PHASE 4 — CORRECT THE COMPOSITING

1. The planet must have a proper circular alpha silhouette.
2. Do not apply a rectangular or triangular translucent color overlay to the entire sky.
3. If using PNG or image-plane compositing, verify correct alpha handling and premultiplication.
4. Composite the planet behind the atmospheric sky elements where appropriate.
5. Blend the visible planetary disc subtly into the current daytime atmosphere.
6. Use restrained atmospheric scattering and tonal compression to reduce its contrast.
7. Keep the visible edge soft, but recognizable.
8. Avoid a bright glowing outline around the entire limb.

PHASE 5 — PRESERVE THE EXISTING SCENE

Do not modify:
- Camera and composition
- Giant ring
- Bunker
- Terrain and grass
- Stream and lake
- Distant mountains
- Current fog
- Sun direction
- World illumination
- Exposure and color management
- Existing industrial lighting

The giant ring remains the primary focal point.
The bunker remains the secondary focal point.
The planet is a subtle tertiary worldbuilding element.

PHASE 6 — PREVIEW VARIATIONS

Create two variations:

Variation A — Extremely Subtle:
The planet is very faint, with a barely visible but recognizable curved limb and minimal surface detail.

Variation B — Slightly More Readable:
The planet has somewhat clearer curvature and soft surface variation, while still remaining low-contrast and visually secondary.

Use the same geometry, placement, camera, and scene exposure for both versions.

Do not modify global lighting to make the planet visible.

OUTPUT:
1. An isolated planet pass showing the correct circular silhouette and transparency.
2. Final-camera render of Variation A.
3. Final-camera render of Variation B.
4. A sky-focused comparison crop.
5. A short technical report identifying the cause of the previous diagonal-overlay appearance.
6. Save a new Blender version without overwriting the last approved scene.

STOP FOR HUMAN REVIEW.
Do not proceed to additional scene modifications.
```

<a id="make-p20"></a>

## MAKE-P20 — Giant Jupiter-like Planet Replacement and Reframing

```text
Proceed with a focused planet asset replacement and scale correction pass.

PASS NAME:
Giant Jupiter-like Planet Replacement and Reframing

CURRENT PROBLEM:
The current giant planet is not convincing.
Its procedural texture does not resemble a real gas giant.
It also appears too small and too confined to the upper-left corner, so the sense of colossal scale is weak.

PRIMARY GOALS:
1. Replace the current planet texture with a more realistic Jupiter-like appearance.
2. Increase the planet’s apparent size dramatically so that it feels like an enormous world mostly outside the frame.
3. Keep the planet very subtle and atmospheric, but still readable as a gigantic celestial body.
4. Preserve the current scene, composition, lighting, fog, ring, bunker, mountains, stream, and overall daytime mood.

TEXTURE / ASSET INSTRUCTION:
Do not keep the current soft procedural texture.
Use a realistic Jupiter-like texture based on an official NASA global Jupiter map if available.
Preferred texture source:
- Hubble Jupiter Global Map (2019), equirectangular / flat global map
Alternative:
- New Horizons Jupiter Atmospheric Map
Optional secondary reference:
- Cassini Great Red Spot true-color image for local color and storm structure reference

If network access is available, fetch an official NASA Jupiter global map.
If not, use the user-provided downloaded texture.

MATERIAL / PLANET LOOK:
- The planet should resemble Jupiter:
  - large horizontal atmospheric bands
  - subtle tonal variation
  - soft storm structure
  - recognizable gas giant appearance
- Avoid synthetic cloud-ball noise or generic foggy texture.
- Keep surface detail broad and large-scale, not overly sharp.
- Keep the color subdued and compatible with the current pale blue daylight sky.

IMPORTANT COMPOSITION NOTE:
The current planet is too small.
Make the planet much larger in frame.

TARGET SCALE:
- Planet diameter should feel approximately 2.2x to 3x the frame width.
- Most of the planet must remain outside the frame.
- Only the lower-right limb of the planet should be visible.
- The visible arc should extend across a significant part of the top-left sky.
- The result should feel like the viewer is standing on one world and looking up at another enormous world beyond the atmosphere.

TARGET FRAMING:
- Planet center stays far outside the upper-left of the frame.
- Show a strong curved limb, not a small corner patch.
- The visible planetary arc should occupy substantially more area than in the previous attempt.
- Do not let the planet overlap the mechanical ring.
- Do not let the planet dominate the entire image more than the ring.

READABILITY VS SUBTLETY:
- Keep the planet faint and atmospheric.
- However, the curvature must be clearly readable.
- The texture should be visible enough to read as a gas giant.
- Do not reduce it to a nearly flat translucent overlay.

GREAT RED SPOT HANDLING:
- If possible, orient the texture so the Great Red Spot faces roughly toward camera.
- However, do not force the Great Red Spot to be fully centered if that breaks the giant-scale framing.
- Priority order:
  1. colossal scale
  2. believable planetary curvature
  3. realistic Jupiter banding
  4. Great Red Spot partial visibility if composition allows
- If the Great Red Spot cannot be shown clearly without weakening the colossal off-frame composition, prefer correct scale and subtle Jupiter banding.

RENDER / COMPOSITING INSTRUCTION:
- Use a proper spherical object or a correctly rendered planet pass.
- Do not fake the effect as a simple flat diagonal sky overlay.
- Preserve soft atmospheric blending.
- Maintain low contrast.
- Avoid a hard glowing rim.
- Keep it integrated with the current sky.

PRESERVE:
- camera
- bunker
- ring
- mountains
- fog
- stream
- grassland
- current lighting and daytime atmosphere

OUTPUT:
1. One version with “colossal scale priority”
2. One version with “slightly more readable Jupiter texture”
3. A cropped sky comparison
4. A short note stating:
   - texture source used
   - whether the Great Red Spot is visible
   - why the chosen scale works better

STOP FOR REVIEW.
Do not change any other scene element.
```

<a id="make-p21"></a>

## MAKE-P21 — Neptune / Saturn Planet Material Look-Development

```text
Create two planet material look-development variants.

Use the currently approved daytime hero scene.
Do not change the camera, ring, bunker, terrain,
lighting, atmosphere, or planet composition.

Replace the existing synthetic planet texture
with real planetary texture assets.

Variation A — Desaturated Neptune:
- Use a high-quality equirectangular Neptune texture.
- Preserve recognizable atmospheric bands and storms.
- Reduce saturation toward a cool slate-blue palette.
- Maintain subtle but readable planetary detail.

Variation B — Cool Grey Saturn:
- Use a high-quality equirectangular Saturn texture.
- Preserve its natural horizontal atmospheric bands.
- Shift warm beige/yellow colors toward cool neutral grey.
- Do not add prominent planetary rings.

For both variations:
- Keep the planet extremely large and mostly off-frame.
- Preserve a recognizable spherical limb.
- Keep the planet behind the atmospheric sky.
- Adjust the planet's color and contrast independently
  from the scene's global color management.
- Do not reduce opacity so far that planetary texture
  becomes unreadable.
- Do not create a flat translucent overlay.
- Preserve the giant mechanical ring as the main subject.

Render both variations from the exact approved camera,
using identical planet placement and apparent size.

Save new versions and stop for review.
```

<a id="make-p22"></a>

## MAKE-P22 — Giant Planet Realism + Distant Mountain Structure Refinement

```text
Proceed with a combined background-worldbuilding refinement pass.

PASS NAME:
Giant Planet Realism + Distant Mountain Structure Refinement

SCENE CONTEXT:
This is the approved cool daytime hero scene.
The giant mechanical ring remains the primary focal point.
The bunker remains the secondary focal point.
The current overall daytime atmosphere, terrain, stream, fog, composition, and cinematic mood are broadly approved.

IMPORTANT:
Do not redesign the scene.
Do not change the approved camera.
Do not alter the core composition.
This pass is specifically about refining:
1. the giant planet in the upper-left sky,
2. the distant mountain layers beneath the sky.

The goal is to improve realism, scale, atmospheric integration, and worldbuilding strength while preserving the approved shot.

==================================================
SECTION 1 — KEEP / PRESERVE
==================================================

Keep unchanged unless absolutely necessary:
- camera and framing
- ring design and placement
- bunker design and placement
- foreground terrain and path
- stream placement and current overall shape
- grassland layout
- current daytime lighting direction
- current overall exposure and color management
- current fog mood and basin atmosphere
- overall scene identity

The ring must remain the main focal point.
The bunker must remain the secondary focal point.
The planet and distant mountains must remain supporting worldbuilding/background elements.

Save as a new version file.
Do not overwrite the current approved version.

==================================================
SECTION 2 — GIANT PLANET REFINEMENT
==================================================

CURRENT PROBLEMS:
The current giant planet is improved compared to earlier versions, but it still has several issues:
- it still feels somewhat like an inserted texture rather than a truly enormous celestial body,
- its integration with the sky is not fully natural,
- its scale can be pushed further to strengthen the “colossal world above” feeling,
- the texture/material may still not be the best match for the current cool-toned scene.

PRIMARY GOALS:
1. Make the giant planet feel more believable and more physically present in the sky.
2. Preserve a sense of extreme scale: the viewer should feel they are standing on one world and looking up at another enormous world beyond the atmosphere.
3. Improve realism of the planet’s material and shading.
4. Improve atmospheric integration without losing readability.

--------------------------------
2A — Texture / Material
--------------------------------

Use a realistic large-scale planetary texture instead of a generic synthetic cloud-ball look.

Preferred approach:
- Use a real planetary equirectangular texture or a highly believable planet texture reference.
- A Jupiter-like texture is acceptable if a suitable cool-toned version can be made.
- If the Jupiter coloration clashes with the scene too much, use a better-fitting cool-toned gas giant texture (for example a desaturated Neptune-like or cool-grey Saturn-like look).
- The final texture should match the current scene better than the previous warm Jupiter attempt.

Material requirements:
- broad planetary banding / atmospheric structure
- believable large-scale cloud patterns
- subtle storm structure
- not overly sharp
- not overly noisy
- no generic procedural blur-ball appearance

Color requirements:
- keep the planet in a cool, low-saturation range
- compatible with the pale blue-grey daytime sky
- avoid strong warm orange/yellow tones unless extremely subtle
- avoid making the planet brighter than the surrounding sky by too much

--------------------------------
2B — Scale / Framing
--------------------------------

The planet still needs a stronger colossal presence.

Requirements:
- Increase the apparent scale so the planet occupies more of the upper-left and upper sky area.
- The planet should feel enormous, with most of its disc still outside the frame.
- Do not make it a small object sitting in the corner.
- The visible planetary limb should extend farther across the upper-left region so the viewer feels the sky is being occupied by a massive celestial body.
- However, do not let the planet overlap the ring.
- Do not let the planet become the dominant focal point over the ring.

Target compositional feeling:
- The planet should be a huge off-frame celestial body.
- The visible arc should clearly imply that the majority of the planet lies outside the image.
- It should feel awe-inspiring and massive, not like a decorative background element.

--------------------------------
2C — Shading / Spherical Readability
--------------------------------

Improve the sense that this is a real sphere:
- introduce subtle spherical shading / curvature logic,
- ensure the planet reads as a round body rather than a flat composited patch,
- keep the curvature readable even though the planet remains subtle.

Do not:
- flatten it into a translucent overlay,
- create an unnaturally strong rim glow,
- over-contrast the planet.

--------------------------------
2D — Atmospheric Integration
--------------------------------

The planet must feel outside the atmosphere but seen through the current sky and haze.

Requirements:
- integrate it with the sky using atmospheric fading,
- soften the transition into the sky naturally,
- keep the edge recognizable but not cut-out sharp,
- prevent the planet from looking like a pasted PNG or a separate layer,
- preserve subtle visibility of texture.

Do not simply lower opacity until all detail disappears.
Do not create a hard-edged collage look.

--------------------------------
2E — Optional Great Red Spot Handling
--------------------------------

If a Jupiter-like texture is used:
- If composition allows, orient the texture so a large storm feature / Great Red Spot-like structure is visible within the visible portion of the planet.
- However, do not sacrifice the giant off-frame scale just to center the Great Red Spot.
- Priority order:
  1. giant scale,
  2. believable spherical presence,
  3. good texture integration,
  4. visible storm feature if possible.

==================================================
SECTION 3 — DISTANT MOUNTAIN REFINEMENT
==================================================

CURRENT PROBLEMS:
The distant mountain layers beneath the sky still feel too soft, too smooth, and too uniform.
They read more like wave-shaped silhouette layers or cutout backdrops rather than believable mountain ranges.
The atmospheric depth exists, but the landform realism is weak.

PRIMARY GOALS:
1. Make the distant mountains feel like real mountain systems rather than smooth layered wave shapes.
2. Increase the structural difference between mountain layers.
3. Improve their interaction with fog.
4. Preserve them as background elements that support scale and depth.

--------------------------------
3A — Mountain Silhouette Language
--------------------------------

Rework the mountain silhouettes:
- reduce the overly smooth, repeated wave-like forms,
- introduce more natural ridgeline variation,
- create a believable rhythm of peaks, shoulders, and valleys,
- add subtle asymmetry and local irregularity,
- preserve restraint: these mountains are distant, not hero mountains.

Do not:
- create extremely sharp alpine peaks,
- create dramatic fantasy spikes,
- over-detail them.

The final result should look like real far-off mountain ranges seen through atmosphere.

--------------------------------
3B — Layer Differentiation
--------------------------------

The mountain layers should no longer feel like copies of the same shape at different opacities.

Give each layer a distinct structural role:
- farthest layer:
  - tallest / broadest
  - most faded
  - softest
  - most atmospheric
- middle layer:
  - somewhat more readable
  - more varied ridgeline rhythm
  - subtle mountain structure
- nearer distant layer:
  - slightly clearer
  - more grounded
  - still clearly atmospheric and secondary

Preserve depth using:
- value separation
- softness
- atmospheric perspective
- silhouette variation

--------------------------------
3C — Fog Integration
--------------------------------

The mountain and fog relationship must be more natural.

Requirements:
- avoid uniform transparency across entire mountain layers,
- let some mountain bases sink more into basin fog,
- let some ridgeline sections remain slightly more readable,
- vary the local interaction so it feels organic rather than evenly faded,
- preserve the current gentle daytime mist mood.

Especially behind the ring and behind the bunker:
- improve the mountain-to-fog transition,
- avoid the “flat backdrop card in fog” look.

--------------------------------
3D — World Scale Support
--------------------------------

The mountains must help sell the world scale.
They should support the scale of the giant ring rather than undermine it.

Requirements:
- the environment should feel expansive,
- the mountains should feel large enough to belong to the same world as the ring,
- but they must not compete for attention.

==================================================
SECTION 4 — PRIORITY AND FOCUS
==================================================

This pass should focus only on:
1. giant planet realism / scale / integration,
2. distant mountain structure / layering / fog interaction.

Do not use this pass to change:
- bunker material weathering
- stream design
- foreground rock scattering
- grass distribution
- ring lighting
- overall scene lighting
- sky cloud redesign

Those may be refined later if needed.
For this pass, keep variables limited and controlled.

==================================================
SECTION 5 — OUTPUT REQUIREMENTS
==================================================

Please produce:

1. One final-camera render: Version A
   - planet with “colossal scale priority”
   - mountain refinement applied

2. One final-camera render: Version B
   - same mountain refinement
   - planet slightly more readable in texture/detail while preserving background status

3. One sky-focused crop showing the planet integration

4. One background-focused crop showing the refined mountain layering behind the ring

5. One background-focused crop showing the refined mountain layering behind the bunker

6. A short technical summary explaining:
   - what texture/material approach was used for the planet,
   - how planetary scale/framing was adjusted,
   - how atmospheric integration was improved,
   - how mountain silhouettes were refined,
   - how mountain layer differentiation was increased,
   - how mountain-fog interaction was improved

STOP FOR REVIEW after rendering.
Do not continue to additional scene refinements.
```

<a id="make-p23"></a>

## MAKE-P23 — SMALL SECONDARY PLANET ON THE GIANT PLANET LIMB

```text
==================================================
SECTION 6 — SMALL SECONDARY PLANET ON THE GIANT PLANET LIMB
==================================================

Add one small secondary planet positioned along the visible limb / edge transition area where the giant main planet meets the sky.

PRIMARY GOAL:
Introduce a subtle but readable secondary celestial body to enhance the sense of a larger planetary system and reinforce the sci-fi scale of the sky.

REQUIREMENTS:
1. Use the user-provided Neptune texture / reference for this secondary planet.
2. The small planet should be clearly much smaller than the giant main planet.
3. Position it near the arc / limb area of the giant main planet, so it appears close to the boundary where the giant planet’s visible curve meets the open sky.
4. The placement should feel intentional and elegant, not random.
5. Keep the secondary planet subtle and believable:
   - not too bright
   - not too saturated
   - not too sharp
   - not visually competing with the ring or bunker
6. Preserve the feeling that it is very far away, suspended in the same sky system.
7. The secondary planet should remain fully readable as a small spherical object.
8. It should not overlap the ring.
9. It should not attract more attention than the giant main planet.
10. It should help enrich the upper-left / upper-sky composition without cluttering it.

VISUAL STYLE:
- cool-toned Neptune-like appearance
- soft but readable spherical shading
- subtle atmospheric integration
- slight desaturation if needed so it harmonizes with the current scene

PLACEMENT NOTE:
Try placing the small planet along or near the visible arc of the giant main planet, where the curvature is easiest to read.
It should feel like a companion body in the same celestial composition.

OUTPUT:
Include this small secondary planet in both Version A and Version B.
If needed, provide one additional crop focused on the upper-left sky showing:
- the giant main planet,
- the small Neptune-like planet,
- and their relationship to the sky.

Do not change other scene elements while adding this feature.
```

Additional original instruction / concept note:

```text
Prefer placing the small secondary planet slightly off the giant planet’s limb rather than exactly sitting on the edge, so the silhouette remains clear and the celestial layering feels more natural.
```

<a id="make-p24"></a>

## MAKE-P24 — Distant Mountain Geological Realism and Surface Detail Refinement

```text
Proceed to a focused realism correction pass for the existing distant mountain system.

PASS NAME:
Distant Mountain Geological Realism and Surface Detail Refinement

CURRENT PROBLEM:
The distant mountains currently look too smooth, rounded, pale, and artificial.

They resemble large grey-white hills, soft dunes, or simplified layered silhouettes rather than believable natural mountain ranges.

The problem is not simply insufficient texture detail.
The mountains also lack convincing geological structure, erosion patterns, directional shading, and natural surface variation.

PRIMARY GOAL:
Transform the existing distant mountains into believable large-scale geological formations while preserving their atmospheric distance and secondary visual role.

The desired style is realistic, rugged, distant mountain terrain with subtle volcanic-rock characteristics, inspired by Icelandic and other cold-region mountain landscapes.

IMPORTANT:
Do not make the mountains look closer.
Do not turn them into dramatic foreground mountains.
Do not increase their contrast excessively.

The ring remains the primary visual subject.

REFERENCE ROLES:
Image A = current Blender render showing the unrealistic distant mountains.
Image B, if provided = real distant geological mountain reference.

PHASE 1 — INSPECT EXISTING MOUNTAINS

Before modifying anything:

1. Inspect how the current mountains were created.
2. Determine whether they are actual 3D terrain meshes, procedural geometry, image cards, or another implementation.
3. Inspect their current materials, normals, texture coordinates, lighting response, and fog interaction.
4. Determine why the mountains appear excessively smooth and uniformly pale.
5. Produce a temporary diagnostic preview with reduced background haze if necessary to reveal the underlying mountain structure.

Do not permanently change the approved fog during diagnosis.

PHASE 2 — IMPROVE GEOLOGICAL SHAPE

The current mountains lack natural geological formation.

Improve their large-scale structure by introducing:

- believable primary mountain ridges,
- secondary branching ridges,
- natural erosion gullies,
- irregular mountain shoulders,
- asymmetric slopes,
- subtle rocky formations,
- more realistic peak and valley relationships.

Avoid uniformly rounded hill shapes.

Do not rely on random noise alone.

The terrain should appear shaped by long-term geological and erosion processes.

Keep the overall mountain placement and distant-background composition.

PHASE 3 — SURFACE MATERIAL REALISM

Introduce realistic but restrained mountain surface detail.

Use a combination of:

1. Large-scale rock and soil color variation.
2. Medium-scale erosion and geological patterns.
3. Subtle rock normal and roughness variation.
4. Limited darker rock exposure on suitable slopes.
5. Natural material transitions across mountain faces.

If suitable assets are available, use tileable photographic rock materials or realistic terrain textures.

If procedural shading is used, avoid uniform high-frequency noise.

Use object/world-space or triplanar mapping where appropriate to prevent stretching on steep slopes.

IMPORTANT:
The surface should feel geological rather than decorative.

PHASE 4 — LIGHTING RESPONSE

The mountains currently lack convincing light-facing and shadow-facing surfaces.

Improve their response to the EXISTING sunlight direction.

- Allow mountain slopes to display subtle directional shading.
- Preserve natural shadowing in valleys and erosion channels.
- Improve large-form value separation.
- Avoid uniform flat shading.
- Avoid artificially painting dark stripes onto the terrain.

Do not move the main Sun light or change the approved scene lighting.

The mountain geometry and materials must work with the existing light.

PHASE 5 — ATMOSPHERIC PERSPECTIVE

Maintain believable distance.

The farthest mountains should remain:

- lower contrast,
- less saturated,
- softer,
- cooler in color,
- partially obscured by atmospheric haze.

However, do not erase all geological detail.

Preserve slightly more readable ridgelines and sunlit/shaded slope relationships where appropriate.

Allow mountain bases to fade naturally into basin haze.

Avoid uniformly applying the same transparency to entire mountain layers.

PHASE 6 — LAYER DIFFERENTIATION

Make the mountain layers geologically distinct.

Farthest range:
- broad, large-scale geological structure,
- very subdued rock details,
- strong atmospheric perspective.

Middle distant range:
- more recognizable ridges and erosion structure,
- moderate surface variation,
- still low contrast.

Nearest distant range:
- slightly clearer rocky slopes,
- subtle material detail,
- still visually behind the giant ring and bunker.

Avoid repeated wave-like silhouettes.

PHASE 7 — PRESERVE THE APPROVED SCENE

Do not modify:

- final camera
- giant mechanical ring
- bunker
- giant gas planet in the upper-left sky
- small Neptune-like companion planet
- existing sky appearance
- terrain and foreground vegetation
- stream and lake
- lighting direction
- global exposure
- color management
- ring-base fog and light effects

This pass is ONLY for the distant mountain system and necessary local mountain-atmosphere integration.

PHASE 8 — OUTPUT

Save a new Blender version without overwriting the previous approved version.

Provide:

1. Updated full-scene camera render.
2. A mountain-focused diagnostic render with reduced haze.
3. The same mountain view with the approved atmospheric haze restored.
4. A close-up showing geological and material detail.
5. A short report explaining:
   - original mountain geometry and material problems,
   - geological shape improvements,
   - surface texture improvements,
   - lighting-response improvements,
   - atmospheric integration changes.

STOP FOR HUMAN REVIEW.

Do not continue to any additional scene modifications.
```

---

## 中文阅读说明

这里保留项目原始任务提示词，包括中间试验与纠错。最终采用方向以[制作流程](Workflow_EN_CN.md)为准。未收录完整聊天记录；涉及本地电脑的路径替换为 `<local asset path>`。通过[提示词索引](Prompt_Index_EN_CN.md)查找对应阶段。
