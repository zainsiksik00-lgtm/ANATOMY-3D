# Anatomy 3D — Phase 1

A standalone web application foundation for a specialist-level interactive human anatomy atlas.

## Current Phase 1 scope

- Responsive React + TypeScript application shell.
- Anatomy systems navigation for 11 human body systems.
- Three.js / React Three Fiber scene with orbit, zoom, hover and click selection.
- Structure context panel and anatomy-layer UI scaffolding.
- Initial data registry for systems and sample structure categories.

## Important content status

The 3D human figure in this phase is a **stylized interaction placeholder built from geometric primitives**. It is not a medically accurate anatomical model. The layer switches are interface scaffolding and do not yet hide real anatomical meshes. Phase 2 will replace the placeholder with properly segmented, licensed GLB/glTF anatomy assets and implement real layer visibility and structure picking.

No AI provider, Supabase credentials, authentication, clinical content database, or medical reference corpus is configured in Phase 1. These are planned integrations, not active features.

## Requirements

- Node.js 20.19+ or 22.12+
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

## Project structure

```text
src/
  components/AnatomyViewer.tsx
  data/systems.ts
  App.tsx
  main.tsx
  styles.css
```

## Roadmap

1. Phase 1 — Core app shell and 3D interaction foundation.
2. Phase 2 — Real anatomy assets, segmented meshes, layer visibility and precise picking.
3. Phase 3 — Specialist anatomy content, multilingual structure records and references.
4. Phase 4 — AI anatomy tutor with retrieval-grounded answers.
5. Phase 5 — quizzes, flashcards, progress and cloud deployment.

## Medical safety

This application is an educational prototype. It is not validated for diagnosis, treatment decisions, or other clinical use. All anatomical models and educational content must be reviewed against trusted references before release.
