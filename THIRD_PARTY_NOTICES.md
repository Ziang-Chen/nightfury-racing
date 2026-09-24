# Third-party notices / 第三方许可与署名

NIGHTFURY（极夜狂飙）的原创代码按根目录 LICENSE 中的 MIT 许可发布。
第三方模型和库保留各自许可；根目录 MIT 不替代这些许可。

## 3D models — CC BY 4.0

| Files | Work / author | Original source |
| --- | --- | --- |
| dist/models/lamborghini.glb | Lamborghini Aventador — Arion Digital (https://sketchfab.com/andrewswihart) | https://sketchfab.com/3d-models/lamborghini-aventador-888e37a3641d4f7b94bc1a39396e2441 |
| dist/models/bugatti.glb, bugatti-race.glb, bugatti-ai.glb | Bugatti Veyron · Racing Car - Unity&Unreal — DevPoly3D (https://sketchfab.com/DevPoly3D) | https://sketchfab.com/3d-models/bugatti-veyron-racing-car-unityunreal-8517e3271613487ca1cb37832ff54669 |

License: Creative Commons Attribution 4.0 International, https://creativecommons.org/licenses/by/4.0/ .
Full text: dist/licenses/CC-BY-4.0.txt.
Changes: scene scale/orientation/position, runtime paint and lighting adjustments; Bugatti race/AI variants also simplify geometry with meshoptimizer. Packed variants remove unreferenced buffer data and use lossless gzip transport; all referenced geometry and texture bytes are retained. Original author/license/source metadata is retained in GLB assets. These adapted models remain distributed under CC BY 4.0. Include attribution, a license link and modification notices when redistributing.

## Libraries

- Three.js r180, including vendored addons: Copyright 2010–2025 Three.js Authors. MIT, dist/licenses/THREE-MIT.txt. Source: https://github.com/mrdoob/three.js/tree/r180 .
- meshoptimizer 0.22 simplifier (offline asset preparation): Copyright 2016–2024 Arseny Kapoulkine. MIT, dist/licenses/MESHOPTIMIZER-MIT.txt. Source: https://github.com/zeux/meshoptimizer/tree/v0.22 .
- Draco decoder bundled with Three.js: Copyright The Draco Authors. Apache License 2.0, dist/licenses/DRACO-APACHE-2.0.txt and dist/licenses/DRACO-AUTHORS.txt. Source: https://github.com/google/draco .

## Generated concept artwork

Map covers and the NIGHTFURY poster in dist/covers were generated with OpenAI ImageGen for this project. Prompts and generation notes are included alongside the images. These are concept illustrations, not game screenshots. The project offers its rights, if any, in these generated assets under the MIT license. This does not change the separate CC BY 4.0 licenses of the car models.

## Names and trademarks

汽车名称、商标和外观的权利属于相应权利人，不因代码或模型许可而转让。
这是独立的浏览器赛车项目，不代表汽车厂商或模型作者赞助、认可本项目。
游戏性能参数是玩法设定，并非真实车辆实测数据。

## PBR textures — CC0 1.0

Color, OpenGL normal and roughness textures in dist/textures are from Poly Haven.
License: https://creativecommons.org/publicdomain/zero/1.0/ . Official asset license: https://polyhaven.com/license .

- rock_face — Greg Zaal, Dario Barresi — https://polyhaven.com/a/rock_face
- asphalt_02 — Rob Tuytel — https://polyhaven.com/a/asphalt_02
- snow_02 — Rob Tuytel — https://polyhaven.com/a/snow_02
- forest_ground_04 — Rob Tuytel, Rico Cilliers — https://polyhaven.com/a/forest_ground_04
- dark_rock_02 — Amal Kumar — https://polyhaven.com/a/dark_rock_02

Changes: color maps use the official 2K variant, normal and roughness maps use 1K variants. JPEG files are re-encoded for web delivery without changing pixel dimensions. Original source URLs, source MD5 checksums, authors, local SHA-256 checksums and modification notes are in dist/textures/sources.json.

Engine, wind, nitro, tires, collisions and interface tones are synthesized by original Web Audio code. Licensed CC0 music recordings are listed below.


## Added 2K environment materials — Poly Haven CC0 1.0

Willow bark: Dario Barresi and Dimitrios Savva (https://polyhaven.com/a/bark_willow). Grey wooden planks: Rob Tuytel (https://polyhaven.com/a/wood_planks_grey). White castle bricks: Rob Tuytel (https://polyhaven.com/a/castle_brick_02_white). Color, OpenGL normal, roughness and ambient-occlusion maps retain their original 2K JPEG data. The runtime tiles them in world space and blends their appearance with authored colors. License: https://polyhaven.com/license . Full provenance: licenses/texture-sources.json.


## Canyon surface materials — Poly Haven CC0 1.0

- Sandstone Cracks (sandstone_cracks) — Rob Tuytel — https://polyhaven.com/a/sandstone_cracks
- Cobblestone Floor 08 (cobblestone_floor_08) — Rob Tuytel — https://polyhaven.com/a/cobblestone_floor_08
- White Plaster Rough 02 (white_plaster_rough_02) — Rob Tuytel — https://polyhaven.com/a/white_plaster_rough_02

License: Creative Commons CC0 1.0 Universal, https://creativecommons.org/publicdomain/zero/1.0/ . Official asset license: https://polyhaven.com/license .

The canyon uses these official 2K surface maps for roads, rock formations and building materials, including textures embedded in GLB models. Changes: authored color tints; painted-plaster color variants derived from the scan's luminance; UV tiling and normal-strength adjustments; Blender texture embedding and roughness-channel packing for glTF materials. Canyon model transport uses lossless gzip. The already credited Brown Mud 03, Grey Wooden Planks and White Castle Bricks are also reused; their author and license entries above and below continue to apply. Project-authored geometry and scene-lighting atlases are separate from the source texture licenses.

## Recorded soundtrack — CC0 1.0

Six tracks are bundled for map-specific EDM/cyberpunk/synthwave music. Each author page explicitly grants CC0. Re-encoded as stereo MP3 (LAME V2); adjusted to approximately -18 LUFS, with short trailing silence removed from New Factory and System Overload. Full provenance, hashes and processing: licenses/music-sources.json. Original synthesized compositions remain a fallback if a recording cannot play.

- New Factory — Alexander Ehlers (tricksntraps) · https://opengameart.org/content/t-t-free-cyberpunk-pack-2
- System Overload — Alexander Ehlers (tricksntraps) · https://opengameart.org/content/t-t-free-cyberpunk-pack-2
- Space Adventure — MintoDog · https://opengameart.org/content/space-adventure
- Empacotatron (Loop) — Fupi · https://opengameart.org/content/empacotatron
- Pure Raceway — MintoDog · https://opengameart.org/content/pure-raceway
- 160BPM Electronic Loop — RUOK · https://opengameart.org/content/160bpm-electronic-loop

License: https://creativecommons.org/publicdomain/zero/1.0/

Brown Mud 03 — Rob Tuytel (https://polyhaven.com/a/brown_mud_03), Poly Haven CC0 1.0. The original 2K JPEG colour, OpenGL normal, roughness, ambient-occlusion and displacement maps are used for local forest surface relief and wetness. Original pixels are retained; processing occurs in the runtime shader. The source hashes are recorded in the texture manifest.


## Forest understory and pinball finishes (September 2026)

Fern 02 — Rob Tuytel (scanning), Rico Cilliers (modeling), https://polyhaven.com/a/fern_02, CC0 1.0. All four original mesh variants and original 2K color/OpenGL-normal/ARM pixels are retained. The runtime extracts mesh descriptors and grounds/scales instances; ARM green is used as roughness. See licenses/forest-fern-sources.json.

Metal Plate — Rob Tuytel, https://polyhaven.com/a/metal_plate, CC0 1.0. Original 2K color, normal and roughness maps are world-space projected onto explicit pinball material slots. Brushed steel and rubber normal/roughness maps are original deterministic project artwork. See licenses/pinball-sources.json.

All ten September 2026 map-selection covers are individually generated with OpenAI ImageGen. They are concept illustrations, not captures of the realtime renderer.


The pinball static world includes original project Blender geometry and the original procedural metal-deck module from the project's material lab. Metal Plate scan maps retain the CC0 attribution above; numerical brushed-steel/rubber maps are project artwork. Blender exports embed these textures without reducing resolution. The runtime GLB uses lossless gzip packaging. Three.js RectAreaLight lookup tables and uniform helpers are distributed under the existing Three.js MIT license.


## AssemblyScript

The WASM track core uses AssemblyScript standard-library math implementations. See licenses/ASSEMBLYSCRIPT-NOTICE.txt and licenses/ASSEMBLYSCRIPT-APACHE-2.0.txt.
