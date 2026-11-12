# Architect Inspire (A.I.)

**Describe your dream home - get floor plans, a 3D model, a cost estimate and preliminary drawings.**

Architect Inspire is an AI home architect. Describe the home you want in words, with reference
images or sketches - even creative wishes like a circular Japanese window or a firefighter pole -
optionally on a real lot drawn on a map. The app generates concept designs (2D floor plan and
3D model), analyzes the site and climate, gives regional design advice, estimates the
construction cost by materials, and produces a preliminary drawing set (PDF, DXF, IFC) that an
architect can continue. Designs can be saved, shared and remixed in a community gallery.

## How it works

The core principle: **the LLM decides *what*, deterministic code decides *how much* and *where*.**
AI agents understand the user's needs, images and creative requests; a constraint solver
(Google OR-Tools) places the rooms; rule-based validators and an AI critic check the result;
cost and drawings are computed from the real geometry.

## Status

Planning. Progress is tracked in [milestones](../../milestones) and [issues](../../issues).

| Phase | |
|---|---|
| 0. Setup | Planned |
| 0.5 UX wireframes | Planned |
| 1. MVP core | Planned |
| 2. Cost v1 | Planned |
| 3. Map + site | Planned |
| 4. Smart design | Planned |
| 5. Cost v2 | Planned |
| 6. 3D + drawings | Planned |
| 7. Evaluation | Planned |
| 8. Community + ship | Planned |
| 9. Pro handoff (stretch) | Planned |

## Tech stack

Python, FastAPI, Pydantic, OR-Tools, Shapely, GitHub Models / Gemini, ChromaDB,
React, TypeScript, Leaflet, Three.js, ezdxf, IfcOpenShell, Figma, Docker, GitHub Actions, Azure.

## Disclaimer

Designs, cost estimates and drawings are **preliminary**. Permit-ready construction plans must be
reviewed and signed by a licensed architect or engineer. Always get quotes from contractors.

## License

MIT
