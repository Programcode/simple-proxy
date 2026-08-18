# HERMES.md

Project-specific operating notes for Hermes/Hermione and coding subagents. This file is intentionally concise and safe: inspect the repo before acting, prefer reversible changes, and verify with real commands.

## Repository
- Path: `/home/codex/Projects/simple-proxy`
- Detected stack: Node/JavaScript/TypeScript

## Working rules
- Read existing README, config, package manifests, and tests before editing.
- Keep diffs narrow and avoid unrelated formatting churn.
- Do not expose secrets or copy values from `.env`, credentials, caches, or logs into chat.
- Ask before destructive actions: data deletion, irreversible migrations, production deploys, payment/billing changes, or secret rotation.
- Attach important reports, generated files, and screenshots by default when they are the deliverable.

## Verification hints
- `lint`: `npm run lint`
- `build`: `npm run build`
- `dev`: `npm run dev`
- `start`: `npm run start`

## Notes
- Prefer `pnpm` in this repo if the lockfile matches; otherwise inspect existing scripts before installing dependencies.
- Docker/deploy files exist: treat restarts, migrations, and production changes as ops-sensitive.
- Git remote: `https://github.com/Programcode/simple-proxy.git`
