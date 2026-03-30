# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

Marketing website for **Elyt** (formerly "AutoFlow" — the product was renamed to Elyt), built from the "Astrolus" Astro template with Tailwind CSS (Tailus blocks). This repo is **only the marketing site**, not the Elyt product codebase. Note: many reference docs in this repo still use the old "AutoFlow" name — treat any mention of "AutoFlow" as referring to Elyt.

### Product Context (read these before writing copy or making design decisions)

- `Elyt_Readme.md` — Full product overview: architecture, features, tech stack
- `AppSummary.md` — Product summary with target personas (Botters, Web Scrapers, Growth Hackers, Power Users) and key differentiators (mass automation, anti-detection, AI humanization, workflow system)
- `B2C-landing-page-research.md` — B2C conversion research and landing page strategy
- `2025-WEBSITE-CONTENT.md` — Persona-specific landing page content strategy
- `2025-CONTENT-CREATION.md` — Content creation and E-E-A-T strategy
- `2025-SEO-GEO-AUTOFLOW_STRATEGY.md` — SEO strategy overview

### Key Product Differentiators (for copy/messaging)

1. **Mass AI browser automation** — automate across infinite profiles, not just one browser
2. **Anti-detection technology** — paired with anti-detect browsers (AdsPower, MoreLogin, GoLogin)
3. **AI humanization** — mouse movements, typing patterns, behavioral mimicry
4. **Workflow system** — complex multi-node automation with scheduling

### Competitive Context

Competitors (browser-use.com, fellou.ai, airtop.ai, skyvern.com) offer AI browser automation but lack anti-detection, mass profile orchestration, and workflow systems.

## Commands

```bash
pnpm install          # Install dependencies (uses pnpm, see .npmrc)
pnpm dev              # Dev server (localhost:4321)
pnpm build            # Production build to ./dist/
pnpm preview          # Preview production build locally
```

No test runner or linter is configured in this repo. Prettier is available but has no script — run manually with `npx prettier --write .` if needed.

## Architecture

- **Framework:** Astro 5.x with static output (`astro.config.mjs`: `output: "static"`)
- **Styling:** Tailwind CSS v4 beta via Vite plugin (`@tailwindcss/vite`)
- **Theme colors:** Primary = indigo-600, Secondary = orange-600, Info = blue-600 (defined in `src/tailus.css` via `@theme`)
- **Font:** Urbanist (Google Fonts, loaded via `astro-font` in Layout)
- **CSS entry:** `src/tailus.css` (imported in Layout)

### Page Composition

Single-page marketing site. `src/pages/index.astro` composes sections in order:

1. HeroSection
2. Features
3. Stats
4. Testimonials
5. CallToAction
6. Blog

`src/layouts/Layout.astro` wraps everything with: `<head>` (fonts, meta), `<AppHeader>`, `<slot>`, `<AppFooter>`.

### Static Assets

```
public/
├── Elyt/images/         # Product screenshots and visuals
├── Elyt/videos/         # Product demo videos
├── images/avatars/      # Testimonial/team avatars
├── images/clients/      # Client/partner logos
└── favicon.svg
```

## Available Skills

- `/copywriting` — Write landing page headlines, CTAs, hero copy
- `/copy-editing` — Polish and tighten existing copy
- `/page-cro` — Optimize the landing page for conversions
- `/product-marketing-context` — Define product positioning (feeds into the other skills)

## Available MCP Servers

- **astro-docs** (`mcp__astro-docs__search_astro_docs`) — Search Astro documentation for Astro-specific questions, configuration, or APIs

## Conventions

- **Prettier:** `printWidth: 1000`, `tabWidth: 4`, Tailwind class sorting plugin
- All components are `.astro` files (no React/Vue/Svelte)
- Dark mode supported via Tailwind `dark:` variants (body has `dark:bg-gray-950`)
- `Layout.astro` `<title>` and `<meta description>` are still template defaults — update when customizing
