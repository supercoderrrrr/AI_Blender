# Megastructure — Blender Delivery

## English

Three Blender projects are prepared for presentation and sharing. Their filenames do not contain revision numbers. Download the three projects from the linked release.

| File | Purpose | Startup scene |
| --- | --- | --- |
| [Megastructure_Final_Scene.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Megastructure_Final_Scene.blend) | Approved environment, camera, lighting, atmosphere and final color finish | `Megastructure \| Final Daylight` |
| [Industrial_Ring_Clay.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Industrial_Ring_Clay.blend) | Final ring geometry with a neutral clay material override | `Industrial Ring \| Clay Study` |
| [Industrial_Ring_Material_Showcase.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Industrial_Ring_Material_Showcase.blend) | Isolated final ring with materials, practical lights, studio lighting and ten saved views | `01 \| Ring - Three Quarter` |

### Final image

[Megastructure_Final.png](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Megastructure_Final.png) is the approved 3840 × 2160, 16-bit RGB image, copied directly from the final delivery.

The final project contains four scenes:

- `Megastructure | Final Daylight`: editable 3D environment with the approved camera and lighting. F12 renders the environment using EEVEE at 4K, 192 samples.
- `Final Image | Region Assembly`: recomposes the packed, full-resolution render strips used for delivery. This is the simplest way to reproduce the final image with a smaller memory requirement.
- `Planet Pass | Jupiter` and `Planet Pass | Neptune`: editable source spheres. After changing and rendering a planet, update its image node in the main scene's compositor manually.

### Ring presentation images

Start with [Ring_Showcase_Overview.jpg](../assets/renders/Ring_Showcase_Overview.jpg). The gallery links below open web previews; the approved 4K final image is available separately in the release.

| View | Saved scene | Image |
| --- | --- | --- |
| Three-quarter | `01 \| Ring - Three Quarter` | [01_Ring_ThreeQuarter.png](../assets/renders/01_Ring_ThreeQuarter.jpg) |
| Front | `02 \| Ring - Front` | [02_Ring_Front.png](../assets/renders/02_Ring_Front.jpg) |
| Rear | `03 \| Ring - Rear` | [03_Ring_Rear.png](../assets/renders/03_Ring_Rear.jpg) |
| Upper crown | `04 \| Detail - Upper Crown` | [04_Upper_Crown.png](../assets/renders/04_Upper_Crown.jpg) |
| Suspended core | `05 \| Detail - Suspended Core` | [05_Suspended_Core.png](../assets/renders/05_Suspended_Core.jpg) |
| Side platform | `06 \| Detail - Side Platform` | [06_Side_Platform.png](../assets/renders/06_Side_Platform.jpg) |
| Platform underside | `07 \| Detail - Platform Underside` | [07_Platform_Underside.png](../assets/renders/07_Platform_Underside.jpg) |
| Base assembly | `08 \| Detail - Base Assembly` | [08_Base_Assembly.png](../assets/renders/08_Base_Assembly.jpg) |
| Inner light channel | `09 \| Detail - Inner Light Channel` | [09_Inner_Light_Channel.png](../assets/renders/09_Inner_Light_Channel.jpg) |
| Mechanical pivot | `10 \| Detail - Mechanical Pivot` | [10_Mechanical_Pivot.png](../assets/renders/10_Mechanical_Pivot.jpg) |

The three full views are 2560 × 2560. Detail images are 2048–2560 pixels wide. All individual renders are 16-bit RGB PNGs, rendered with Cycles, 192 samples and denoising. Select a scene from Blender's scene selector, then press F12 to render that saved view. Enable a suitable Cycles device on your computer; these images were rendered with OptiX on an RTX 4060 Laptop GPU.

[Industrial_Ring_Clay.png](../assets/renders/Industrial_Ring_Clay.jpg) uses the same geometry and three-quarter camera as the material version. The clay effect is a view-layer material override; the original materials remain editable.

### Materials and file integrity

The independent studio uses lower fill light and corrected practical-light energy for the ring's local scale. World-coordinate procedural textures are mapped back to their coordinates in the environment so their pattern size matches the final scene. The model retains its final materials, warning stripes and industrial emission panels. Studio lighting changes how the surfaces appear compared with the blue daylight and haze in the environment.

All file-based images used by these projects are packed. There are no linked external Blender libraries. Geometry, local transforms and assembly parents were checked against the final source. The empty assembly control used by the suspended unit is retained as a dependency. Files were opened and checked in Blender 5.2.2 LTS. A 4K assembly check differed from the delivered image by at most 2/255 per channel when compared at 8-bit precision; the provided final PNG is an exact copy of the approved image.

The three Blender projects contain their image dependencies. Render output paths are relative to the project files; create a `renders/` folder next to them when saving new renders.

---

## 中文

三份工程已整理为方便展示和分享的名称，不带版本号。通过链接中的 Releases 下载三份工程。

| 文件 | 用途 | 默认打开的场景 |
| --- | --- | --- |
| [Megastructure_Final_Scene.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Megastructure_Final_Scene.blend) | 最终环境，保留批准的相机、光照、雾和调色 | `Megastructure \| Final Daylight` |
| [Industrial_Ring_Clay.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Industrial_Ring_Clay.blend) | 最终圆环几何的白模展示 | `Industrial Ring \| Clay Study` |
| [Industrial_Ring_Material_Showcase.blend](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Industrial_Ring_Material_Showcase.blend) | 独立材质圆环、工业灯光、摄影棚灯光和十个展示机位 | `01 \| Ring - Three Quarter` |

### 最终成图

[Megastructure_Final.png](https://github.com/supercoderrrrr/AI_Blender/releases/download/1.0/Megastructure_Final.png) 是原最终交付图的直接副本，3840 × 2160、16 位 RGB。

最终场景文件内保留四个场景：

- `Megastructure | Final Daylight`：可编辑的三维环境，保留终稿相机和光照。F12 使用 EEVEE，以 4K、192 采样渲染。
- `Final Image | Region Assembly`：用已打包的完整分辨率分区渲染重组终稿，内存需求较小。
- `Planet Pass | Jupiter` 和 `Planet Pass | Neptune`：保留可编辑的行星球体。修改并重渲行星后，需要手动替换主场景合成器中的对应图像节点。

### 圆环展示图

先看 [Ring_Showcase_Overview.jpg](../assets/renders/Ring_Showcase_Overview.jpg)。下方链接提供单张网页预览；批准的 4K 场景图在 Releases 中单独提供。

共十张：三分之四、正面、背面，以及顶部吊装、悬挂核心、侧平台、平台底部、底座、内圈灯槽和机械转轴七张细节。英文部分的表格列出了对应场景和图片链接。

完整圆环为 2560 × 2560；细节图宽度为 2048–2560 像素。单张均为 16 位 RGB PNG，使用 Cycles、192 采样和降噪。通过 Blender 顶部的场景选择器切换机位，然后按 F12 重渲。请按自己电脑的硬件设置 Cycles 设备；本次使用 RTX 4060 Laptop GPU 的 OptiX 渲染。

[Industrial_Ring_Clay.png](../assets/renders/Industrial_Ring_Clay.jpg) 与材质版使用同一套最终几何、同一个三分之四机位。白模通过视图层材质覆盖实现，原材质仍可编辑。

### 材质和完整性

展示版降低了补光，并按独立模型的尺寸换算局部灯光能量。世界坐标程序纹理映射回原环境中的坐标，恢复了终稿的纹理比例。最终材质、警示条纹和工业发光面板均保留；摄影棚灯光与场景中的蓝色日光和雾会带来不同的表面观感。

文件使用的图像均已打包，没有外部链接的 Blender 库。几何、局部变换和装配父级已与终稿核对，悬挂装配使用的空物体控制器也已保留。三份文件均在 Blender 5.2.2 LTS 中重新打开检查。4K 合成校验图与交付图按 8 位精度比较，每通道最大差异为 2/255；提供的最终 PNG 则与原批准图完全一致。

三份 Blender 工程包含自身的图像依赖。渲染输出路径相对于工程文件；保存新渲染时，在工程旁建立 `renders/` 文件夹。
