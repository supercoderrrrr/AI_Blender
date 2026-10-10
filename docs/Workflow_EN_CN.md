# English version

# Making a Sci Fi Megastructure Environment with ChatGPT Codex and Blender

This project began with a selected concept image: a bunker embedded in a hillside on the left, a giant mechanical ring in a distant basin on the right, and a figure, path, and stream in the foreground to establish scale. ChatGPT on the web helped break down the design, generate references, and plan focused tasks. Codex wrote and ran Blender scripts. Blender held the actual geometry, materials, lighting, and renders. I reviewed each result from the main camera before keeping it, correcting it, or returning to an earlier version.

The project reached v119 with a cool daytime image at 3840 × 2160. This breakdown follows the work from visual references to an editable scene, with particular attention to the corrections that changed the result.



![Final v119 camera render. Cool daylight, with the ring as the primary subject.](<../assets/process/final_v119.jpg>)

*Final v119 camera render. Cool daylight, with the ring as the primary subject.*

## 1 Establish the composition and reference roles

The focal hierarchy stayed consistent: the ring was the primary subject, the bunker was secondary, and the figure, path, and terrain supported them. Mountains, fog, and the later planets also had to fit that hierarchy.

The concept image established the composition before the assets were separated. The ring sat in a distant basin; the bunker occupied higher ground on the left. The lake stayed near the ring, while the path guided the figure into the scene. The final camera made it possible to judge whether a local detail deserved more work.

References had different responsibilities. The full scene supplied framing and proportions. Blockouts supplied installation positions. Concept crops supplied silhouettes. Material references supplied color and surface character. Later overcast images supported lighting experiments, while the final scene returned to daylight.

The numbered files 1–9 and 20–25 are external references collected online. Most were found through ArtStation, and a few with GPT search assistance. FinalRef and Ref2 are my own target images generated with NeoWow. The other images supply ring structure and detail references; file 19 is a layout reference. The key ring reference is the file named “未来工业环形空间门 render.png”, translated here as Future Industrial Ring Portal. The unused alu-1 image is omitted.



![FinalRef and Ref2. Target scene references generated with NeoWow.](<../assets/process/target_finalref.jpg>)

![FinalRef and Ref2. Target scene references generated with NeoWow.](<../assets/process/target_ref2.jpg>)

*FinalRef and Ref2. Target scene references generated with NeoWow.*



![File 19. Layout reference supplied for the scene and asset relationships.](<../assets/process/reference_19.jpg>)

*File 19. Layout reference supplied for the scene and asset relationships.*

## 2 Turn the concept into modeling references on the web

### Separate the complete ring and the standard segment

First, the ring was extracted from its environment and presented as a clean white and gray asset. Removing weathering and fog made the structural layers easier to read. Front, side, top, and rear references then helped describe the shell thickness, platforms, and foundations.

The full ring was still too complex to use as a single modeling task, so it was broken down into a repeatable segment. The first generated result was a large C shape. The next instruction specified an approximately 20° short arc, two radial interfaces, continuous shell and rails, and no decorative exposed end caps.

The outer service channel also required a directional correction. “Outer shell channel” could be interpreted as an inner edge or front-face decoration. Describing the convex outer crown as the equivalent of a tire tread made the target surface and circumferential direction clearer.

### Resolve the attachments separately

The right outer platform used the blockout for its position and the original concept for its shape. It developed a thick deck, lower structural mass, diagonal braces, and upper and lower curved mounts. The mounts had to wrap the ring, with readable connections between platform and shell.

The inner platform was generated separately. Its first requirement was to project from the right side into the ring opening. Thick edge beams, lower mass, and a central portal frame came afterward. One symmetric front-view attempt lost that frame, so the next correction targeted the center without rebuilding the rest.

The clearest spatial misunderstanding involved the two suspension rods. They were initially arranged left and right. Rotating their cross-sections did not solve the problem. Their positions needed to separate along the ring's depth axis: nearly overlapping in front view, distinct in side view, and separated in plan. Describing the expected projection in each view was more effective than saying “rotate 90°.”

The lower assembly was broken into diagonal supports, upper joints, lower feet, a central column, and stepped foundations. Local images supplied structural language; Blender supplied the actual dimensions and connections.

### Reduce the bunker to a few large masses

The bunker initially explored interlocking wedge modules inspired by Quixel REBIRTH. Increasing their scale made the building and hillside too prominent, while the terrain became busy. The design moved toward a simpler hillside bunker with large sloped buttresses, a deep vertical entrance, restrained panel joints, and warm lights.

Once that direction was stable, further images described the building's views, entrance details, and contact with the slope. Local references became easier to use without disturbing the overall composition.

Generated orthographic images remained design references. Their views could disagree. Precise angles, thickness, and continuity had to be checked against a single Blender model.



![Future Industrial Ring Portal. The principal ring structure reference.](<../assets/process/principal_ring.jpg>)

*Future Industrial Ring Portal. The principal ring structure reference.*



![Segment and outer-crown references for modular structure and the service channel.](<../assets/process/arc_segment.jpg>)

![Segment and outer-crown references for modular structure and the service channel.](<../assets/process/outer_crown.jpg>)

*Segment and outer-crown references for modular structure and the service channel.*

## 3 Write focused tasks with clear limits

The prompt-planning conversation analyzed visible problems and turned them into tasks for Codex. A typical task identified the approved baseline, the role of each reference, the current mismatch, the parts to preserve, the permitted changes, and the required previews. It also required a new saved version and a stop for review.

This format made broad requests more concrete. A water task described reflection, shallow-water visibility, and disturbances around rocks. A concrete task specified where stains began, how long they were, and how dark they could become. A planet task specified the curved limb, transparency, texture, and separation from the mechanical ring.

AGENTS.md preserved the working rules across tasks: keep approved versions, save major changes separately, protect manual work, avoid duplicate generated geometry, and review from the final camera. Each prompt defined the current change; the project rules carried the longer-term constraints.

## 4 Build a real parametric ring

Blender work began with a thick annular sector. The early prototype exposed four custom properties on ARC_PARAMETERS: outer radius, inner radius, axial thickness, and segment angle. After editing them, an external Python script rebuilt the generated studies.

The initial values were 10, 7.8, 2.1, and 20°. These were provisional modeling units. The ring width and scene scale changed later.

The prototype produced an isolated segment, three connected segments, and an eighteen-segment ring. It checked the continuity of the shell, channels, and rails. Interface frames belonged to the assembly, with one frame at each joint. The early review recorded a first-to-last shell closure error of about 0.00000215 units.

This converted visual plausibility into a geometric check. The full-ring test was fixed at eighteen repetitions, so changing the segment angle also required updating the repetition count.

Broad shell panels, the outer service belt, side platforms, suspension structure, and foundations developed afterward. Large silhouettes and medium-scale structure came before small inspection openings, fittings, and industrial markings. Cross-sections, recesses, and connections carried more of the distant mechanical read than randomly scattered boxes.



![Blender v001. Isolated segment, three-segment connection, and eighteen-segment ring.](<../assets/process/v001_isolated.jpg>)

![Blender v001. Isolated segment, three-segment connection, and eighteen-segment ring.](<../assets/process/v001_three.jpg>)

![Blender v001. Isolated segment, three-segment connection, and eighteen-segment ring.](<../assets/process/v001_ring.jpg>)

*Blender v001. Isolated segment, three-segment connection, and eighteen-segment ring.*

## 5 Move from the asset to the scene and materials

Once the ring was stable, the environment blockout used a collection instance of the asset. The hillside, basin, bunker, lake, path, and placeholder figure were arranged before the main camera was reviewed.

The ring was moved farther away and enlarged in world space to retain a similar image size while increasing the spatial separation. The figure established human scale, and the path and stream led toward the distance.

Material work centered on painted metal, concrete, terrain and vegetation, and water. The ring's broad shell stayed lighter than its platforms and recesses, with a warm inner light band. The bunker used large concrete surfaces and a deep doorway for weight. Yellow industrial accents later gained black warning stripes, while functional lights remained sparse.

The grass initially looked too gray-green. It was adjusted toward the dry yellow meadow in the reference, with olive shadows and soil variation retained. Color decisions were made under the current lighting, because a warmer base color alone did not guarantee a yellow result in the render.

Fog occupied separate spatial layers: basin accumulation, a thin lake layer, mountain atmosphere, and local haze around the ring. The foreground high ground remained clearer, while low mist connected the ring's base to the basin.



![Blender v049 and v056. From the environment blockout to the first global look development.](<../assets/process/v049_blockout.jpg>)

![Blender v049 and v056. From the environment blockout to the first global look development.](<../assets/process/v056_lookdev.jpg>)

*Blender v049 and v056. From the environment blockout to the first global look development.*

## 6 Balance the stream through several corrections

The stream successively resembled a gray ribbon, a cut trench, a wet dry channel, and uniform brushed streaks. These problems involved the banks, water material, and motion cues together.

The bank pass improved the transition between water, wet soil, rocks, and vegetation. Once the banks became more natural, reflection became too weak and the channel read as mud. The next pass restored sky reflections and highlights while preserving a restrained view of the shallow bed.

The motion pass used coordinates following the channel and disturbances around rocks. The first directional texture was too uniform. Later changes introduced quiet patches, transverse ripples at different scales, and local variation near stones, breaking up the continuous streaks.

This was a shading and surface-normal solution with flow cues. No complete fluid simulation was produced. The final adjustments only clarified reflections, aiming for a slowly flowing shallow stream. Once the banks were accepted, further corrections stayed within the water material.



![Blender v098 and v099. Directional streaks followed by a more varied water surface.](<../assets/process/v098_stream.jpg>)

![Blender v098 and v099. Directional streaks followed by a more varied water surface.](<../assets/process/v099_stream.jpg>)

*Blender v098 and v099. Directional streaks followed by a more varied water surface.*

## 7 Return to cool daylight after weather experiments

AI concept images explored an overcast sky and light entering from behind and above the ring. The actual Blender attempt made the bunker too dark, created repeated hard beams, and made the water too bright. The project returned to the v092 daytime direction.

Cloud layering from the overcast reference still informed later work, but the sky had to fit the established daylight. Attempts at thicker clouds then produced oversized, close-looking foam forms. The v099 sky shape was restored as a base, followed by adjustments to blue-gray depth and the lighter sky toward the upper-right light direction.

During the same period, the bunker retained mild vertical stains. The staircase changed from 72 to 54 treads while keeping its width, run, total rise, and landings. The upper lights developed from simple luminous lines into physical wall recesses: dark housings, inset light surfaces, and local area lights created shadows and illumination. The central panel remained unlit by this strip; only the side buttresses retained it.



![Blender weather experiments. The v093 overcast direction and v103 thick-cloud forms were not retained.](<../assets/process/v093_weather.jpg>)

![Blender weather experiments. The v093 overcast direction and v103 thick-cloud forms were not retained.](<../assets/process/v103_clouds.jpg>)

*Blender weather experiments. The v093 overcast direction and v103 thick-cloud forms were not retained.*



![Blender v104. Inset light strips on the bunker buttresses, with housing and local illumination.](<../assets/process/v104_recess.jpg>)

*Blender v104. Inset light strips on the bunker buttresses, with housing and local illumination.*

## 8 Solve the planet's shape before its texture and scale

The upper-left planet added world context while the ring remained the subject. Its first appearance looked like a diagonal gray-blue overlay, with little recognizable curvature or surface information.

Inspection showed that the initial implementation used an analytic sphere and circular mask in the sky shader. The offset placed a nearly tangent part of the limb inside the frame, while strong downward fading erased more of the curve. The projection and blending needed to change.

The replacement rendered a real sphere in a separate scene, exported a transparent linear EXR, and projected it through the fixed main camera. Shape, alpha, visibility, and sky integration could then be controlled independently while the original world illumination stayed intact.

The procedural surface still did not resemble a gas giant, so it was replaced with NASA's Hubble Jupiter Global Map 2019. Spherical mapping preserved Jupiter's broad bands. Texture orientation and visible coverage were adjusted around the Great Red Spot. These bands belonged to the planet's own atmosphere; no additional outer cloud shell was added.

The planet went through enlargement, texture rescaling, desaturation, and a later reduction in overall size. Jupiter's natural warm colors did not fit the cool blue scene well, so the final direction was subdued. Framing depended on visible curvature and texture readability rather than retaining the early diameter of about 2.4 frame widths.

The smaller Neptune-like companion used the supplied texture and the same sphere-pass approach. It was moved close to the large planet's limb and tilted slightly.

This solution was designed for the fixed hero camera. A camera change would require recalculating the projection and updating the planet layers.



![Blender v106 and v114. From the diagonal-looking planet mask to the Jupiter and companion composition.](<../assets/process/v106_planet.jpg>)

![Blender v106 and v114. From the diagonal-looking planet mask to the Jupiter and companion composition.](<../assets/process/v114_sky.jpg>)

*Blender v106 and v114. From the diagonal-looking planet mask to the Jupiter and companion composition.*

## 9 Combine mountain structure with atmospheric perspective

The mountains first gained layers, then lower contrast, saturation, and edge clarity to move them farther away. Excessive fading made them look too low and weak. Later work restored some peak definition and lowered the mist in front of them.

After background version B was selected, the mountains returned to the v105 three-layer foundation. In v115, the smooth slopes gained asymmetric ridges, main valleys, tributaries, and residual spurs while retaining their existing footprint and height envelope.

Photographic rock textures used world-space triplanar mapping to limit stretching on steep slopes. Each distance layer had separate air-color blending. Mountain bases approached the basin haze color, and the farthest layer carried less surface variation.

A low-haze diagnostic render used the same camera to separate missing terrain structure from structure hidden by fog. Those diagnostic haze values did not replace the final atmosphere.



![Blender v115. Approved haze and a low-haze diagnostic from the same camera.](<../assets/process/v115_mountains.jpg>)

![Blender v115. Approved haze and a low-haze diagnostic from the same camera.](<../assets/process/v115_lowhaze.jpg>)

*Blender v115. Approved haze and a low-haze diagnostic from the same camera.*

## 10 Replace the figure and resolve the bunker lighting

The figure was replaced near the end with the static D3_IDLE2 pose from an external FBX. Height, position, and foot contact matched the placeholder. The figure remained turned away from the camera toward the ring, with a final height of about 1.76 meters. Its materials and textures were packed into the project.

The final lighting problem was to bring some daylight onto the bunker while retaining the light through the ring's lower-right fog. Rotating the global sun clockwise improved the bunker but changed the ring's beams. Smaller rotations still did not provide the preferred balance.

The final solution restored the original global sun and added a directional light linked only to the bunker. It lit surfaces and cast shadows, with its volume contribution set to zero. The bunker gained definition while the original fog lighting remained. The bunker geometry was not rotated.

This was a local lighting adjustment for the main camera. Limiting the receiving objects reduced the effect on the rest of the scene.



![Blender v114. The supplied D3_IDLE2 static pose replaces the placeholder figure.](<../assets/process/v114_idle2.jpg>)

*Blender v114. The supplied D3_IDLE2 static pose replaces the placeholder figure.*



![Blender v118. Bunker comparison before and after the linked directional fill.](<../assets/process/v118_fill.jpg>)

*Blender v118. Bunker comparison before and after the linked directional fill.*

## 11 Render at full resolution and apply a restrained grade

The v119 delivery used Blender 5.2.2 LTS with these settings.

| Setting | Value |
|---|---|
| Resolution | 3840 × 2160 |
| Main scene engine | EEVEE |
| Samples | 192 |
| Output | 16-bit RGB PNG |
| Color management | Original AgX and exposure retained |
| Final grade | Gentle RGB curve and saturation 0.99 |
| Planet layers | Rerendered as 4K camera passes |

To manage memory, four overlapping horizontal regions were freshly rendered at the final resolution and smoothly assembled in Blender. Every region was refreshed; no earlier low-resolution foreground was reused. The planet passes were output at 4K, while source textures retained their existing resolutions.

The grade made small tonal and saturation adjustments. The main camera, geometry, world, fog, and existing lights stayed intact. The final project was reopened for checks and retained editable grading nodes and the hero scene.

## 12 Working habits that helped

Specify the object and direction before changing it. Rod depth, outer-crown placement, and the inner light band all needed explicit spatial descriptions. Words such as “core,” “outside,” and “rotate a little” could refer to different things.

Handle silhouette, material, and atmosphere in focused stages. Check the ring closure before adding detail, restore water reflections when the channel loses its water read, and diagnose mountain structure before adding texture.

Keep recoverable versions. The overcast direction and oversized clouds were rolled back. Figure replacement, mountains, and local lighting also had separate versions. Earlier files preserved a useful baseline and explained why a direction changed.

Review both the main camera and targeted diagnostics. The hero frame decided whether a change helped; orthographic views, low-haze renders, and isolated transparent planet passes helped locate the cause.

A successful script run only confirmed that the operation executed. References, hierarchy, and material credibility still needed a rendered image and human judgment. That repeated review connected ChatGPT, Codex, and Blender throughout the project.

## Reference and asset credits

External references are the numbered files 1–9 and 20–25. Most were collected through [ArtStation](https://www.artstation.com/?sort_by=community&dimension=all); some were located with GPT search assistance. Search assistance does not make these GPT-generated images. Individual artwork pages and artist names were not provided with these files, so the available attribution remains at collection-platform level.

FinalRef and Ref2 were generated with NeoWow as my target scene references. The remaining selected images document ring structure, detail, or layout. The Future Industrial Ring Portal is the principal ring reference; file 19 supplies layout. The unused alu-1 is excluded.

The Jupiter texture source recorded in the project is [Hubble Jupiter Global Map 2019](https://science.nasa.gov/asset/hubble/jupiter-global-map-2019/). Credit: NASA, ESA, A. Simon at Goddard Space Flight Center, and M. H. Wong at the University of California, Berkeley. The Neptune texture and D3_IDLE2 FBX were supplied separately for the project. Rock textures were packed with the Blender files.

The companion prompt archive preserves 37 numbered reference-design instructions and 24 numbered production-refinement prompts, together with the concept-image prompt notes. The workflow above explains the implementation and final choices.


[Prompt index](Prompt_Index_EN_CN.md) · [Reference-design prompts](Reference_Prompts.md) · [Production prompts](Production_Prompts.md) · [Image credits](Credits_EN_CN.md)

## Collected reference gallery

External references 1–9 and 20–25, collected online. Most were found through ArtStation.

![External reference gallery](<../assets/process/external_reference_gallery.jpg>)

The other selected files supply ring structure, detail, and layout references.

![Ring structure reference gallery](<../assets/process/structure_reference_gallery.jpg>)


# 中文版本

# 用 ChatGPT Codex 和 Blender 制作科幻巨构场景

这次制作从一张已选定的概念母图开始：左侧是嵌入山坡的地堡，右侧远处是一座巨型机械圆环，前景用人物、小路和溪流交代尺度。ChatGPT 网页版负责拆解设计、生成参考图和规划修改任务；Codex 编写并执行 Blender 脚本；Blender 保存真实几何、材质、灯光和最终渲染。每轮结果由人工从主镜头判断，再决定保留、修正或回退。

项目最终完成到 v119，交付 3840 × 2160 的冷调白天场景。这篇复盘讲述参考图如何转成可制作的任务，以及制作中几次影响较大的纠错。



![v119 最终镜头渲染。冷调白天，圆环保持第一焦点。](<../assets/process/final_v119.jpg>)

*v119 最终镜头渲染。冷调白天，圆环保持第一焦点。*

## 1 先固定画面关系

整个项目始终围绕同一个主次关系推进：圆环是第一焦点，地堡是第二焦点，人物、道路和地形负责辅助。后来加入的山、雾和行星，都要服从这个关系。

母图先确定构图和世界尺度，再拆分资产。圆环在远处盆地，地堡位于左侧较高的坡地，湖面靠近圆环，小路将人物带向场景深处。这样安排后，局部结构即使很复杂，也能用最终镜头判断它是否值得继续投入。

参考图的职责也需要提前说清楚。整体母图提供画面占比；白模提供安装位置；原概念裁图提供轮廓；材质参考提供色彩和表面特征。后期的阴天参考只用于光照探索，没有成为最终天气方向。

参考图文件 1–9、20–25 是网上搜集的外部参考，多数来自 ArtStation，少量由 GPT 帮助查找。FinalRef 和 Ref2 是我使用 NeoWow 生成的目标效果参考。其余图用于圆环结构与细节，其中 19 是布局图，“未来工业环形空间门”是最重要的圆环参考；未使用的 alu-1 不收录。



![FinalRef 与 Ref2。使用 NeoWow 生成的目标效果参考。](<../assets/process/target_finalref.jpg>)

![FinalRef 与 Ref2。使用 NeoWow 生成的目标效果参考。](<../assets/process/target_ref2.jpg>)

*FinalRef 与 Ref2。使用 NeoWow 生成的目标效果参考。*



![19.png。用于场景与资产关系的布局参考。](<../assets/process/reference_19.jpg>)

*19.png。用于场景与资产关系的布局参考。*

## 2 在网页版把概念拆成建模参考

### 从完整圆环拆到标准弧段

第一步把圆环从环境中单独提取出来，再生成清洁白灰版本，减少做旧和雾对结构的遮挡。之后补正面、侧面、俯视和背面参考，检查壳体厚度、平台和底座的大体关系。

完整圆环仍然太复杂，所以继续拆出可重复的标准弧段。第一次生成结果是一个很大的 C 形，无法直接帮助制作短模块。修正时明确要求约 20° 的短弧、两个径向切面、连续的壳体和轨道，并去掉展示式端部装饰。

外圆冠服务槽也经历了方向纠错。只写“外壳凹槽”容易得到内圈或正面装饰；后来用类似轮胎胎面的凸外圆冠来说明目标面，限定槽的位置和沿圆周延伸的方向。

### 分别解决附件的形体和空间关系

右侧外平台先用白模锁定安装位置，再参考原概念恢复厚甲板、下部体量、斜撑和上下夹持座。夹持座需要随环的曲率包裹，平台与圆环之间的连接也要读得清楚。

内平台单独生成，先明确它从右侧环体向开口内部伸出，再补厚边梁、底部质量和中央门架。要求立面对称时，生成图一度把门架删掉；下一轮只修中间区域，避免整个平台再次变形。

顶部吊装最有代表性的错误是两根吊杆的位置。最初它们被画成左右排列，随后尝试旋转杆的截面仍没有解决问题。真正需要改的是前后深度关系：从正面看两杆接近重叠，从侧面看分开，俯视能看到轴向间距。用不同视图的投影结果描述位置，比只说“转 90°”更明确。

底部结构继续拆成斜撑、上端接环节点、下端支脚、中央立柱和阶梯基础。局部参考提供结构语言，真实连接与比例留到 Blender 中验证。

### 地堡从堆叠模块转向少量大体块

左侧建筑早期探索过 Quixel REBIRTH 风格的交错楔形模块。放大后，建筑和山体过强，地面也变得繁杂。后来转向更简洁的山嵌式地堡：少量巨型斜面扶壁、深凹的纵向入口、有限的板缝和暖色灯光。

这个方向确定后，再生成建筑多视图、入口细节和建筑与坡面的关系图。参考图开始围绕可制作的局部问题服务，整体构图也更容易保持稳定。

这些生成的“正交图”仍然是设计参考。视图之间可能出现不一致，精确角度、拼接关系和厚度要在同一个 Blender 模型上重新检查。



![“未来工业环形空间门”。圆环结构的主要参考。](<../assets/process/principal_ring.jpg>)

*“未来工业环形空间门”。圆环结构的主要参考。*



![环段与外圆冠参考，用于模块结构和服务槽设计。](<../assets/process/arc_segment.jpg>)

![环段与外圆冠参考，用于模块结构和服务槽设计。](<../assets/process/outer_crown.jpg>)

*环段与外圆冠参考，用于模块结构和服务槽设计。*

## 3 把视觉要求写成有边界的制作任务

网页版的提示词规划对话用于分析当前画面的问题，再转成 Codex 可以执行的分阶段任务。实际使用的任务通常包含：

- 当前采用的版本和参考图职责。
- 本轮要解决的具体问题。
- 必须保留的相机、对象、灯光和材质。
- 允许调整的对象及调整幅度。
- 需要交付的主镜头、局部图和版本文件。
- 输出预览后停止，等待人工审阅。

这种格式最有用的地方，是把“更真实”“更有电影感”拆成可检查的变化。例如水面修复会指定反射、浅水透视和绕石波纹；混凝土做旧会指定污痕的源头、长度和深浅；行星修复会指定圆弧、透明轮廓、纹理和与圆环的间隔。

项目还用 AGENTS.md 固定操作规则：保留已批准版本，每次主要修改另存，保护手工编辑，避免重复生成几何，按最终相机审阅。提示词里的约束负责本轮范围，项目规则负责长期习惯。

## 4 用参数化原型建立真实圆环

Blender 制作先从厚环形扇区开始。早期原型把四项参数放在 ARC_PARAMETERS 对象的自定义属性中：外半径、内半径、轴向厚度和段角度。修改后运行外部 Python 脚本重建生成部分。

初始值是外半径 10、内半径 7.8、轴向厚度 2.1、段角度 20°。这些是原型的暂定建模单位，后续又调整过宽度和场景尺度。

原型分别输出单段、三段接续和十八段整环，检查壳面、凹槽和轨道是否连续。接口框由装配统一放置，每个接点只保留一份，避免两段重复复制。早期审核记录给出的首尾壳板闭合误差约为 0.00000215 单位。

这一步把图像里的“看起来能拼接”落实成实际几何检查。脚本中的整环测试固定重复十八段，因此段角度改动后，重复数量也需要配套调整。

随后逐步发展宽壳板、外圆冠服务带、侧平台、顶部吊装和底部承座。细化时先看大轮廓和中等结构，再补小型检修口、连接件和工业标识。远景中的机械量感主要来自截面、凹入关系和连接层次，随机贴小方块很容易让画面变碎。



![Blender v001。单段、三段接续与十八段整环检查。](<../assets/process/v001_isolated.jpg>)

![Blender v001。单段、三段接续与十八段整环检查。](<../assets/process/v001_three.jpg>)

![Blender v001。单段、三段接续与十八段整环检查。](<../assets/process/v001_ring.jpg>)

*Blender v001。单段、三段接续与十八段整环检查。*

## 5 从资产转入场景白模和材质

圆环资产稳定后，环境白模阶段将原资产以集合实例放入场景。先搭左侧坡地、盆地、建筑、湖面、小路和人物占位，再检查主镜头。

为了强化远近关系，圆环曾后移并同步增大实体尺寸，使画面占比接近原构图，同时获得更大的真实空间间隔。人物作为比例参照，小路和溪流提供向远处延伸的线索。

后续材质主要围绕四类对象展开：浅色涂装金属、混凝土、地表植被和水。圆环宽壳板较浅，平台与机械凹陷较暗，内圈保留暖色发光带；地堡以混凝土大面和深门洞形成重量感。黄色工业标识后来加入黄黑警示条纹，功能灯点保持稀疏。

草地也反复调整过。最初灰绿倾向较强，后来按照参考中的干黄草甸调整，保留暗部的橄榄色和土壤变化。颜色判断始终在当前光照下进行，避免材质看似变黄、渲染后仍偏绿。

雾分成不同空间层：盆地积雾、湖面薄雾、远山空气透视，以及圆环附近的局部薄霭。靠近前景的高地保持相对清晰，低雾用于交代圆环基座与盆地的深度。



![Blender v049 与 v056。从环境白模到初步全局材质和氛围。](<../assets/process/v049_blockout.jpg>)

![Blender v049 与 v056。从环境白模到初步全局材质和氛围。](<../assets/process/v056_lookdev.jpg>)

*Blender v049 与 v056。从环境白模到初步全局材质和氛围。*

## 6 溪流修复是一次连续的平衡过程

溪流先后出现过灰色丝带、人工沟槽、湿泥干沟和均匀拉丝等问题。它们涉及岸线、水材质和表面运动感，单独增加一种噪声无法同时解决。

岸线阶段处理水、湿土、岩石和植被之间的过渡。岸边更自然后，水的反射又被压得太弱，远景看起来像没有水的泥沟。下一步恢复天空反射和水面高光，同时保留浅水的床底信息。

流动感阶段使用沿河方向的坐标和局部绕石变化。一开始顺流纹理过于均匀，产生刷痕般的拉丝。后续加入较平静的水面区域、不同尺度的横向波纹和石头附近的局部扰动，打散整条河的统一纹理。

这里采用的是水面着色、微法线和流向变化，没有制作完整流体模拟。最后只小幅加强反射，让它在主镜头里读成缓慢流动的浅溪。河岸已经认可后，水面调整继续保持在材质范围内。



![Blender v098 与 v099。从顺流拉丝到更有空间变化的水面。](<../assets/process/v098_stream.jpg>)

![Blender v098 与 v099。从顺流拉丝到更有空间变化的水面。](<../assets/process/v099_stream.jpg>)

*Blender v098 与 v099。从顺流拉丝到更有空间变化的水面。*

## 7 天气探索后回到冷调白天

中途曾以 AI 概念图预演阴天和右后上方破云的效果。实际 Blender 版本出现地堡过暗、重复硬光束和水面过亮等问题，整体气氛偏离了原先希望保留的白天场景，因此回到 v092 的方向。

之后仍借鉴阴天参考的云层层次，但要求天空服从已经确定的白天光照。继续尝试厚云时，云团又变得过大、过近，像泡沫状体块。最终回到 v099 的天空形态作为基础，再调整蓝灰色深度和右侧较浅的受光区域。

同一阶段，地堡侧墙只保留轻微竖向污痕；台阶从 72 级减到 54 级，保留原有宽度、坡长、总高度和平台位置。上部灯带也从简单发光线改成墙内凹槽：暗色灯槽、内缩的发光面和局部面光一起提供阴影与墙面受光。中间板上的灯带移除，仅保留两侧扶壁部分。



![Blender 天气试验。v093 阴天方向和 v103 厚云形态后来均未保留。](<../assets/process/v093_weather.jpg>)

![Blender 天气试验。v093 阴天方向和 v103 厚云形态后来均未保留。](<../assets/process/v103_clouds.jpg>)

*Blender 天气试验。v093 阴天方向和 v103 厚云形态后来均未保留。*



![Blender v104。扶壁上的内凹灯带，包含灯槽与局部照明。](<../assets/process/v104_recess.jpg>)

*Blender v104。扶壁上的内凹灯带，包含灯槽与局部照明。*

## 8 行星先解决球形，再解决纹理和尺度

左上行星用于补充世界观，圆环仍然是主角。最初的行星看起来像斜向灰蓝覆盖层，球面曲率和表面信息都很弱。

检查实现后发现，初版使用天空着色器中的解析球面与圆形遮罩。圆心偏移、画内可见轮廓接近切线，加上较强的向下淡化，把可识别的曲率进一步擦掉。这里需要调整的是投影与融合方式。

修正方案在独立场景中渲染真实球体，输出带透明通道的线性 EXR，再按固定主相机投影合成。这样可以分别控制球形、透明轮廓、可见度和天空融合，保持场景原来的世界照明。

程序纹理仍不够像气态行星，于是换成 NASA 的 Hubble Jupiter Global Map 2019。用球面映射保留木星带状结构，并围绕木星之眼调整纹理朝向与可见区域。这里的云带属于木星表面的大气纹理，没有另外包一层云壳。

行星经历过放大、纹理缩小、降饱和，以及整体重新缩小。真实木星的暖色与场景冷蓝色不够协调，最后选择更淡、更低饱和度的表现；尺度也以画内弧线和纹理可读性为准，没有一直保留最初约 2.4 倍画宽的方案。

小海王星使用提供的纹理，同样先渲染球体，再融入天空。它移到大行星与天空的边界附近，并略微倾斜，成为更小的陪伴天体。

这套方法针对固定主镜头。修改相机后，需要重新计算投影并更新相关行星图层。



![Blender v106 与 v114。从斜向覆盖感到木星与陪伴天体的天空构图。](<../assets/process/v106_planet.jpg>)

![Blender v106 与 v114。从斜向覆盖感到木星与陪伴天体的天空构图。](<../assets/process/v114_sky.jpg>)

*Blender v106 与 v114。从斜向覆盖感到木星与陪伴天体的天空构图。*

## 9 远山要同时具备地貌和空气透视

远山先增加层次，再压低对比、饱和度和边缘清晰度，让它们后退。但过度减淡之后，山又显得矮而模糊；后续逐步恢复峰形，并控制山前雾的高度。

选定背景 B 版后，山体先恢复到 v105 的三层基础。v115 再做地质结构修复：原来平滑的宽坡加入不对称山脊、主谷、支流和残留支脊，保持原有范围与高度轮廓。

表面换成岩石摄影纹理，通过世界坐标三向投射减少陡坡拉伸。近、远层分别控制空气色混合，山脚逐渐接近盆地雾色，最远层的表面变化更弱。

检查时还生成了同相机的低雾诊断图，用来区分几何本身缺少结构和结构被雾遮住这两种情况。诊断场景的低雾设置没有直接取代最终氛围。



![Blender v115。同镜头的正常雾与低雾诊断，用于检查山体结构。](<../assets/process/v115_mountains.jpg>)

![Blender v115。同镜头的正常雾与低雾诊断，用于检查山体结构。](<../assets/process/v115_lowhaze.jpg>)

*Blender v115。同镜头的正常雾与低雾诊断，用于检查山体结构。*

## 10 最后替换人物并解决地堡受光

人物到收尾才替换为外部 FBX 中的 D3_IDLE2 静态姿态。先对齐草稿的身高、位置和脚底，再保持背向镜头、面朝圆环的方向。放入场景后的身高约 1.76 米，人物贴图与材质打包进工程。

最后一个光照问题，是地堡需要多一点日光，但圆环右下方原有的穿雾效果又必须保留。尝试顺时针旋转全局太阳后，地堡受光改善，圆环附近的光束却发生变化；回调角度仍难兼顾。

最终恢复旋转前的全局太阳，另外添加一盏只关联地堡的定向补光。它参与表面照明并产生阴影，体积贡献设为零，所以能够改善地堡明暗，同时保留原有圆环雾中的光线。地堡没有旋转。

这是为主镜头服务的局部补光选择。把受光对象限定清楚，能减少一次局部修改对整幅画面的影响。



![Blender v114。使用提供的 D3_IDLE2 静态姿态替换人物草稿。](<../assets/process/v114_idle2.jpg>)

*Blender v114。使用提供的 D3_IDLE2 静态姿态替换人物草稿。*



![Blender v118。仅关联地堡的定向补光前后对比。](<../assets/process/v118_fill.jpg>)

*Blender v118。仅关联地堡的定向补光前后对比。*

## 11 最终渲染和轻微调色

v119 采用 Blender 5.2.2 LTS，最终设置如下。

| 项目 | 设置 |
|---|---|
| 分辨率 | 3840 × 2160 |
| 主场景渲染引擎 | EEVEE |
| 采样 | 192 |
| 输出 | 16 位 RGB PNG |
| 色彩管理 | 保留原 AgX 与曝光 |
| 后处理 | 轻微 RGB 曲线，饱和度 0.99 |
| 行星图层 | 按最终镜头重新输出 4K pass |

为控制内存，画面分成四个带重叠的水平区域，以最终分辨率重新渲染，再在 Blender 中平滑拼合。最终图片的所有区域均重新计算，没有沿用早期低分辨率前景。行星 pass 的输出提升到 4K，原始纹理仍保持自身分辨率。

调色只轻微整理明暗和饱和度。主相机、场景几何、世界、雾和原有灯光继续保持，最终文件也经过重新打开检查。工程保留可编辑的调色节点和主场景。

## 12 这次工作中最有用的几个习惯

第一，修改前说清楚对象和方向。吊杆前后关系、外圆冠位置、内圈发光带，都需要明确的空间描述；含糊的“核心”“外侧”“转一点”容易指向不同东西。

第二，把轮廓、材质和氛围分阶段处理。短弧段没有拼好时先做闭环；水感丢失时先恢复反射；山形不足时先检查地貌。明确当前问题，后续结果也更容易判断。

第三，保存可以回退的版本。v093 的天气和过厚云团都曾回退，人物替换、山体修复、补光也各自另存。旧版提供可恢复的基础，还能用于说明为什么改变方向。

第四，既看主镜头，也看局部诊断。主镜头决定投入是否有意义，正交视图、低雾图和透明球体 pass 帮助定位原因。

最后，脚本运行成功只说明操作执行了。是否符合参考、主次是否稳定、材质是否真实，仍然要通过渲染和人工判断。ChatGPT、Codex 和 Blender 之间持续来回的检查，构成了这次项目的实际制作流程。

## 参考与素材来源

编号 1–9、20–25 是网上搜集的外部参考，多数经由 [ArtStation](https://www.artstation.com/?sort_by=community&dimension=all) 找到，少量由 GPT 帮助查找。由 GPT 查找的图片仍属于外部参考。随文件提供的信息没有包含每幅作品的作者与作品页，当前记录的是搜集平台。

FinalRef 和 Ref2 是我使用 NeoWow 生成的目标效果参考。其他选定图片用于圆环结构、细节或布局；“未来工业环形空间门”是主要圆环参考，19 是布局图。alu-1 未使用，不收录。

木星贴图使用项目记录中的 [Hubble Jupiter Global Map 2019](https://science.nasa.gov/asset/hubble/jupiter-global-map-2019/)。署名 NASA、ESA、A. Simon（Goddard Space Flight Center）、M. H. Wong（University of California, Berkeley）。海王星纹理和 D3_IDLE2 FBX 由项目另行提供，岩石纹理打包在工程中。

配套提示词档案保存 37 条参考设计指令、24 条制作修正提示词和概念图提示词补记。实际实施与最终取舍见上面的制作流程。

[提示词索引](Prompt_Index_EN_CN.md) · [参考图提示词](Reference_Prompts.md) · [制作修正提示词](Production_Prompts.md) · [图片来源](Credits_EN_CN.md)

## 参考图目录

外部参考 1–9、20–25，来自网上搜集，多数经由 ArtStation 找到。

![外部参考目录](<../assets/process/external_reference_gallery.jpg>)

其余选定文件用于圆环结构、细节和布局参考。

![圆环结构参考目录](<../assets/process/structure_reference_gallery.jpg>)
