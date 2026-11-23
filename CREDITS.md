# Credits

| Asset | Author / source | Licence | Where |
|---|---|---|---|
| Car Concept (glTF) | Eric Chadwick, Darmstadt Graphics Group, 2024 — Khronos glTF-Sample-Assets | CC BY 4.0 (Khronos / 3D Commerce logos removed, licence excludes trademarks) | `game/public/models/car/car.glb` (source: `game/assets-src/car/`) |
| snow_02, snow_03, brown_mud_dry, brown_mud_02, rock_face_03, concrete_floor_02, pine_bark | Poly Haven | CC0 1.0 | `game/public/tex/` (sources: `game/assets-src/textures/`) |
| snow_field, snowy_field HDRIs | Poly Haven | CC0 1.0 | `game/public/hdri/` |
| three.js | three.js authors | MIT | npm |
| Rapier (@dimforge/rapier3d-compat) | Dimforge | Apache-2.0 | npm |
| JetBrains Mono | JetBrains | SIL OFL 1.1 | Google Fonts |
| Sedan, van, mannequins, trees, town furniture, Cyrillic signs, sounds | procedural / original (this project) | — | `game/src/` |

Not yet sourced: realistic downloaded models for the old sedan and the van (currently procedural stand-ins).

## Realistic human assets (Track C: game/public/models/human, game/assets-src/human)
- **MakeHuman / MPFB2 system assets** (base mesh, modelling targets, skins, eyes, eyebrows, eyelashes, hair, shoes, game_engine rig weights): CC0 1.0. Copyright released by Data Collection AB, Joel Palmius, Jonas Hauquier and the MakeHuman community. https://static.makehumancommunity.org/assets/assetpacks/makehuman_system_assets.html and https://github.com/makehumancommunity/mpfb2 (v2.0.18, add-on code is GPL-3.0; it was only run as a tool in Blender, none of its code ships).
- **Z-Anatomy** (skeleton, organs, vessels, muscles, eyeballs, brain: FBX models from https://github.com/LluisV/Z-Anatomy, branch PC-Version, Resources/Models/FBX): by Lluís Vinent Juanico and the Z-Anatomy project (based on BodyParts3D, © The Database Center for Life Science, CC BY-SA 2.1 JP). Licence: **CC BY-SA 4.0**. The interior meshes in `game/public/models/human/*_interior.glb` are derivative works (merged, decimated, re-fitted to each body, rigged) and are therefore also released under **CC BY-SA 4.0**.
- Garment shells, fabric/tissue/skin-detail normal maps, the game rig, interior fitting and the viewer are original work made for this project.

## Weapons and tools (Track E: game/public/models/weapons, game/assets-src/weapons)
- **service_pistol**, **bolt_action_rifle_7_62**, **stick_grenade** glTF models: Poly Haven (https://polyhaven.com), **CC0 1.0**. Re-parented, renamed parts and reference empties added (`game/tools/weapons/prep_polyhaven.py`).
- **AK-74, IZh-43 shotgun, RGD-5, TNT remote charge + detonator remote, MPL-50 shovel, spent casings**: original models made for this project in Blender 5.1 (`game/tools/weapons/*.py`), procedural materials baked to textures. Same licence as the project.
- Weapon/tool code, particles, decals, procedural gun/explosion/foley sounds (Web Audio, no samples): original work (`game/src/weapons`, `game/src/tools`).

## Character animation (game/public/anim, game/assets-src/quaternius)
- **Universal Animation Library [Standard]** (Godot GLB, 46 clips; 31 kept, retargeted to the game rig by `game/tools/anim/retarget.mjs`): by **Quaternius** (https://quaternius.com, https://www.patreon.com/quaternius), **CC0 1.0**. Licence text: `game/assets-src/quaternius/License.txt`.
