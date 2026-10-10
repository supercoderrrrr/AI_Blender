# Reference design prompts

Original project instructions, organized for reading. These are prompts, including experiments and corrections; the final choices are explained in [the workflow](Workflow_EN_CN.md). Full conversation transcripts are not included. Local machine paths are replaced with `<local asset path>` where present.

[Prompt index](Prompt_Index_EN_CN.md)

<a id="ref-p01"></a>

## REF-P01 — Extract the ring from the scene

```text
Using the uploaded final scene image as the master reference, extract and refine the distant ring megastructure into a clean standalone asset reference for Blender modeling.

The goal is not to redesign the object, but to clarify and isolate the already established ring design from the current scene so it can be modeled more accurately in Blender.

Keep only the ring megastructure and remove all environment elements, including the grassland, sky, hillside building, human figure, path, water, and distant mountains. Replace the background with a neutral light gray or another very simple clean background.

Preserve the core design language of the ring from the current scene:
- a giant complete ring structure
- white-grey industrial man-made surfaces
- clear large-scale structural segmentation
- a thick ring cross-section
- a few attached side platforms and protruding structures
- the suspended central hanging platform near the top interior
- lower support structures
- overall restrained, clean, realistic, and not overloaded with tiny mechanical noise

Make the image clearly show:
- the overall silhouette of the ring
- the thickness of the outer shell
- the inner rim structure
- the placement of the main attached platforms
- the suspended central structure
- how the lower support structures connect to the ground

For this round, do not create strict orthographic views. Instead, generate a clear three-quarter asset view that reveals the front, side thickness, and main structural hierarchy.

Requirements:
- neutral background
- soft even lighting
- no fog, no strong backlight, no depth of field blur
- full object visible, not cropped
- no labels, no titles, no measurement text
- do not invent many new small parts
- do not turn it into a space station, spaceship, or city
- do not make it more complex; only improve clarity and readability

The purpose is to provide a reliable visual reference for later Blender modeling.
```

<a id="ref-p02"></a>

## REF-P02 — Clean white and gray ring

```text
Based on the approved ring megastructure design, generate a clean standalone asset reference image suitable for Blender modeling.

The goal is not to redesign the object, but to convert it into a more modeling-friendly version for later Codex / Blender use.

Preserve the core design:
- a giant complete ring structure
- a heavy ring cross-section
- white-grey industrial man-made form language
- clear large-scale segmentation
- the left and right attached side platforms
- the suspended central platform near the top interior
- the lower support structures
- overall restrained, clean, and realistic

Please simplify the surface treatment and make it cleaner, closer to a white model / white-box / clay model presentation:

- remove most rust, dirt, aging, and weathering marks
- avoid large rusty streaks, heavy wear maps, corrosion, or grunge
- keep the essential panel seams, structural joints, layered surface zones, and a small amount of functional detail
- keep subtle shading so the form remains readable, but do not rely on material noise to show detail
- the result should feel like a clean pale grey industrial model, not a fully textured final concept painting

This round should focus on:
- improving structural readability
- making the large forms, thickness, connections, and module logic easier for Codex and Blender to understand
- not adding complexity
- not redesigning the object

Output requirements:
- one clear three-quarter asset view
- neutral light gray background
- soft even lighting
- no fog, no depth-of-field blur, no strong backlight
- full object visible, not cropped
- no labels, text, callouts, or measurements

The purpose is to create a primary visual reference for detailed Blender modeling.
```

<a id="ref-p03"></a>

## REF-P03 — Full ring orthographic views

```text
Use the uploaded ring megastructure as the locked master design reference.

Create a clean orthographic modeling reference sheet of exactly the same structure for Blender.

Show:
- front orthographic view
- side orthographic view
- top orthographic view
- rear orthographic view

Preserve exactly:
- overall outer diameter
- inner opening diameter
- axial thickness of the ring
- position and size of the left and right side platforms
- suspended central platform and its two vertical suspension supports
- lower structural supports
- main shell segmentation
- overall proportions and silhouette

This is NOT a redesign.
Do not improve, stylize, simplify, or reinterpret the architecture.
Every view must represent the exact same object.

Presentation:
- clean white / very light gray clay material
- no rust
- no dirt
- no weathering
- no decals
- no colored materials
- neutral light gray background
- soft, even studio lighting
- minimal shadows
- no fog
- no depth of field
- no dramatic lighting
- no environment

Keep panel seams and major structural boundaries visible, but remove unnecessary surface noise.

The purpose is accurate Blender blockout and proportion matching.
Structural consistency is more important than visual beauty.
```

<a id="ref-p04"></a>

## REF-P04 — Initial standard arc segment

```text
Use the uploaded ring megastructure as the locked master reference.

Isolate and develop one representative standard arc segment of the ring for detailed Blender modeling.

The segment should represent the normal repeating structural language of the ring, not one of the large attached platform zones.

Clearly show:
- outer armored shell
- inner ring surface
- axial side wall thickness
- major structural ribs
- large shell plates
- recessed structural channels
- panel seams
- internal support framing
- connection logic at both ends of the arc segment

Design hierarchy:
70% large structural forms
20% secondary structural layering
10% small functional detail

Avoid random greeble.

The segment must look engineered and modular, with believable construction logic.

Very important:
- preserve the design language of the master ring
- do not introduce a new sci-fi style
- do not cover every surface with small mechanical parts
- keep large clean panels
- small details should appear mainly around joints, recesses, access areas, and structural transitions

Presentation:
- clean white / pale gray clay model
- neutral background
- soft even studio lighting
- no rust
- no weathering
- no decals
- no environment
- no dramatic shadows

Show the segment in a clear three-quarter view where the outer shell, inner rim, side thickness, and one connection end are all visible.

This image will be used to build a reusable modular arc asset in Blender.
```

<a id="ref-p05"></a>

## REF-P05 — Correct a 20 degree segment

```text
Use the uploaded full ring megastructure image as the LOCKED MASTER DESIGN.

Create ONE clean standard modular arc segment extracted from the ordinary repeating portion of the ring.

This is NOT a new design and NOT a presentation sheet.

The purpose is to create a repeatable Blender module that can be duplicated around a circular ring.

MODULE DEFINITION:

- The segment represents approximately 20 degrees of the full ring.
- It must be a short arc segment, NOT a half-ring or large C-shaped section.
- Both ends must be clean radial cut planes.
- The start and end cross-sections must be structurally compatible so that identical copies can connect continuously.
- Do NOT create terminal end caps.
- Do NOT create X-braced end frames as exposed exterior features.
- Do NOT treat the ends as finished ends of a structure.
- The module must visually continue beyond both ends.

Preserve the design language of the master ring:

- broad pale outer armor panels
- darker recessed inner structural layers
- large longitudinal structural ribs
- restrained panel seams
- recessed maintenance channels
- believable structural depth
- clean industrial hard-surface construction

The module should contain:

PRIMARY STRUCTURE:
- curved main structural body
- outer armor shell
- inner structural rim
- axial side thickness
- major longitudinal support ribs

SECONDARY STRUCTURE:
- several large shell panels
- recessed service channels
- structural brackets at logical intervals
- a few maintenance access areas

TERTIARY DETAIL:
- very limited small functional detail
- only where structurally necessary

DETAIL HIERARCHY:
75% large clean structural surfaces
20% secondary structural features
5% small functional detail

Very important:
DO NOT add side platforms.
DO NOT add the suspended central platform.
DO NOT add foundation supports.
DO NOT add unique landmark structures.
DO NOT add antennas, buildings, towers, or decorative greeble.

This is the NORMAL repeating ring segment only.

SURFACE PRESENTATION:

- clean white / pale gray clay-model material
- no rust
- no dirt
- no weathering
- no decals
- no text
- no labels
- no material color variation
- neutral light gray background
- soft even studio lighting
- minimal shadows
- no fog
- no environment

CAMERA:

Show ONE clear three-quarter view only.

The camera must clearly reveal:
- the outer curved shell
- the inner rim
- the axial side thickness
- one start cut plane
- one end cut plane

The two ends should clearly look like continuation interfaces, not finished end caps.

Most important:
This asset must look like a modular section cut from the complete ring, not an independent curved building.

Do not redesign the master asset.
Prefer structural simplicity over invented detail.
```

<a id="ref-p06"></a>

## REF-P06 — Parametric Blender prototype task

```text
Build a parameterized ring-arc prototype in Blender using the two uploaded references.

REFERENCE PRIORITY
- The complete ring image defines the overall proportions and major structural relationships.
- The arc-segment image defines the local shell design, recessed channels, inner reinforcement, and detail hierarchy.
- Do not infer an exact arc angle or absolute dimensions from the perspective images.

TASK
Create one standard arc segment, then test its repetition before adding fine detail.

GEOMETRY
- Use an exact 20-degree angular span as the initial module setting.
- Expose the outer radius, inner radius, axial thickness, and segment angle as editable parameters.
- Use a common ring center and rotation axis for all repeated segments.
- Build a thick annular sector, not a round tube-shaped torus.
- Keep the cross-section consistent at both radial boundaries.
- When dimensions are ambiguous, state the provisional assumptions rather than presenting them as measured facts.

STRUCTURE
Build separate, editable objects or collections for:
1. primary curved structure;
2. broad shell panels;
3. recessed channels and inner reinforcement;
4. transverse brackets and connection frames.

Preserve the reference's large clean surfaces and selective detail.
Do not replace the design with random cubes or uniform greeble.
Do not model every tiny seam or fastener in this first pass.

CONNECTION TEST
- Display three adjacent segments.
- Check shell continuity, channel alignment, gaps, intersections,
  and accidentally doubled connection frames.
- Then test a complete 18-segment ring for closure.
- Do not hide connection problems with extra cover plates.

PRESENTATION
Use a neutral pale-gray material and soft lighting.
No rust, textures, fog, or dramatic effects.

DELIVERABLES
Save a new version of the Blender file without overwriting existing work.
Render:
- one isolated segment;
- three connected segments;
- the complete basic ring.

Report any unresolved geometric assumptions.
Stop for review before adding fine detail or other ring attachments.
```

<a id="ref-p07"></a>

## REF-P07 — Blender detail benchmark task

```text
Continue the existing Blender project from the current saved version.

The current model is acceptable as a structural prototype,
but it has NOT yet reached the visual fidelity of the approved reference.

This task is a LOCAL DETAIL BENCHMARK, not another blockout pass.

IMPORTANT CHANGE TO PREVIOUS INSTRUCTIONS
The earlier restriction against all small details no longer applies
inside the selected benchmark area.

Clean clay presentation does NOT mean low geometric detail.
Keep the material clean, but build the actual parts visible in the reference.

1. PRESERVE THE VALIDATED STRUCTURE

Save a new version of the Blender file and generator script.
Preserve the previous working versions and unrelated scene content.

Keep the existing ring dimensions, 20-degree module angle,
rotation axis, and validated connection logic.

Do not rebuild the entire ring.
Do not distribute new detail across the full ring yet.

2. INSPECT BEFORE EDITING

Open the full arc reference, the supplied detail crops,
and the current model screenshot.

Inspect the actual scene geometry from both sides.

Identify the mesh surfaces corresponding to:
- the broad armor face;
- the recessed rail/channel area;
- the transverse connection bracket.

Do not place the new detail only on a hidden or incorrect face.

If geometry already exists but is hidden, disabled, or too shallow
to read clearly, diagnose that before creating duplicate objects.

Briefly identify the three largest local differences from the reference,
then proceed with the modeling task.

3. WORK ON ONE REPRESENTATIVE BAY

Choose one small area within the existing master module that includes:
- part of the broad armor shell;
- a recessed channel and its rails;
- one transverse bracket connecting the rails;
- the adjacent inner backing surface.

Use the supplied crop as the local visual target.

Do not compress every feature from the entire reference arc into this bay.
Do not add unique platforms, foundations, or major new structures.

4. BUILD THESE FEATURES AS DISTINCT GEOMETRY

A. ARMOR AND ACCESS DETAIL

Create a convincing layered armor assembly:
- a broad curved plate with actual thickness;
- a restrained edge step or narrow border;
- deliberate panel gaps with backing beneath them;
- one small inset access cover;
- one rectangular recessed opening with visible side walls and a backing.

Follow the reference's proportions and placement as closely as possible.
Do not make a uniform grid of tiny tiles.
Do not model all seams as raised strips.

B. MULTI-PART CONNECTION BRACKET

Replace any placeholder block with a recognizable assembly.

Use the crop to guide:
- upper and lower mounting blocks;
- connecting members between them;
- collars, clamp plates, or mounting feet where visibly appropriate;
- a small number of recessed holes or fasteners at actual connections.

Each component must have a clear attachment relationship.
Do not add bolts to every surface.
Do not substitute a single beveled cube for the entire assembly.

C. RECESSED CHANNEL AND RAILS

Make the channel visibly three-dimensional:
- a clear opening;
- side walls or edge lips;
- a recessed backing surface;
- separate curved rail profiles;
- supports that connect the rails to the backing or frame.

The rails must have readable cross-sectional shape,
rather than appearing as several arbitrary parallel lines.

D. INNER BACKING AND LOCAL STRUCTURE

Keep the backing relatively quiet.
Add only the panel boundaries and local reinforcement
needed to support the bracket and channel arrangement.

Do not cover the backing in random boxes or pipes.

5. IMPLEMENTATION REQUIREMENTS

Construct curved parts using the existing ring geometry and local coordinates.
Do not stretch flat boxes across the curve until they intersect the shell.

Keep useful components separately editable and clearly named.

If the current generator only produces continuous strips and equal-width panels,
extend or replace those local geometry-building functions.

Do not limit the work to changing panel counts or adding more edge strips.

Use suitable bevels and shading for the exposed edges.
Check that bevels are actually visible and do not destroy small features.

Do not use increased subdivision, polygon count, or object count
as a substitute for reference-matched parts.

For this benchmark, the main recess, rail profiles, bracket,
and plate thickness must exist as real geometry.

No painted fake structure, weathering, or random displacement.

6. PROVE THE RESULT WITH CLOSE-UP RENDERS

Create two local review cameras:
- an oblique view showing plate thickness, channel depth, and the bracket;
- a complementary view checking the connections and recess depth.

Frame the benchmark so it occupies most of the image.
Render at least 1600 pixels on the long edge.

Use neutral clay material and soft lighting.
Keep cavities readable and avoid excessive ambient occlusion.
Do not use fog, rust, dramatic lighting, or depth of field.

Save BEFORE and AFTER images using identical cameras and lighting.

Also render one wider view showing the detailed bay in the existing module,
so its scale and density can be judged in context.

7. VISUAL ACCEPTANCE

Open and inspect the rendered images.

Check whether:
- the access opening has visible depth;
- armor thickness and stepped edges are readable;
- the bracket is visibly a connected multi-part assembly;
- the rails and backing are spatially separated;
- the result approaches the reference's local structural complexity;
- the detail still belongs to the same ring design.

Do not report completion based only on script execution,
closure tests, or object counts.

If the result still reads as broad panels and a few thin strips,
make one focused correction to the largest remaining difference
before submitting it.

Report any remaining mismatch honestly.

8. STOP POINT

Save the detailed bay in a clearly named collection.

Deliver the updated Blender file, script, close-up renders,
and wider context render.

Stop for visual approval before repeating this detail across the arc
or generating the complete ring.
```

<a id="ref-p08"></a>

## REF-P08 — Shell design and recessed service belt

```text
Create a clean hard-surface concept reference image of a 20-degree sci-fi megastructure ring segment.

IMPORTANT:
This reference is specifically for the OUTER SHELL design of the ring, not the inner rim.

The segment should be shown in a clear three-quarter view, with the OUTER ARMOR SURFACE as the main focus.

Key design requirement:
The outer shell must include a continuous recessed circumferential band running through the middle of the outer surface.
This recessed band should feel engineered and intentional, like a designed structural/service belt, not random damage.

The outer shell should have:
- broad armor panels
- stepped panel offsets
- layered plate relationships
- controlled geometric recesses
- occasional raised or inset structural elements
- clean but articulated hard-surface design
- modular sci-fi megastructure language

The middle recessed band should:
- be clearly visible
- run continuously along the segment
- have defined edges and depth
- create a strong break in the otherwise broad outer shell
- influence the surrounding panel layout

Style:
- clean pale gray / white clay-model presentation
- no rust
- no dirt
- no weathering
- no environment
- neutral light gray background
- soft even studio lighting

Do not focus on the inner ring details.
Do not add random holes or noisy greeble.
Do not make the shell overly smooth.

The result should feel like a refined concept design reference for Blender modeling.
```

<a id="ref-p09"></a>

## REF-P09 — Outer crown and service belt direction

```text
Create an outer-shell design reference based on the two uploaded images.

REFERENCE ROLES

Image 1 is the PRIMARY reference for:
- camera position;
- visible surface;
- segment orientation;
- curvature;
- overall proportions;
- framing.

Image 2 is a SECONDARY reference for:
- industrial armor design;
- layered plates;
- recessed structural zones;
- controlled geometric surface variation.

Do not copy the camera angle from Image 2.
Preserve the exterior viewing direction from Image 1.

TARGET SURFACE

Refine only the OUTER CIRCUMFERENTIAL SURFACE:
the convex crown at the largest radius of the ring.

Think of its location as the tread-facing surface of a tire,
but keep the object entirely architectural and industrial.
Do not introduce rubber, tread patterns, or automotive styling.

Do not move the design onto the concave inner rim.
Do not move it onto the front or rear annular side face.

MAIN DESIGN FEATURE

Create a continuous recessed service channel along the middle
of the convex outer crown.

The channel must:
- follow the ring's circumferential direction from one segment end to the other;
- be centered across the shell's front-to-back axial width;
- separate two broad armor bands on either side;
- descend radially inward below the surrounding outer armor;
- have clearly visible side walls, stepped edge lips, and a recessed floor;
- remain a backed recess, not a hole passing through the whole ring.

Make it read as a substantial continuous structural band,
not a thin panel seam or a row of separate rectangular holes.

Inside the channel, include a restrained arrangement of rails,
mounting brackets, and occasional transverse bridges.
Keep the recessed route visually continuous beneath the bridges.

SURROUNDING ARMOR

Use broad clean plates with selective:
- stepped height changes;
- overlapping edge pieces;
- shallow inset panels;
- geometric notches around structural connections.

The variation must be organized and engineered.
Preserve quiet areas.
Do not add random damage, dense greeble, or uniform holes everywhere.

PRESERVE

Keep the underlying segment envelope, curvature, axial width,
and camera perspective from Image 1.

Allow only the local shell relief and central channel needed
for this outer-surface design.

Do not redesign the inner rim, connection system, or overall ring.

PRESENTATION

One image only.
Clean pale-gray clay-model appearance.
Neutral background and soft directional studio lighting.
Readable recess depth without black painted shadows.
No rust, dirt, decals, fog, text, or multi-view layout.

FINAL CHECK

The image must predominantly show the CONVEX OUTER CROWN,
with two broad armor bands flanking one continuous recessed channel.

Do not return to an inside-the-ring view.
```

<a id="ref-p10"></a>

## REF-P10 — Right platform detail study

```text
Create a detailed hard-surface modeling reference for the RIGHT-SIDE PLATFORM assembly of a sci-fi megastructure ring.

I am providing multiple images with different roles.

IMAGE ROLES

Image A:
Primary blockout reference for the right-side platform.
Use it to preserve the current platform size, orientation, attachment location, support-arm position, and camera framing.

Image B:
Full-ring context reference.
Use it to understand how the platform belongs to the whole ring and to preserve the overall scale relationship and visual context.

Image C:
Design-language reference.
Use it to match the approved ring’s hard-surface vocabulary:
clean armor plates, layered shell logic, restrained geometric cut-ins, believable plate thickness, and a monumental industrial sci-fi feel.

Image D:
Optional platform style cue from the original concept.
Use it only as a secondary shape/style influence for the platform architecture.
Do not override the current blockout position or scale.

TASK GOAL

Refine the RIGHT-SIDE PLATFORM into a more believable, detailed, and visually coherent industrial attachment,
while preserving its current placement and general proportions.

This is not a redesign of the ring.
This is not a redesign of the whole scene.
This is a focused design refinement of one platform assembly.

ASSET SCOPE

Show:
- one complete right-side platform
- its mounting root
- the diagonal support arm
- a short adjacent portion of the ring for context

Do not include:
- the full left platform
- the suspended central platform
- the base/foundation
- environment, landscape, or background scene elements

STRUCTURAL GOALS

The platform should feel like a real attached industrial structure.

Develop:
1. a strong mounting root where the platform meets the ring
2. a readable deck with real thickness
3. underside support structure
4. a meaningful diagonal brace / support arm
5. layered transitions between the ring shell and the platform
6. a believable load path from deck to support to ring

DETAIL LANGUAGE

The platform should visually match the ring.

Use:
- broad clean surfaces
- stepped panel offsets
- layered plate relationships
- selected recessed maintenance zones
- restrained geometric cut-ins
- underside reinforcement
- a small number of equipment masses or structural housings where appropriate

Do NOT:
- overfill the platform with tiny greebles
- add random pipes everywhere
- make it look like a spaceship wing
- make it look like a building rooftop
- add railings everywhere unless they clearly help the design
- create chaotic noise or damage

SHAPE CONTROL

Preserve the current general platform size and silhouette from Image A.
Do not drastically enlarge or shrink it.
Do not move the platform to a different clock position on the ring.

The deck should remain mostly horizontal.
The support arm should remain structurally believable.
The attachment to the ring should feel intentional and engineered.

PRESENTATION

Generate one clean concept reference image only.

View:
- similar to the current close-up / three-quarter platform view
- platform clearly readable
- mounting interface clearly visible

Style:
- pale gray / white clay-model presentation
- neutral gray background
- soft even studio lighting
- no rust
- no dirt
- no weathering
- no text labels
- no exploded view
- no blueprint layout

PURPOSE

This image is intended as a Blender modeling reference.

Prioritize:
- clear construction logic
- readable major parts
- believable structural hierarchy
- compatibility with the approved ring design language

The result should look like a refined industrial side platform attached to a giant sci-fi ring megastructure.
```

<a id="ref-p11"></a>

## REF-P11 — Restore the platform silhouette

```text
Create a revised detailed modeling reference for the RIGHT-SIDE PLATFORM assembly.

IMPORTANT REFERENCE PRIORITY

Image A:
This is the current blockout / white-model placement reference.
Use it ONLY for:
- platform position on the ring
- approximate scale
- general deck orientation
- support-arm placement
- mounting location
- camera/view framing

Do NOT use Image A as the main reference for the platform’s final shape language,
architectural style, or detailed structural design.

Image B:
This is the original concept / original design reference.
Use Image B as the PRIMARY reference for:
- platform shape
- platform silhouette
- structural character
- industrial design language
- architectural massing
- edge treatment
- overall visual identity

Image C:
This is the approved ring detail-language reference.
Use it to keep the platform consistent with the ring’s hard-surface design language,
panel treatment, plate thickness, and overall industrial sci-fi feel.

TASK GOAL

Redesign the right-side platform so it matches the original concept language much more closely,
while keeping the CURRENT approved placement from the blockout.

In short:
- keep the current placement from the white model
- recover the platform design language from the original concept

CRITICAL INSTRUCTION

The white-model blockout is NOT the final design reference for shape.
It only defines WHERE the platform sits, not WHAT the platform looks like.

Do not simply add detail on top of the blockout slab.
Do not preserve the blockout’s plain rectangular deck shape unless the original concept clearly supports it.
Do not let the blockout override the concept design.

DESIGN INTENT

The final platform should feel visually closer to the original concept:
- stronger architectural character
- more recognizable silhouette
- more intentional platform massing
- more concept-faithful structure
- more resemblance to the original side attachment

Keep the result consistent with the approved ring,
but let the original concept guide the actual platform design.

PRESERVE FROM THE BLOCKOUT

Preserve only:
- attachment location on the ring
- approximate clock position
- general scale
- the fact that this is a side-mounted platform
- the approximate direction of the support arm
- the approximate viewing angle

ALLOW TO CHANGE

You may redesign:
- deck outline
- edge profile
- underside structure
- platform thickness distribution
- support geometry
- mounting-root form
- superstructure volumes on the deck
- structural layering
- the transition between ring and platform

Do this as needed to better match the original concept.

SHAPE GUIDANCE

The platform should not read as a generic rectangular slab.
It should feel like a purpose-built megastructure attachment.
Use the original concept to recover the intended visual identity.

Avoid:
- overly boxy slab-like deck design
- arbitrary rooftop-like equipment placement
- excessive small greeble noise
- making the platform look like a random industrial balcony
- simply detailing the blockout without rethinking its form

PRESENTATION

Output one clean concept reference image.

Show:
- the complete right-side platform
- the mounting region
- the support arm
- a short portion of the ring for context

Style:
- pale-gray / white clay model
- neutral background
- soft studio lighting
- no environment
- no text
- no blueprint sheet

FINAL CHECK

Before finalizing, ensure that:
1. the platform placement still follows the blockout
2. the platform’s actual design language follows the original concept
3. the result does NOT look like “the white-model blockout plus extra detail”

This should look like the ORIGINAL platform design translated into the approved ring system.

If there is any conflict between the blockout image and the original concept image,
follow the blockout for placement only,
but follow the original concept for form, silhouette, and design language.
```

<a id="ref-p12"></a>

## REF-P12 — Wraparound collars and diagonal braces

```text
Create a refined hard-surface modeling reference for the RIGHT-SIDE PLATFORM ATTACHMENT SYSTEM of a giant sci-fi ring megastructure.

REFERENCE ROLES

Image A:
Annotated correction reference.
Use it to identify the problem areas that must be redesigned:
- the upper attachment block
- the lower attachment block
- the relationship between the main outer platform and the inner secondary platform

Image B:
Current clean close-up reference.
Use it for the approved placement, approximate scale, camera angle, and the current general location of the platform system on the ring.

Image C:
Full-ring context reference.
Use it to preserve the platform’s overall position and scale relationship to the ring.

Image D:
Original concept / original design cue.
Use it as the main stylistic and structural inspiration for the platform system.
This image should guide the intended design language more than the blockout does.

IMPORTANT PRIORITY

Use the current blockout and close-up images only for:
- placement
- approximate scale
- orientation
- mounting zone
- camera framing

Use the original concept as the primary guide for:
- platform shape
- structural character
- silhouette
- mounting style
- industrial language
- attachment logic

TASK GOAL

Redesign the RIGHT-SIDE PLATFORM as a more coherent attachment system.

The result should include:

1. Main outer platform
- the larger outer deck/platform
- believable structural thickness
- clearer underside support
- a more intentional architectural silhouette

2. Secondary inner platform
- a smaller inner / lower service platform
- clearly related to the main platform
- integrated into the same attachment system
- not an isolated random box

3. Upper attachment point
- redesign it so it CLAMPS / WRAPS around the ring
- it should feel like a curved mounting collar or saddle
- it should conform to the ring curvature instead of reading as a flat box pasted on the shell

4. Lower attachment point
- also redesign it as a ring-clamping or ring-hugging support block
- it should visually grip or embrace the curvature of the ring
- it should provide a strong structural landing point for the diagonal brace

5. Diagonal support arm
- keep the general support-arm logic
- redesign it to connect more naturally between the lower clamping support and the main platform system
- it should feel engineered, not improvised

STRUCTURAL INTENT

The whole assembly should read as one coherent platform system:
- main outer platform
- inner secondary platform
- upper clamp mount
- lower clamp mount
- diagonal brace
- shared structural logic

These elements should feel designed together, not added separately.

DESIGN LANGUAGE

Match the monumental industrial sci-fi language of the approved ring:
- clean white / pale-gray clay-model presentation
- layered hard-surface armor logic
- selective recessed panels
- readable plate thickness
- structural clarity
- restrained fine detail

Avoid:
- random clutter
- noisy greebles
- simple rectangular blocks pasted onto the ring
- generic balcony-like structures
- support blocks with flat interfaces that ignore the ring curvature

CLAMPING REQUIREMENT

The upper and lower support blocks must visibly follow the curvature of the ring.
They should look like they are gripping, hugging, or saddling the ring body.

Do not leave them as flat rectangular boxes attached to a curved surface.

PRESENTATION

Generate one clean reference image only.

Show:
- the complete right-side platform system
- the main outer platform
- the inner secondary platform
- the upper and lower clamp-like supports
- the diagonal brace
- a short section of the ring for context

Use a three-quarter close-up view similar to the current close-up image.

Style:
- clay render
- neutral gray background
- soft studio lighting
- no rust
- no dirt
- no labels
- no environment
- no blueprint sheet

PURPOSE

This is a structural design reference for Blender modeling.
Prioritize coherent attachment logic and concept-faithful platform architecture.
```

<a id="ref-p13"></a>

## REF-P13 — Inner platform design scope

```text
Create a design reference for the RIGHT-SIDE INNER AUXILIARY PLATFORM
of the existing ring megastructure.

This is a new inward-projecting attachment.
The existing ring and approved outer platform are not redesign targets.

REFERENCE ROLES

Image A — PLACEMENT AND CAMERA
Use this image for:
- the current ring geometry and proportions;
- the right-side attachment location;
- the available space inside the opening;
- the camera direction and framing;
- the position of the existing outer platform.

Image A defines WHERE the new attachment belongs.
It does not define the new platform's final shape.

Image B — PRIMARY INNER-PLATFORM DESIGN
Use the original inward-projecting platform as the primary guide for:
- silhouette;
- relative size;
- deck shape;
- structural layering;
- underside massing;
- architectural character.

Do not confuse this element with a service pod below the outer platform.

Image C — APPROVED CONSTRUCTION LANGUAGE
Use the finished outer platform to match:
- plate thickness and stepped edges;
- framed recesses;
- mounting and connection details;
- equipment-housing style;
- the clean industrial hard-surface treatment.

Do not copy the entire outer platform inward.
Do not redesign the approved outer platform.

SPATIAL DEFINITION — CRITICAL

The new platform attaches to the INNER EDGE of the RIGHT-HAND side
of the ring and projects radially toward the central opening.

In a near-front view:
- the central opening is to the LEFT of the right-hand ring segment;
- the existing outer platform extends to the RIGHT;
- the new inner platform extends to the LEFT, into the open aperture.

The new platform must visibly cross the inner boundary of the ring
and project into empty space.

It is NOT:
- a lower equipment pod;
- an attachment on the rear face;
- a second outward-facing platform;
- the suspended platform hanging from the top;
- a bridge spanning the opening.

DESIGN GOAL

Develop one smaller, subordinate inner service platform that belongs
to the same attachment system as the approved outer platform.

Follow Image B for its recognizable form.
Use Image C for construction quality and local detailing.

Include:
- a layered deck with readable thickness;
- a clear perimeter frame;
- an underside support assembly;
- a mounting root fitted to the existing inner attachment zone;
- selected service panels or equipment only where appropriate.

Keep broad quiet surfaces.
The inner platform should have the same quality of construction as
the outer platform, but fewer elements and a smaller overall presence.

Do not turn it into a plain slab.
Do not fill the deck with identical equipment boxes.
Do not add new large towers, antenna clusters, or random machinery.

PLACEMENT AND CONNECTION

Keep the deck horizontal relative to the installed ring's gravity direction.

Place it near the right-side horizontal centerline,
with its precise silhouette and any small elevation offset guided by Image B.

Keep the platform subordinate to the existing outer platform.
Preserve the large open center of the ring.

Integrate the mounting root with the existing local attachment system
where possible, using a dedicated inward-facing adapter or support.

Do not erase the ring's service channels.
Do not alter the approved outer-platform clamps, rounded brace joint,
small masts, or main equipment arrangement.

Do not invent an enormous support crossing the aperture or reaching the ground.

CAMERA AND COMPOSITION

Use the near-front, slightly elevated three-quarter direction from Image A.

Show:
- the entire new inner platform;
- its mounting root;
- enough of the ring's inner edge to establish the connection;
- a recognizable part of the approved outer assembly as context.

Keep the central opening visible behind and beside the new platform.
Do not hide the new design behind the ring body.

PRESENTATION

Output ONE clean design-reference image.

Use:
- pale-gray clay-model appearance;
- neutral background;
- soft lighting that reveals thickness and recess depth;
- clear, connected structural parts.

No weathering, rust, colored textures, fog, dramatic effects,
text labels, exploded diagram, or multi-view sheet.

FINAL REQUIREMENT

The image must clearly communicate:
one existing outer platform projecting outward,
and one smaller NEW inner platform projecting into the ring opening.

Preserve the approved existing design.
Develop only the new inner attachment and its local connection.

This is a visual design reference for later Blender modeling,
not a dimensionally certified engineering drawing.
```

<a id="ref-p14"></a>

## REF-P14 — Isolated inner platform

```text
Create a standalone design reference for ONE INNER PLATFORM
attached to the right-hand side of the ring megastructure.

This is an asset-design task, not a full assembly redraw.

IMAGE 1 — PRIMARY FORM REFERENCE

Use the wider, lower platform projecting into the ring opening
as the subject to develop.

Preserve its recognizable:
- compact silhouette;
- layered deck and edge structure;
- close integration with the ring;
- stepped underside massing;
- restrained industrial detail.

The smaller projection above it is surrounding context,
not an instruction to add another platform.

The crop is limited in resolution.
Clarify its visible design rather than inventing a different architecture.
Do not claim to recover exact hidden geometry.

IMAGE 2 — INSTALLATION REFERENCE ONLY

Use this image only for:
- the actual ring curvature and mounting zone;
- the direction of the central opening;
- available attachment space;
- platform orientation and approximate scale.

It does NOT define the platform's final shape or detail level.
Do not inherit simplified placeholder geometry as the finished design.

OUTPUT SCOPE

Show only:
- the new inner platform;
- its mounting root;
- its underside support;
- a narrow fragment of the ring at the connection.

Do not show or regenerate the existing outer platform.
Do not show the complete ring or the complete attachment system.

The approved outer platform will remain unchanged in Blender.
It does not need to be reproduced in this image.

SPATIAL RELATIONSHIP

This platform belongs to the RIGHT-HAND ring structure
and projects radially INWARD into the central aperture.

For this reference view:
- place the ring connection on the right;
- let the platform extend toward the left into open space;
- keep the deck horizontal.

It is not a pod beneath the outer platform,
not an attachment on the rear face,
and not a second outward-facing balcony.

DESIGN DIRECTION

Follow Image 1's form instead of making a miniature copy
of the completed outer platform.

The platform should read as a compact architectural attachment:
- a layered, substantial deck;
- thick perimeter beams;
- a mounting root integrated with the ring;
- a stepped underside that narrows into a supporting structure;
- selected recessed panels and framed service openings.

Keep the equipment subordinate to the architecture.
Concentrate any necessary equipment near the mounting root.
Do not make a tall freestanding ventilation box the main feature.

Use railings sparingly where they support the reference design.
Do not automatically repeat the outer platform's masts,
rooftop equipment, and lower hanging pod.

Maintain broad clean surfaces, but preserve precise construction:
visible plate thickness, controlled bevels, narrow joints,
recessed interfaces, and readable supporting members.

Avoid:
- a generic rectangular balcony;
- an empty slab with one oversized equipment box;
- chunky rounded toy-like forms;
- random machinery;
- excessive panel fragmentation;
- a uniformly scaled-down outer platform.

PRESENTATION

Produce one exterior three-quarter asset view,
showing the deck, mounting root, and part of the underside.

The inner platform should occupy most of the frame.
Use pale-gray clay material, a neutral background,
and soft lighting that reveals depth without washing out details.

No text, environment, weathering, exploded diagram,
or multi-view sheet.

SUCCESS CRITERION

The output should look like the original INNER PLATFORM design
clarified into a usable modeling reference,
not a simplified version of the current outer platform.

Do not include the outer platform anywhere in the output.
```

<a id="ref-p15"></a>

## REF-P15 — Inner platform structural weight

```text
Generate a clean high-resolution white-model concept reference of the INNER PLATFORM attached to the megastructure ring.

REFERENCE PRIORITY:
- Image A is the primary design authority for the platform's silhouette, massing, proportions, and style.
- Image B is only for placement and mounting position on the ring.
- Image C, if provided, is a negative example showing what NOT to do.

TASK:
Reconstruct the inner platform so that it closely matches the silhouette and heavy industrial shape language of Image A.

IMPORTANT DESIGN GOALS:
- The platform must feel thick, heavy, and integrated into the megastructure.
- It should not look like a thin catwalk, scaffold balcony, or lightweight maintenance deck.
- The outer contour should match the reference image as closely as possible.
- The massing should be broader and more substantial.
- The body should feel like a compact industrial service module projecting from the ring interior.

REQUIRED FORM CHARACTERISTICS:
- Strong, blocky, weighty silhouette.
- A thicker deck/body profile.
- More enclosed and architectural than a simple railing platform.
- Layered industrial side surfaces with structured geometric detail.
- The platform should visually connect into the ring as a built-in megastructure component.
- The top silhouette should remain controlled and believable.
- Detail density should be significantly higher than the current rough version.

DO NOT:
- Do not redesign it as a generic balcony.
- Do not make it thin or fragile.
- Do not add a vertical support pillar under the platform.
- Do not invent a different silhouette from the original reference.
- Do not overuse simple railings as the dominant visual language.
- Do not make the bottom structure rely on a central support post.

VISUAL STYLE:
- clean white-model / clay-render style
- realistic hard-surface sci-fi industrial design
- sharp but believable paneling
- clear secondary and tertiary forms
- subtle geometric complexity
- no rust, no texture weathering, no color materials

CAMERA:
Show a close three-quarter view that clearly presents:
- the platform silhouette
- its connection to the ring
- the underside massing
- the top deck structure
- the front and side profiles

The result should be a strong modeling reference image suitable for Blender reconstruction.
```

<a id="ref-p16"></a>

## REF-P16 — Inner platform near-front view

```text
Generate a front-facing reference image of the inner platform attached to the megastructure ring.

IMPORTANT:
This is NOT a redesign task.
The goal is to create a clean modeling reference image for Blender/Codex.

Use the approved side-perspective reference as the main design authority for the platform's shape language, silhouette, massing, and detail style.
Use the white model / placement reference only to confirm the installation position on the inner side of the ring.

Requirements:
- show the platform from a near-front view, facing the platform facade as directly as possible
- reduce perspective distortion; the image should read like a modeling reference, not a cinematic shot
- preserve the heavy industrial sci-fi shape language from the approved reference
- keep the platform thick, substantial, and weighty
- preserve the layered front fascia, framed paneling, underside support mass, and upper boxy equipment
- the platform should cantilever from the inner side of the ring
- do not add thin catwalk proportions
- do not make it too light or too skeletal
- keep the silhouette bold and blocky
- include visible railing, upper equipment boxes, front frame divisions, and underside structural mass
- show enough of the ring behind it to understand the connection point, but keep the platform as the main subject
- clean white clay render
- neutral gray background
- high clarity, sharp forms, readable hard-surface detail

Very important:
Match the approved reference image's overall outline and architectural character.
Do not invent a completely new platform design.
```

<a id="ref-p17"></a>

## REF-P17 — Symmetric front elevation

```text
Generate a strict front-elevation reference image of the inner platform attached to the megastructure ring.

IMPORTANT:
This is NOT a cinematic concept render.
This is NOT a redesign task.
This image is for Blender/Codex modeling reference.

Primary goal:
Create a near-orthographic front reference of the platform with strict bilateral symmetry.

Use instructions:
- Use the approved perspective platform reference as the main authority for shape language, silhouette, massing, and detail style.
- Use the white model / placement reference only to determine where the platform attaches to the inner side of the ring.
- Do NOT invent a new platform design.

Camera and composition requirements:
- camera centered exactly in front of the platform facade
- optical axis perpendicular to the platform front face
- near-orthographic view
- minimal perspective distortion
- platform centered in the image
- left and right sides must be symmetrical
- keep the front elevation flat and readable
- avoid angled cinematic composition
- avoid 3/4 view
- avoid tilted framing

Design requirements:
- preserve the heavy industrial sci-fi style from the approved reference
- platform should feel thick, substantial, and weighty
- keep a bold and blocky silhouette
- preserve the layered front fascia, railing, upper equipment boxes, and underside structural mass
- show enough of the ring behind it to understand the mounting position, but the platform must remain the main subject

Symmetry requirements:
- strict bilateral symmetry across the vertical centerline
- left and right railings aligned
- left and right edge thickness aligned
- left and right facade massing aligned
- do not let one side protrude or tilt more than the other

Rendering requirements:
- clean white clay render
- neutral gray background
- high clarity
- hard-surface readability
- suitable as modeling reference

Avoid:
- perspective-heavy view
- off-center composition
- asymmetrical railing placement
- asymmetrical facade blocks
- concept-art camera angle
- dramatic lens distortion
- redesigning the platform into a different silhouette
```

<a id="ref-p18"></a>

## REF-P18 — Repair the central portal frame

```text
Edit the existing front orthographic reference image.

IMPORTANT:
Preserve the current orthographic camera, bilateral symmetry, platform proportions,
front facade, railings, underside structure, ring geometry, and all existing details.

Do NOT redesign the platform.
Do NOT change the camera angle.
Do NOT change the existing platform silhouette.

Only add back the missing large PORTAL FRAME shown in the secondary reference.

The missing structure should be a heavy rectangular industrial gantry / portal frame
positioned directly behind the central platform deck.

Use the secondary reference only for the shape and construction of this portal frame.

PORTAL FRAME REQUIREMENTS:

- centered exactly on the platform vertical centerline
- strictly bilaterally symmetrical
- one thick horizontal top beam
- two substantial side supports
- the inner edges of the side supports should angle inward / step inward,
  similar to the approved perspective reference
- create a deep recessed opening inside the frame
- the structure should feel thick, heavy, architectural, and integrated into the ring
- preserve the layered hard-surface sci-fi construction language
- use broad clean surfaces with restrained panel seams and secondary framing
- the portal should visually rise behind the railing, not replace the railing

The portal frame should NOT be:
- a curved arch
- a thin railing frame
- a lightweight scaffold
- a generic doorway
- asymmetrical
- tilted
- offset from the platform center

CAMERA / PRESENTATION:

- strict front elevation
- near-orthographic / orthographic appearance
- optical axis perpendicular to the platform front face
- platform centered
- vertical centerline perfectly aligned
- no 3/4 perspective
- no cinematic tilt

SYMMETRY:

The left and right halves of the portal frame must mirror each other exactly.
Keep the existing platform symmetry unchanged.

STYLE:

clean white clay model
neutral gray background
same lighting and material as the current orthographic image
no rust, no weathering, no color changes

FINAL GOAL:

Return the current approved front orthographic platform image,
but with the large central rectangular portal/gantry structure restored
to match the approved perspective reference.
Everything outside that missing portal-frame area should remain unchanged.

This is a LOCAL CORRECTION, not a regeneration.
Do not alter any approved geometry outside the missing central portal-frame area.
```

<a id="ref-p19"></a>

## REF-P19 — Inner platform side elevation

```text
Generate a strict SIDE ORTHOGRAPHIC modeling reference of the exact same inner platform shown in Image A.

IMPORTANT:
Image A is the LOCKED PRIMARY DESIGN.
Preserve its architecture, proportions, symmetry, portal frame, front fascia,
railings, equipment layout, and overall visual identity.

Image B is only a secondary depth and construction reference.
Use it to clarify projection depth, underside massing, and mounting-root depth.
Do not redesign the platform to match Image B.

This is NOT a new concept design.
This is a technical modeling reference for Blender/Codex.

CAMERA

Create a true side elevation of the platform.

Use an orthographic or near-perfect orthographic camera.
The optical axis must be perpendicular to the platform side plane.

No three-quarter view.
No cinematic perspective.
No camera tilt.
No perspective exaggeration.

The platform should be horizontally aligned and fully visible.

PRESERVE

Keep exactly:
- the heavy platform body
- the thick layered deck
- the approved front-edge architecture
- the central portal-frame system
- the railing height
- the equipment proportions
- the overall visual weight

Do not simplify the model.

SIDE-VIEW INFORMATION TO CLARIFY

Clearly show:
- the total platform projection from the ring
- deck thickness
- layered underside construction
- underside beams and recessed structural zones
- portal-frame depth
- equipment depth
- mounting-root thickness
- transition from platform body into the ring structure

The platform must remain cantilevered and integrated into the ring.

Do NOT add:
- vertical support columns under the platform
- long diagonal ground supports
- new large attachments
- a different portal frame
- a thinner catwalk-like structure

GEOMETRIC CONSISTENCY

The side view must describe the SAME platform as Image A.

Do not change the front design because it is not visible from this angle.
Do not invent a new silhouette.

If hidden geometry is ambiguous, use the simplest structurally plausible
solution consistent with Image A and Image B.

PRESENTATION

clean white / pale-gray clay model
neutral gray background
soft even studio lighting
high structural readability
no rust
no weathering
no text
no blueprint labels

FINAL GOAL

Produce one clean orthographic SIDE ELEVATION suitable for reconstructing
the platform depth and underside geometry accurately in Blender.
```

<a id="ref-p20"></a>

## REF-P20 — Inner platform plan

```text
Generate a strict TOP ORTHOGRAPHIC modeling reference of the exact same platform defined by Images A and B.

REFERENCE AUTHORITY

Image A defines:
- platform width
- bilateral symmetry
- front-face structure
- portal-frame width
- equipment spacing

Image B defines:
- platform projection depth
- mounting-root depth
- deck thickness relationship
- longitudinal proportions

Do not redesign either dimension.

This is a technical top-view modeling reference,
not a new concept-art interpretation.

CAMERA

Use a true top orthographic view.

Camera optical axis must be perpendicular to the horizontal deck plane.

No perspective distortion.
No three-quarter view.
No camera tilt.
No cinematic framing.

Center the platform on its longitudinal centerline.

SYMMETRY

Maintain strict bilateral symmetry across the platform centerline.

The left and right halves of the platform footprint must mirror each other
unless a clearly approved centered feature requires otherwise.

Do not introduce random asymmetrical equipment placement.

SHOW CLEARLY

- complete deck footprint
- platform width
- projection depth from the ring
- mounting-root footprint
- portal-frame footprint
- railing layout
- major equipment footprints
- perimeter beam thickness
- main panel divisions

Keep the central deck area relatively clean.

Do not fill the deck with additional machinery.

PRESERVE

The top view must describe the SAME platform as Images A and B.

Do not:
- widen or narrow the platform
- change its projection depth
- relocate the portal frame
- change the equipment scale
- alter the approved mounting position
- add new support systems

PRESENTATION

clean white clay model
neutral gray background
soft even lighting
no rust
no weathering
no labels
no environment

FINAL GOAL

Produce one clean TOP ORTHOGRAPHIC reference suitable for reconstructing
the exact footprint and layout in Blender.
```

<a id="ref-p21"></a>

## REF-P21 — Upper suspension elevation

```text
Use the provided images as references.

REFERENCE PRIORITY
- The close-up hanging platform image is the PRIMARY and AUTHORITATIVE design reference for the suspended assembly.
- The full ring image is only a SECONDARY spatial reference for placement and scale within the ring.
- Do not redesign the hanging assembly. Reconstruct it faithfully.

TASK
Generate a clean front orthographic reference image of the suspended central platform assembly attached to the ring.

CAMERA
- true front orthographic view
- no perspective distortion
- camera centered on the hanging assembly
- symmetrical composition
- neutral studio background
- technical reference style
- high clarity, clean white model / clay render look

INCLUDE
- the upper ring segment around the mounting area
- the full top mounting/clamp structure
- both vertical suspension rods
- the entire lower suspended platform
- enough surrounding ring geometry to clearly show how the top structure is attached

IMPORTANT DESIGN REQUIREMENTS
1. The top mounting structure must wrap around the ring body, not merely attach to the outer edge.
2. The upper structure should read like a deep clamp or encircling mechanical housing integrated into the ring thickness.
3. Keep the two suspension rods clearly separated left and right, vertical, and aligned with the lower platform.
4. Preserve the lower platform silhouette as closely as possible to the primary reference.
5. The underside protruding central mass below the platform must be trapezoidal / tapered, not a plain box.
6. Maintain the heavy industrial sci-fi megastructure feel.
7. Keep the design thick, solid, and mechanically believable.
8. Keep the model symmetrical in the front view.

DO NOT
- do not redesign the shape
- do not simplify the mount into a shallow bracket
- do not change the rod placement
- do not turn the underside protrusion into a rectangular box
- do not stylize
- do not add random extra platforms or supports
- do not use perspective

OUTPUT
A precise front orthographic modeling reference suitable for Blender reconstruction.
```

<a id="ref-p22"></a>

## REF-P22 — Initial rod rotation attempt

```text
Use the provided orthographic hanging-platform reference image as the base.

Edit only the two suspension rods.

Requirements:
1. Keep the ring, top mount, lower suspended platform, and overall composition unchanged.
2. Keep the rod attachment points, spacing, height, and length unchanged.
3. Rotate both suspension rods 90 degrees around their own vertical axis.
4. The rods currently face the wrong direction; correct their cross-section orientation so they match the intended reference.
5. Preserve full left-right symmetry.
6. Do not redesign any other part.
7. Keep this as a clean front orthographic white-model technical reference.

Output:
A corrected front orthographic reference image with the two suspension rods rotated 90 degrees in orientation only.
```

<a id="ref-p23"></a>

## REF-P23 — Correct front and rear rod placement

```text
CORRECTION TO THE SUSPENSION SYSTEM

The current suspension-rod arrangement is incorrect.

This is NOT a rod-orientation problem.
Do NOT simply rotate each rod in place.

The two suspension rods must be arranged along the AXIAL DEPTH of the ring,
meaning one rod is on the near/front side of the ring thickness
and the other rod is on the far/rear side.

SPATIAL DEFINITION

Use the existing ring coordinate system.

Define:
- ring plane = the plane of the large circular opening
- axial direction = perpendicular to the ring plane,
  running through the front-to-back thickness of the ring

The two suspension rods should:

- share approximately the same position when projected into the ring plane
- have the same vertical centerline in the FRONT orthographic view
- differ primarily in their axial/depth position
- be placed symmetrically on opposite sides of the ring's axial center plane

In other words:

ROD A = front / near-side suspension rod
ROD B = rear / far-side suspension rod

They must NOT be positioned left and right across the ring opening.

FRONT-VIEW REQUIREMENT

From a true front orthographic camera looking perpendicular to the ring plane:

- the two rods should visually overlap
- they should project onto approximately the same vertical line
- the viewer should therefore see only one apparent rod silhouette,
  except for any very small depth-related edge visibility

This overlap is intentional.

SIDE-VIEW REQUIREMENT

From a true side orthographic view:

- both rods must become clearly visible
- one should be located toward the front face of the ring
- one should be located toward the rear face
- their front-to-back separation should correspond to the ring thickness
  and the suspension mounting design

TOP MOUNT

Update the upper mounting assembly accordingly.

The upper mount should provide:
- one front suspension attachment point
- one rear suspension attachment point

These attachment points should belong to the same central hanging assembly
and remain symmetric around the ring's axial center plane.

Do not place the two suspension points left and right in the front elevation.

LOWER PLATFORM

Update the lower suspended platform attachment points accordingly.

The platform should receive:
- one suspension connection near its front side
- one suspension connection near its rear side

The two connections should be aligned in the front orthographic projection.

Do not change the approved lower platform silhouette unnecessarily.

PRESERVE

Keep unchanged:
- suspension length
- platform vertical position
- overall upper mounting position
- lower platform design
- ring geometry
- existing approved proportions

Only correct the front/back suspension layout and any mounting geometry
required to support that layout.

VALIDATION

After correction, render:

1. TRUE FRONT ORTHOGRAPHIC VIEW
   - the two suspension rods should overlap and appear approximately as one

2. TRUE SIDE ORTHOGRAPHIC VIEW
   - the two rods should be clearly separated front-to-back

3. THREE-QUARTER VIEW
   - both rods should become partially readable as two separate members

4. TOP ORTHOGRAPHIC VIEW
   - clearly show the front/rear spacing of the two rods

Do not report completion unless these four views confirm the intended geometry.

This correction is about AXIAL POSITION, not simply rotating the rod mesh.

In the front orthographic view, the two rods must overlap in projection and appear as approximately ONE rod.
In the side orthographic view, they must appear as TWO rods separated along the ring's front-to-back thickness.
```

<a id="ref-p24"></a>

## REF-P24 — Suspension assembly four views

```text
Generate a clean isolated orthographic reference sheet of a suspended sci-fi hanging module in a white clay model style.

Subject:
Only the hanging assembly should be shown, isolated from the large ring as much as possible.
The subject includes:
1. the upper mounting / clamp structure,
2. two vertical suspension rods,
3. the lower suspended platform.

Important:
The large circular ring should NOT dominate the image and should NOT block the assembly.
If necessary, include only a minimal mounting interface or a very small portion of the ring connection area for context, but keep the hanging module visually isolated and fully readable.

Critical structural requirements:
- The whole hanging module must be strictly LEFT-RIGHT SYMMETRICAL.
- No asymmetrical protrusions.
- No extra block sticking out on only one side.
- No bottom latch or clamp protruding only from one side.
- The upper mounting structure must be centered.
- The lower platform must also be centered and symmetrical.

Suspension rod logic:
- There are TWO vertical rods.
- They are arranged FRONT and REAR along the ring thickness direction, not left and right.
- In the true FRONT orthographic view, the two rods should overlap in projection and appear approximately as ONE rod.
- In the true SIDE orthographic view, both rods must be clearly visible as two separate rods.
- In the true TOP orthographic view, the front / rear spacing of the two rods must be visible.

Design requirements:
- The upper mounting structure should feel heavy, mechanical, architectural, and integrated.
- It should look like it wraps / grips the ring connection zone in a robust way.
- The lower platform should keep the approved silhouette: heavy rectangular deck, mechanical edge framing, and a distinct trapezoidal protruding mass underneath.
- The bottom central protrusion should be trapezoidal / beveled, not random.
- The overall design language should match a large-scale industrial sci-fi megastructure.
- Clean paneling, layered hard-surface geometry, and controlled mechanical detailing.
- No random greeble noise.
- No delicate thin support legs underneath the platform.
- No unnecessary decorative asymmetry.

Output layout:
Create a 4-view reference sheet:
1. FRONT ORTHOGRAPHIC VIEW
2. SIDE ORTHOGRAPHIC VIEW
3. TOP ORTHOGRAPHIC VIEW
4. THREE-QUARTER VIEW

Camera / presentation:
- true orthographic for front / side / top views
- no perspective distortion in orthographic views
- centered composition
- neutral gray background
- white clay render
- crisp modeling reference quality
- highly readable silhouettes
- industrial design presentation

Most important:
This sheet is for modeling reference.
Clarity, symmetry, and structural correctness are more important than cinematic atmosphere.
```

<a id="ref-p25"></a>

## REF-P25 — Lower support close-up

```text
Use Image A as the overall position and proportion reference, and Image B as the detailed shape reference for the lower support structure.

Generate a highly detailed close-up reference image of the bottom support assembly of the ring structure.

Focus only on the lower support area:
- the two large diagonal support struts on both sides
- the central vertical support/pedestal
- the base platform and ground foundation
- the structural connection between the ring and the supports
- the structural connection between the supports and the ground base

Important requirements:
- match the design language of the reference as closely as possible
- preserve the overall position and proportion seen in Image A
- preserve the detailed silhouette and mechanical feeling seen in Image B
- the two side supports should feel heavy, engineered, and mechanically believable
- emphasize layered industrial geometry, panel blocks, reinforcement forms, connection housings, and support interfaces
- do not redesign freely
- do not simplify into plain blocks
- do not invent unrelated sci-fi shapes

Visual style:
- clean hard-surface sci-fi industrial design
- neutral clay render / white model
- soft studio lighting
- high clarity
- no dramatic composition
- no extra environment distractions

Camera:
- medium close-up three-quarter view
- frame the entire bottom support assembly clearly
- keep enough of the ring visible to show how the supports attach to it
```

<a id="ref-p26"></a>

## REF-P26 — Lower support four views

```text
Use Image A as the overall position and proportion reference, and Image B as the detailed shape reference for the lower support structure.

Generate an orthographic reference sheet for the bottom support assembly of the ring structure.

Show the lower support system in multiple clean reference views:
1. front orthographic view
2. side orthographic view
3. top orthographic view
4. three-quarter reference view

The support system must include:
- the ring lower section around the attachment area
- the two large diagonal supports
- the central vertical support/pedestal
- the ground base / stepped platform / foundation modules

Important:
- keep the structure symmetrical where appropriate
- preserve the support angle and proportion from the reference
- do not redesign the support system
- do not simplify the main silhouette
- clearly show how the supports connect to both the ring and the ground base
- the base should feel layered, heavy, and industrial
- the side braces should feel robust and mechanically integrated

Visual style:
- neutral clay render
- technical concept-sheet look
- clean background
- high readability
- no perspective distortion in orthographic views
```

<a id="ref-p27"></a>

## REF-P27 — Upper brace joint

```text
Use Image A as the global reference and Image B as the detailed lower-support reference.

Generate a close-up detailed reference image of the upper connection area between the ring and the lower support brace.

Focus on:
- how the diagonal support attaches into the ring structure
- the outer mechanical housing around the joint
- the layered hard-surface geometry
- the thickness, silhouette, and load-bearing feeling of the connection block

Requirements:
- preserve the shape language of the reference
- do not redesign the joint
- emphasize structural realism and mechanical integration
- show clear layered forms, support housings, reinforcement blocks, and surface breaks
- avoid random greeble
- keep it consistent with the ring design language

Visual style:
- neutral clay render
- high-detail close-up
- clean lighting
- easy-to-read mechanical forms
```

<a id="ref-p28"></a>

## REF-P28 — Lower brace joint

```text
Use Image A as the overall position reference and Image B as the lower support detail reference.

Generate a detailed close-up reference image of the lower connection between the diagonal support brace and the ground base.

Focus on:
- the foot of the diagonal support
- the connection housing / hinge / mounting block
- the stepped platform and base layers
- secondary supporting structural forms around the foot
- the mechanical load-bearing feeling

Requirements:
- match the reference design language closely
- keep the support foot heavy and engineered
- preserve the layered foundation design
- do not simplify the base into generic boxes
- do not invent unrelated sci-fi decoration
- show clear, readable structural transitions from brace to base

Visual style:
- neutral clay render
- industrial hard-surface concept model
- close-up detail shot
- clean studio lighting
```

<a id="ref-p29"></a>

## REF-P29 — Stepped foundation detail

```text
Use Image A as the overall position reference and Image B as the lower support detail reference.

Generate a detailed close-up reference image of the ground foundation / base platform beneath the ring support structure.

Focus on:
- stepped base layers
- industrial modules embedded in the platform
- edge thickness changes
- panel divisions
- structural massing
- how the supports and central pedestal sit on the base

Requirements:
- match the reference style closely
- keep the base heavy, layered, and mechanically believable
- avoid oversimplification
- avoid adding unrelated design language
- preserve the clean industrial sci-fi hard-surface look

Visual style:
- neutral clay render
- high detail
- clear readable forms
- soft studio lighting
```

<a id="ref-p30"></a>

## REF-P30 — Reinforced bottom segment and doorway

```text
Continue using the previously established ring design language and mechanical surface treatment.

This round is NOT about redesigning the whole structure.
Only design the single bottom-center segment of the ring.

Task:
Create a bottom-center reinforced ring segment that is still part of the ring itself, not an attached box and not a separate building-like module.
This segment should visually read as the main load-bearing and structurally reinforced portion of the lower ring.

Key requirements:

1. Strict left-right symmetry
The entire segment must be perfectly mirror-symmetrical across the vertical centerline.
The massing, panel layout, recesses, trim bands, and structural details on the left and right sides must match symmetrically.

2. Only design this ring segment
Do not include the hanging platform, support columns, base, shield brackets, or any unrelated structures.
Focus only on the bottom-center ring segment itself.

3. Preserve continuous ring curvature
This segment must remain fully integrated into the ring curvature.
The inner and outer arc must stay continuous and smooth.
Do not replace the curved ring section with a rectangular box or an external add-on module.

4. Make it a reinforced version of the normal ring segment
Compared with the surrounding standard ring shell, this segment should feel slightly thicker, heavier, and more structurally layered, but not oversized or bulky.
It should feel like a strengthened version of the ring, not a completely different object.

5. Match the established mechanical language of the ring surface
Do NOT create mechanical detail by randomly sticking many small blocks onto large flat surfaces.
Instead, use the same detail logic as the previously approved ring surface:
- clean large panel masses
- meaningful panel seams
- recessed channels
- layered armor segmentation
- framed access panels
- structural bands / trims
- embedded maintenance features
The detail should feel engineered and integrated, not decorative.

6. Add a central recessed bay on the front face
The front center of this segment must include a clearly defined recessed area that can function as a future large door / hatch / equipment bay location.
This central recess must:
- be centered on the vertical axis
- be symmetrical
- have a clear frame and layered structure
- read as a recessed opening / recessed bay
- be deeper and more intentional than a simple seam
- not become a full hole through the ring
- look like a heavy mechanical portal or access bay

7. Clear hierarchy from center to sides
The design should read as:
normal ring structure → transition zone → reinforced central core segment → transition zone → normal ring structure

8. Stronger lower-edge load-transfer feeling
The lower edge of the segment can be slightly thicker and more reinforced, suggesting that this is the area where structural load is transferred from the lower support system into the ring.
However, it must still remain part of the curved ring and not become a separate attachment.

Avoid:
- asymmetry
- pasted-on random greebles
- boxy add-on modules
- excessive tiny decorative parts
- breaking the ring silhouette
- including supports, platform, base, or other unrelated structures

Output goal:
Generate a clean front orthographic reference image focused only on this bottom-center reinforced ring segment, clearly showing the overall silhouette, strict symmetry, the central recessed bay, and integrated hard-surface mechanical detailing.

Important reminder: the two most important points in this round are strict bilateral symmetry and a clearly defined central recessed door-like bay. Do not solve the detail by randomly adding small surface blocks; use integrated structural layering and recessed hard-surface detail similar to the previously approved ring shell.

Show the segment isolated on a neutral background, front orthographic view only.
```

<a id="ref-p31"></a>

## REF-P31 — Hillside building study

```text
Please revise the left hillside building with two main priorities:

1. The building is currently too large and visually overpowers the scene.  
2. The building form does not yet match the Quixel reference closely enough.

For this revision, please prioritize the building design first, and allow the left hill to be changed in order to fit the building properly.

### Main instructions

- Reduce the overall scale of the left building. It should still feel monumental, but it should not dominate the image more than the ring.
- The building should more closely follow the Quixel architectural language: a modular megastructure made of large cuboid, slanted wedge-like, and blocky interlocking volumes.
- It should feel like a massive engineered facility embedded into the mountainside.
- Avoid random irregular geometry and avoid making it look like a few oversized simple boxes stacked together.
- Keep the material language as pale concrete / metal with a few warm glowing light slits.

### Important terrain note

- Do not feel constrained by the current left hill position or silhouette.
- You are allowed to move the left hill farther back, reshape the slope, or reposition the terrain so the building can fit more naturally.
- In other words: prioritize getting the building shape right, then adapt the hill to support it.
- The hill is not a rigid constraint; it can be redesigned to better accommodate the architecture.

### Scene relationship

- The building remains on the higher foreground hillside on the left.
- The giant ring remains in the farther lowland on the right.
- Preserve the idea that the foreground building sits on higher ground, while the ring is placed in a lower distant basin.
- Keep the open field / valley transition between them.

### Revision priority

1. Fix the overall building silhouette and scale  
2. Adjust the left hill position / shape to support the building  
3. Refine the building-ground integration  
4. Then refine secondary details

The key idea is: **do not force the building into the current small hill. Make the building closer to the Quixel reference, and let the hill adapt to it.**
```

<a id="ref-p32"></a>

## REF-P32 — Increase the building scale

```text
Please revise the left-side building and terrain with the following priorities:

### Current issues

1. The left building does not yet match the reference building closely enough. It only feels similar in style, but the silhouette, massing, and block arrangement are still not accurate enough.  
2. The building is too small.  
3. The mountain on the left is too dominant. The building should be the main subject on the left side of the frame, while the mountain should only act as supporting terrain.

### Revision goals

- Make the left building follow the reference much more closely, aiming for a near 1:1 recreation of the overall architectural form.
- Focus on reproducing the major massing logic:
  - heavy hard-surface cuboid volumes
  - slanted wedge-like forms
  - stacked and interlocking block relationships
  - clear foreground / midground volume overlap
  - a strong engineered megastructure feel
- Avoid simplifying it into just a few generic large boxes.

### Scale adjustment

- Increase the overall size of the left building so it becomes a stronger visual subject.
- It should feel monumental and dominant on the left side.
- However, keep it balanced with the ring so it does not completely overpower the right side.

### Terrain adjustment

- Reduce the visual dominance of the left mountain.
- The mountain should serve as supporting terrain only, not the primary subject.
- You may simplify, lower, push back, or reduce the mountain mass so the building reads more clearly and prominently.
- The key relationship should be: **the building is the left-side subject, and the mountain is only its base/background.**

### Keep

- Keep the ring broadly as it is on the right.
- Keep the idea that the building is on higher ground and the ring sits farther away in lower terrain.
- Keep the foreground path and human figure as scale reference.

### Priority order

1. Correct the left building silhouette and massing to better match the reference  
2. Enlarge the building  
3. Reduce the dominance of the mountain so the building becomes the clear left-side focal point  
4. Then refine how the building integrates into the terrain

### Short summary

**Make the left building much closer to the reference, enlarge it, and reduce the mountain’s dominance so the building—not the mountain—becomes the clear main subject on the left.**
```

<a id="ref-p33"></a>

## REF-P33 — Reduce the building and simplify terrain

```text
Please continue refining the image based on the **current left-image version**, but this round is **not about redesigning the building from scratch**. The main task is to **improve the relationship between the building and the environment**, while using the **right-side reference image** for the terrain and ground treatment.

### Main goals for this round

#### 1. Keep the current architectural design language from the left image

- The overall design direction of the left-side building in the current version is good.
- Please **keep this hard-surface, blocky, modular architectural language**, made of angular volumes, slanted masses, and interlocking cubic / wedge-like forms.
- Do **not** simplify it back into a few large plain sloped concrete shapes.
- The focus of this round is **not to redesign the building itself**, but to improve how it sits in the scene and how it relates to the surrounding terrain.

#### 2. Scale down the building on the left

- The current left-side building is **slightly too large** and visually competes too much with the ring structure on the right.
- Please **reduce the overall size of the left building** so that it still reads clearly and remains an important secondary subject, but does not overpower the ring.
- The final visual hierarchy should be:
  - **The ring on the right is the primary focal point**
  - **The building on the left is the secondary focal point**
- The building should still sit on slightly higher ground, but its scale must be more restrained.

#### 3. Make the mountain / hillside cleaner and simpler, using the right reference image

- In the current left-image version, the mountain slope and rocky terrain feel a bit too busy and overly detailed.
- Please use the **right reference image** as guidance and make the left-side hillside **cleaner, broader, and more simplified**:
  - Reduce the amount of tiny scattered rocks and noisy surface detail
  - Reduce overly complicated small bumps and chaotic texture
  - Keep the main terrain silhouette and large slope shapes
  - The hillside should feel like a clear, readable landform rather than a highly cluttered rocky surface
- It should still feel natural, but more controlled and visually clean.

#### 4. Make the grassland / ground plane cleaner and simpler, also using the right reference image

- The current grassland and foreground ground texture in the left-image version contain too much fine noise and small scattered detail.
- Please simplify the ground treatment and make it closer to the **right reference image**:
  - Reduce excessive small stones, debris, and high-frequency surface noise
  - Make the grassland feel more open, broad, and clean
  - Keep natural variation and gentle terrain undulation, but avoid overcomplicated small details
- The overall result should feel more like:
  - a clean, open plain
  - broad readable land shapes
  - subtle atmospheric haze and depth
  - less visual clutter in the foreground and midground

#### 5. Keep the overall composition and spatial relationship

Please preserve the current overall composition logic:

- The **building on the left** sits on **slightly higher terrain**
- The **ring on the right** stands in the **farther, lower basin / lowland**
- There is an open low area between them
- The foreground path and the human figure can remain
- The water / lake area should stay **closer to the ring in the lower distant terrain**, not pulled back toward the building

Please handle the changes in this order:

1. **Reduce the scale of the left-side building so the ring clearly remains the main subject**
2. **Simplify and clean up the left-side mountain / hillside**
3. **Simplify and clean up the grassland and foreground ground plane**
4. **Keep the current successful blocky building design language**
```

<a id="ref-p34"></a>

## REF-P34 — Single hillside bunker direction

```text
Design a monumental sci-fi bunker-like building embedded into a hillside, intended for a wide cinematic landscape composition where a giant ring megastructure remains the primary focal point. The building should act as a secondary focal point only.

The architecture should be large-scale, hard-surface, brutalist, and fortress-like, with a clean and readable silhouette. Use a few massive geometric volumes rather than many small complex blocks. The building should feel like a defensive bunker, base entrance, or hidden facility built into the slope of a mountain.

Key design features:

- embedded into a hillside or mountain slope
- large slanted retaining walls and wedge-shaped planes
- thick bunker massing
- strong hard-edge geometry, no soft curves
- simple monumental forms with a heavy sense of weight
- a central or slightly offset recessed entrance
- subtle glowing light slits or warm illuminated openings
- layered wall setbacks and shield-like architectural faces
- minimal but intentional panel lines and structural seams
- clean sci-fi realism, not overly decorative
- avoid excessive kitbash clutter
- avoid stacked box chaos
- avoid overcomplicated modular housing appearance

The design should feel austere, monolithic, and grounded, with the visual simplicity of a futuristic fortress or buried megastructure entrance. Keep the building visually powerful but not too visually noisy.

Show the building from a three-quarter view, clearly readable, in daylight, with the hillside integrated into the composition. Focus on shape language, massing, and architectural identity.

**Negative guidance:**\
do not make it look like a city block, do not make it too intricate, do not make it taller or more visually dominant than the giant ring structure, do not use rounded architecture, do not overload the surface with tiny details.
```

<a id="ref-p35"></a>

## REF-P35 — Bunker orthographic references

```text
Create a clean architectural reference sheet for the left-side bunker building in this scene.

The building is a monumental sci-fi bunker embedded into a hillside. It should preserve the same overall design language as the current concept image: a large fortress-like structure integrated into the mountain slope, with heavy slanted concrete-like walls, a recessed vertical entrance, broad buttress-like side masses, and a clean hard-surface silhouette.

Requirements:
- preserve the bunker-like form and overall silhouette from the concept image
- the architecture must feel monolithic, defensive, heavy, and monumental
- use simple large geometric masses rather than many small fragmented shapes
- strong hard edges only, no soft or organic forms
- the entrance should be deeply recessed and vertically emphasized
- include subtle warm light slits and clean structural panel lines
- the building should feel embedded into the hillside, not placed on flat ground
- keep the design visually simple and readable, not overly complex
- this building is a secondary focal point in the overall scene, so do not make it overly elaborate or visually dominant

Show the same building consistently in:
- front view
- side view
- three-quarter view
- optional top view if useful

Use neutral lighting, clean presentation, minimal background, and make it suitable as a 3D modeling reference sheet.
```

<a id="ref-p36"></a>

## REF-P36 — Entrance and foundation details

```text
Generate a detailed close-up reference sheet for a sci-fi bunker building embedded into a hillside.

Focus on the architectural detail language of the bunker:
- recessed entrance
- large slanted wall surfaces
- structural seams and panel breaks
- vents and grilles
- subtle light slits
- layered base transitions where the building meets the ground
- hard-surface trim and support edges
- fortress-like defensive architectural detailing

Style requirements:
- clean sci-fi realism
- hard-surface brutalist bunker design
- simple, functional, believable detailing
- avoid excessive greeble clutter
- avoid decorative complexity
- use details that reinforce mass, thickness, and mechanical realism

Show several close-up views of:
- the main entrance
- the upper wall sections
- the side buttress-like masses
- the base where the architecture meets the hillside

Presentation should be clean, neutral, and suitable for modeling reference.
```

<a id="ref-p37"></a>

## REF-P37 — Bunker integration with the slope

```text
Generate a design reference showing how a monumental sci-fi bunker is embedded into a mountainside.

The focus is the relationship between the architecture and the terrain:
- the bunker is partially buried or inserted into the slope
- the mountain should support and frame the building, but not dominate it
- the architecture should remain the left-side focal element
- the slope should be cleaner and simpler than a highly chaotic rocky mountain
- terrain should feel natural but art-directed and readable
- show how the base of the bunker transitions into the hillside
- show retaining walls, cut slopes, architectural embankments, and clean terrain edges where appropriate

Style:
- cinematic sci-fi environment
- realistic scale
- clean landscape design
- no excessive terrain noise
- no messy rubble overload

Show a three-quarter environmental view and a side view, suitable as reference for 3D blockout.
```

---

## 中文阅读说明

这里保留项目原始任务提示词，包括中间试验与纠错。最终采用方向以[制作流程](Workflow_EN_CN.md)为准。未收录完整聊天记录；涉及本地电脑的路径替换为 `<local asset path>`。通过[提示词索引](Prompt_Index_EN_CN.md)查找对应阶段。
