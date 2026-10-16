# Prototype details

Blueprint Pilot has two complementary prototypes developed with Codex and Gemini coding assistance. Harufumi Nomura led their design, implementation, debugging and review. The assistant names identify development tracks.

House modeling is working in the Gemini prototype. Current work focuses on **phase 2: refining the combined house, site and landscape workflow**. Integrated interior walkthroughs and photorealistic interior generation are planned for phase 3; the public walkthrough and interior gallery illustrate that direction.

Implementation details below draw on source inspection from 15 October 2026. Current phase status reflects subsequent project updates; it is separate from independent architectural benchmarking.

## PDF/CAD review: Codex-assisted prototype

This prototype focuses on drawing evidence, geometry correction, project state and traceable camera capture. Saved house-repair projects contain source/evidence records, modeling jobs, model bundles and review state; they are project data rather than the application source root.

Inspected implementation areas include PDF intake, evidence-linked CAD authoring, five-view feature measurements, source/model freshness checks, paired RGB/component-ID capture, semantic PNG handling, project commands and native worker boundaries.

**Stack:** Python, JavaScript, Rust/Tauri, PDFium, CadQuery, NumPy, Trimesh and Shapely, with geospatial dependencies.

The inspected repair bundle contains a correction candidate with pending findings, rather than whole-model engineering approval. Photorealistic generation work in this prototype is on hold. The public interior examples illustrate the wider product direction and do not establish that this prototype has an integrated interior-generation workflow.

## Interactive 3D and site review: Gemini-assisted prototype

This prototype supports drawing/model display and the house-to-site visualization workflow. House modeling is working, with site and landscape integration under refinement.

Inspected code includes PDF viewing, Three.js scene rendering, site-plan projection, camera capture, floor-plan consistency checks and local usage records.

**Stack:** TypeScript, Three.js, PDF.js, Rust/Tauri, Vite and Leaflet.

The inspected reconstruction path loads prebuilt scene assets for known plans, selected using source identity or filename, and includes procedural fallback logic. Working project-specific house modeling does not establish general reconstruction of unseen plans. Floor-section comparisons measure internal scene consistency; independent comparison with source drawings remains a separate evaluation task.

## How the prototypes support the roadmap

| Phase | Prototype contribution | Status |
| --- | --- | --- |
| **1. House modeling** | Gemini house modeling, alongside drawing evidence, geometry review and correction mechanisms across the two prototypes. | House modeling working in the Gemini prototype; refinement continues. |
| **2. Site and landscape** | Gemini house/site display, site-plan projection and combined scene workflows. | Current development and refinement focus. |
| **3. Interior visualization** | Planned integration of realistic interior walkthroughs and photorealistic interior generation. | Separate walkthrough and four interior examples illustrate the intended experience. |

The implementations differ. Source-bound measurements in one prototype are not acceptance evidence for the other. Public recordings and images have not been tied to specific latest builds or used as an independent architectural accuracy benchmark.

Application source, architectural drawings, internal scene bundles and credentials remain private.

[Back to Blueprint Pilot](../README.md) · [Technical details](TECHNICAL_CASE_STUDY.md) · [Project status and media notes](PROJECT_NOTES.md)
