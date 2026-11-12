# Realistic reef fish

Model: **Barramundi Fish**, Microsoft (2017), published by Khronos Group.

- Exact source: https://github.com/KhronosGroup/glTF-Sample-Assets/tree/8f492390ddc7a2ae221a1369ef560589cf8c70fb/Models/BarramundiFish
- Original file: `glTF-Binary/BarramundiFish.glb` at that revision.
- File-level license evidence: the model directory's `README.md`, Legal section, identifies Microsoft and Creative Commons Zero v1.0 Universal.
- License: **CC0 1.0 Universal**, https://creativecommons.org/publicdomain/zero/1.0/legalcode
- Original SHA-256: `ecc3bafb6b00f2c8b810863c388e3768a7b7ea0d0335e8cb8c574c266e571f4a`.
- Delivered file: `models/fish/realistic-barramundi.glb`.
- Delivered SHA-256: `69d34aae9a0476bb76a0f937456c63581664b8c236ed1b51399e01410e02c3d3`.

Modifications by Mindverve: reduced the three textures to 1024 pixels and JPEG 4:4:4; restrained PBR metalness/roughness; added two tail morph targets and a calm 1.8-second looping animation. The original has no rig or animation. Original mesh topology/UVs are retained: 3,864 triangles. The delivered model and these model adaptations are supplied under CC0 1.0. Attribution is not required by CC0; the Microsoft credit is retained for provenance.

The 360 scene uses 24 instances: twelve barramundi, eight common clownfish and four solitary longsnout seahorses. These are three independent species and original meshes. The old numerical fish and unidentified reef GLBs are not used by the 360 fish population. This model's CC0 notice and the panorama's separate CC BY-SA notice do not relabel unrelated application code.

## common-clownfish — Amphiprion ocellaris

Creator: Innerscene Corp. Original publisher: https://www.innerscene.com/tools/library/3d-parts/common-clownfish-864bbb68

Public download: https://www.innerscene.com/api/library/common-clownfish-864bbb68/download

Exact file-level copyright inside the original GLB identifies Innerscene Corp and dedicates the file under CC0 1.0 Universal. The publisher's model page confirms original authorship and CC0; https://www.innerscene.com/tools/library/terms (contributor agreement version 2026-09-24) confirms redistribution and modification for any purpose. License text: https://creativecommons.org/publicdomain/zero/1.0/legalcode . Attribution is not required; the creator credit is retained for provenance.

Original SHA-256: 5e6481eab1a817b14f80f857f6157a54733f6e2ae887af52a9c8b022d3c06895; 4931012 bytes.

Delivered path: models/fish/realistic-common-clownfish.glb. Optimized SHA-256: b6fa3318fd33c0330172b2e32c81457059bfa0bb61378bd524ea5ab2c0446939; 1316724 bytes, 11582 triangles (source 49476).

Modifications: mesh simplification with existing meshoptimizer tooling (no runtime decoder or new dependency), vertex compaction, textures capped at 1024px with small eye maps at 128px, source transforms retained under a centered axis/size normalization node. Added original CalmBodyTailSwim morph animation: body/tail motion for clownfish; low-amplitude tail flex plus dorsal and pectoral fin flutter for seahorse. These adaptations are CC0 1.0. Surface maps and separate anatomical parts retained.

## longsnout-seahorse — Hippocampus reidi

Creator: Innerscene Corp. Original publisher: https://www.innerscene.com/tools/library/3d-parts/longsnout-seahorse-c841c773

Public download: https://www.innerscene.com/api/library/longsnout-seahorse-c841c773/download

Exact file-level copyright inside the original GLB identifies Innerscene Corp and dedicates the file under CC0 1.0 Universal. The publisher's model page confirms original authorship and CC0; https://www.innerscene.com/tools/library/terms (contributor agreement version 2026-09-24) confirms redistribution and modification for any purpose. License text: https://creativecommons.org/publicdomain/zero/1.0/legalcode . Attribution is not required; the creator credit is retained for provenance.

Original SHA-256: 10266a6796138b09203dadcafb57dadfc659247705158f60e28f7cc36984e5bf; 6878744 bytes.

Delivered path: models/fish/realistic-longsnout-seahorse.glb. Optimized SHA-256: 92e9293b3dea8c733609acc2f66d043a62ccf430336dd69be10a2bd615ba20f4; 1512188 bytes, 15924 triangles (source 69760).

Modifications: mesh simplification with existing meshoptimizer tooling (no runtime decoder or new dependency), vertex compaction, textures capped at 1024px with small eye maps at 128px, source transforms retained under a centered axis/size normalization node. Added original CalmDorsalAndTailSwim morph animation: body/tail motion for clownfish; low-amplitude tail flex plus dorsal and pectoral fin flutter for seahorse. These adaptations are CC0 1.0. Surface maps and separate anatomical parts retained.

These are generalized anatomical study models, not animal scans. The seahorse is a tropical western Atlantic species; this is an interpretive mixed marine cast, not an assertion that every species is native to the Heron Bommie photo location. The original photographic panorama CC BY-SA notice remains separate from these CC0 models and unrelated application code.
