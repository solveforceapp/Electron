# Electron – AI Agent Guide

Purpose: Build a static HTML site themed for SolveForce and Unified Intelligence, focused on "Electron" as it relates to SolveForce's services.

## Architecture
- Single-page static site: `index.html` with inline CSS using SolveForce’s purple gradient (hex 667eea → 764ba2) and translucent white overlays.
- No frameworks, no build tools, no package.json. Pure static assets only.

## Key files
- `index.html` – main content, SEO, and styles.
- `assets/` – static images, SVGs, or media (optional).

## Content requirements
- Site must clearly reflect "Electron" as it relates to SolveForce’s unified intelligence and telecom/IT solutions.
- Use concise, SEO-friendly copy in `<head>` and main headings.
- Include a summary of how "Electron" fits into SolveForce’s portfolio.
- Add contact or call-to-action section referencing SolveForce.

## Dev workflow
- Open `index.html` in a browser to preview.
- For local server: `python -m http.server` (optional).

## Deploy (Cloudflare Pages)
- Framework preset: None
- Root Directory: repository root (with `index.html`)
- Build command: leave empty
- Output directory: leave empty

## Conventions
- Use SolveForce’s color system: gradient (667eea → 764ba2), white overlays.
- Keep markup accessible and semantic.
- Reference assets with relative paths.

## Pitfalls to avoid
- Do not add package managers, frameworks, or build steps.
- Avoid large, unoptimized media.

## Quick edits
- All changes in `index.html`.
- Place new assets in `assets/`.

---

**Example:**
The site should explain SolveForce’s approach to "Electron" (e.g., electron-based communications, quantum technologies, or related services), its role in unified intelligence, and provide a SolveForce contact/CTA.
