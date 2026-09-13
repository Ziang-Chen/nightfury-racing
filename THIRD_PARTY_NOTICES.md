# Third-party notices / 第三方许可与署名

NIGHTFURY（极夜狂飙）的原创代码按根目录 LICENSE 中的 MIT 许可发布。
第三方模型和库保留各自许可；根目录 MIT 不替代这些许可。

## 3D models — CC BY 4.0

| Files | Work / author | Original source |
| --- | --- | --- |
| dist/models/lamborghini.glb | Lamborghini Aventador — Arion Digital (https://sketchfab.com/andrewswihart) | https://sketchfab.com/3d-models/lamborghini-aventador-888e37a3641d4f7b94bc1a39396e2441 |
| dist/models/bugatti-race.glb, bugatti-ai.glb | Bugatti Veyron · Racing Car - Unity&Unreal — DevPoly3D (https://sketchfab.com/DevPoly3D) | https://sketchfab.com/3d-models/bugatti-veyron-racing-car-unityunreal-8517e3271613487ca1cb37832ff54669 |

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

Engine, wind, nitro, tires, collisions and interface tones are synthesized by original Web Audio code. No third-party audio recordings are bundled.
