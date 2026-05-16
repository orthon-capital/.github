# Orthon Capital Landing System

This organization contains the production landing website, archived development versions, and visual research assets created for Orthon Capital Management.

The repositories are intentionally separated so the production codebase stays clean while the full design and implementation history remains available.

## Production

**Live site:** https://orthon-v4.prin7r.com

The active implementation is V4, built as an Astro static site with a small Node settings API for global design controls.

## Repository Map

| Repository | Purpose | Status |
| --- | --- | --- |
| [`orthon-landing`](https://github.com/orthon-capital/orthon-landing) | Current production website. Contains the V4 Astro implementation, global settings system, content, assets, and deploy notes. | Active |
| [`orthon-landing-archive`](https://github.com/orthon-capital/orthon-landing-archive) | Frozen V1, V2, and V3 versions. Preserves the design and engineering evolution before V4. | Archive |
| [`orthon-design-lab`](https://github.com/orthon-capital/orthon-design-lab) | Generated imagery, vector gallery, visual experiments, processed assets, and research materials. | Research |
| [`.github`](https://github.com/orthon-capital/.github) | Organization profile and repository overview. | Metadata |

## Current Production Repository

`orthon-landing` is the repository to use for maintenance, deployment, and future production changes.

It includes:

- Astro 6 + TypeScript static site.
- MDX content for performance, research, charity, and careers pages.
- Global design settings with realtime browser sync.
- Motion and image assets used by the live site.
- A small Node API for persisted site-wide settings.
- Deployment patch notes for the settings API container.

## Archive Repository

`orthon-landing-archive` keeps the previous versions available without mixing them into production.

It includes:

- `v1-vite` — early Vite + React implementation and specification work.
- `v2-next` — second major Next.js landing exploration.
- `v3-next` — third major Next.js exploration and visual direction refinement.

These versions are reference material only. Production work should happen in `orthon-landing`.

## Design Lab

`orthon-design-lab` stores the experimental visual work behind the landing direction.

It includes:

- Vector and generative animation gallery.
- Landing image concepts and processed variants.
- Source scripts for image and motion experiments.
- Archived V3 image sets.

Selected production-ready assets should be copied into `orthon-landing` only after cleanup and optimization.

## Handoff Principle

The organization follows one simple rule:

**Production stays compact; exploration stays preserved.**

This keeps the live website maintainable while retaining the creative and technical process that led to it.
