# Repository Guidelines

## Project Structure & Module Organization
- `quartz/`: TypeScript source for the static-site engine (CLI bootstrap, components, plugins, styles, processors).
- `content/`, `Templates/`, `Worldbuilding/`, `Campaign (DM Notes)/`, `DM Improvement/`: primary markdown inputs and reference material for the site; keep new notes here.
- `public/`: static assets copied as-is; `quartz/static/` holds shared assets bundled during builds.
- `quartz.config.ts` and `quartz.layout.ts`: main configuration and layout entry points; adjust plugins, routes, and theme here.
- Tests live near sources (e.g., `quartz/components/scripts/search.test.ts`, `quartz/util/*.test.ts`).

## Build, Test, and Development Commands
- `npm install` (Node >=22, npm >=10.9): install dependencies.
- `npm run quartz -- build --serve`: build the site from `content/` and serve locally for preview.
- `npm run docs`: serve the upstream Quartz docs from `docs/` for reference.
- `npm run check`: TypeScript type-check + Prettier formatting check.
- `npm run format`: auto-format the repo to project standards.
- `npm run test`: run tsx-based unit tests.

## Coding Style & Naming Conventions
- TypeScript + ESM; follow Prettier defaults (2-space indentation, trailing commas where valid).
- Use camelCase for functions/variables, PascalCase for components, kebab-case or descriptive filenames consistent with nearby code.
- Prefer named exports from modules in `quartz/` and keep configuration typed when editing `quartz.config.ts` or `quartz.layout.ts`.

## Testing Guidelines
- Place new tests alongside implementations using the `*.test.ts` pattern.
- Keep tests deterministic: avoid network calls; use fixture markdown in `content/` or inline strings.
- Cover new utilities, processors, or plugin behavior with `npm run test`; run `npm run check` before pushing.

## Commit & Pull Request Guidelines
- Recent history uses `vault backup: <timestamp>` for automated snapshots; for manual work, use a short, imperative subject, optionally scoped (e.g., `build: speed up watcher`).
- PRs should summarize the change, link any issue/task, list commands run (`npm run test`, `npm run check`), and include screenshots or before/after notes when UI or generated output changes.

## Configuration Tips
- Site behavior lives in `quartz.config.ts`; layout composition is in `quartz.layout.ts`. Keep plugin additions minimal and documented.
- Add or edit content in `content/` (or the domain folders noted above) with consistent frontmatter; run a local build to confirm rendering before submitting.
