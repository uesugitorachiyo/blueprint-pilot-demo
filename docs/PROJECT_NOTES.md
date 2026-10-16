# Project status and media notes

## Current development

Blueprint Pilot is a vertical AI application in development by Harufumi Nomura / Nomura Automation. Harufumi led the design, implementation, debugging and review, with Codex and Gemini coding assistance.

House modeling is working in the Gemini prototype. **Phase 2 refinement of the combined house, site and landscape workflow is the current focus.** Both prototypes continue to evolve. Application source and architectural project data remain private.

## Three-phase roadmap

| Phase | Scope | Status |
| --- | --- | --- |
| **1. House modeling** | Develop a 3D house from 2D blueprints, with drawing-linked components and geometry review. | Working in the Gemini prototype; refinement continues. |
| **2. Site and landscape** | Combine the house with a modeled site and landscape for site planning and visualization. | Current development and refinement focus in the Gemini prototype. |
| **3. Interior visualization** | Integrate realistic interior walkthroughs and photorealistic interior generation for customer presentations and future real-estate listing media, including Zillow postings. | Planned integration; the walkthrough and interior examples illustrate the visual direction. |

The goal is a connected journey from blueprint review to presentation of the envisioned finished home. Existing interior examples demonstrate the intended visual experience; the integrated phase 3 workflow remains planned.

## Videos

| Material | Source | Role in the showcase |
| --- | --- | --- |
| Application demonstration | [Watch the application demo](https://youtu.be/gYKAEUHcBgE) | A recorded project presentation. The cover uses an exterior example rather than an asserted video frame. |
| Interior walkthrough | [Watch the interior walkthrough](https://youtu.be/ncRuzYWc3oc) | A separate recording illustrating the planned phase 3 experience. The cover is a designed title card. |

The recordings have not been matched to either latest prototype build. The interior walkthrough is presented as a preview of the intended product experience; integration into Blueprint Pilot remains planned.

## Photorealistic interior examples

| Example | Original image | Presentation focus |
| --- | --- | --- |
| Kitchen | [Kitchen](../assets/images/interiors/kitchen_photorealistic.jpg) | Wood cabinetry, central island and white countertops. |
| Living room: TV view | [Living room facing the TV](../assets/images/interiors/living_room_tv_photorealistic.jpg) | Seating, media console and interior arrangement. |
| Living room: patio view | [Living room facing the patio](../assets/images/interiors/living_room_patio_photorealistic.jpg) | Seating and the connection to the patio. |
| Primary bedroom | [Primary bedroom](../assets/images/interiors/master_bedroom_photorealistic.jpg) | Bedroom layout, windows, materials and lighting. |

All four supplied interior JPEGs are 1264 x 848. They illustrate the phase 3 visual direction for customer presentations and future listing media. Their presence does not imply that an integrated interior-generation workflow is already available.

## Exterior examples

| View | Original image | Description |
| --- | --- | --- |
| Front-left | [FL](../assets/images/fl.jpg) | Entry and fountain side. |
| Front-right | [FR](../assets/images/fr.jpg) | Deck and pergola side. |
| Rear-right | [RR](../assets/images/rr.jpg) | Pool and garden side. |
| Rear-left | [RL](../assets/images/rl.jpg) | Garage and driveway side. |

The four historical AI-assisted exterior JPEGs are 1376 x 768. View labels follow the supplied filenames. Photorealistic generation work in the Codex-assisted prototype is currently on hold; this is separate from the broader phase 3 roadmap.

## Technical context

Visual appearance is separate from geometric fidelity. Images and recordings do not establish source-plan accuracy, consistent geometry across views, collision-free navigation or construction compliance. Independent architectural benchmarking remains future work.

[Prototype details](DEVELOPMENT_TRACKS.md) describe the implementation tracks and phase 2 focus. [Technical details](TECHNICAL_CASE_STUDY.md) cover architecture, design decisions and the proposed evaluation protocol. See the [usage notice](../NOTICE.md) for showcase scope and media permissions.

[Back to Blueprint Pilot](../README.md)
