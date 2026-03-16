# Project instructions (preview)

This repo is a static site (index.html + styles.css + script.js).

Preview locally in Codex Cloud:
1) npm install
2) npm run dev
3) Open http://localhost:3000/

If preview shows "Not Found", verify the dev server is running on port 3000 and binds to 0.0.0.0.

## Cursor Cloud specific instructions

- **Stack**: Pure static site served by Vite. Single `index.html` with all CSS/JS inline. No backend, no database, no external services.
- **Dev server**: `npm run dev` starts Vite on `http://localhost:3000` (bound to `0.0.0.0`). No lint or test scripts are configured; the only meaningful checks are `npm run build` and manually verifying the site in a browser.
- **Build**: `npm run build` outputs to `dist/`. A CJS deprecation warning from Vite is expected and harmless.
- **No lockfile**: The repo has no `package-lock.json`; `npm install` will generate one locally.
