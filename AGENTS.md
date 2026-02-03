# Repository Guidelines

## Project Structure & Module Organization
- `index.html` contains the full TailwindCSS v4 cheat sheet markup, styles, and layout.
- `package.json` defines the development script (Vite).
- `LICENSE` holds the project license.
- `node_modules/` is generated and should not be edited directly.

## Build, Test, and Development Commands
- `npm install` installs dependencies (Vite is used via `npx`).
- `npm run dev` starts the local dev server via Vite with `--host` for LAN access.

## Coding Style & Naming Conventions
- Use 4-space indentation in HTML and JSON to match existing files.
- Keep HTML readable with one attribute per line for long tags, as in `index.html`.
- Tailwind utility classes are applied inline; prefer semantic grouping (layout, spacing, color).

## Testing Guidelines
- No automated tests are configured. Validate changes by running `npm run dev` and checking the UI in a browser.

## Commit & Pull Request Guidelines
- Commit messages are short, imperative, and capitalized (e.g., `Update index.html`, `Add GPT component prompt and links`).
- PRs should include a concise summary and, for UI changes, before/after screenshots.
- Link relevant issues if applicable.

## Security & Configuration Tips
- External scripts are loaded via CDN (`cdn.tailwindcss.com`, `unpkg.com`). If adding new CDN assets, verify source trustworthiness and pin versions when possible.
