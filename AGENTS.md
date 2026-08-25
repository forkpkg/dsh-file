# AGENTS.md

## Version constraints

All documentation is in English. Replace the old Chinese descriptions with English equivalents.

## Project structure

- `src/index.ts` — host half (Node process, file system RPC). Built by tsc to `dist/index.js`.
- `src/client/` — client half (React, sidebar file tree + editor). Built by esbuild to `dist/client.js`.
- `docs/` — Readme image resources, e.g., logo.
- `test/` — Node tests.

## Common commands

```sh
npm install          # Install dependencies
node build.mjs       # Build host + client
npm test             # Run tests (node --test "test/*.test.ts")
```

Documentation is intentionally kept in English to facilitate international usage.
