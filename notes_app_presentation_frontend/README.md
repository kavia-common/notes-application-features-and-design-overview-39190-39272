# Notes App Presentation (Slidev)

Ocean Professional themed presentation describing the Notes App features, design, and flow.

Quick start:
- Install deps: `pnpm install` (or `npm install`, `yarn`)
- Start dev server: `pnpm dev` (or `npm run dev`, `yarn dev`)
- Open: http://localhost:3000 (the Vite server is configured to run on port 3000)

Editing:
- Main deck: edit [slides.md](./slides.md)
- Theme styles: edit [style.css](./style.css) → [theme/custom.css](./theme/custom.css)
  - Palette:
    - Primary: #2563EB
    - Secondary/Success: #F59E0B
    - Error: #EF4444
    - Background: #f9fafb (mapped to a modern dark canvas for contrast)
    - Surface: #ffffff (mapped to elevated surfaces)
    - Text: #111827 (mapped to high-contrast light text on dark canvas)
- Use Slidev components (icons, code blocks, Mermaid) directly in slides.

Environment variables (optional):
- VITE_API_BASE, VITE_BACKEND_URL, VITE_FRONTEND_URL, VITE_WS_URL
- VITE_NODE_ENV, VITE_NEXT_TELEMETRY_DISABLED, VITE_ENABLE_SOURCE_MAPS
- VITE_PORT (port is managed by vite.config.ts set to 3000), VITE_TRUST_PROXY, VITE_LOG_LEVEL
- VITE_HEALTHCHECK_PATH, VITE_FEATURE_FLAGS, VITE_EXPERIMENTS_ENABLED

Examples in slides show how to read env vars via `import.meta.env`.

Build:
- `pnpm build` → static output in `dist/`
- `pnpm export` → export to PDF

Docs:
- Slidev: https://sli.dev/
