# Codex instructions

## Working method

- Use one agent by default. Delegate only independent, bounded work that merits a separate context; never delegate trivial changes.
- Search filenames and symbols first. Read relevant files only; reuse findings and existing code patterns.
- Make the smallest correct change. Run focused deterministic checks before broader tests. Report only checks actually run and any remaining risk.
- Keep documentation and long-task handoffs concise. Ask before destructive actions, deployment, publication or external financial actions unless the request clearly authorises the exact action.

## Project boundaries

- Read `README.md` for the current architecture and run command. The deployed entry point is `index.html`; retained `app.js`, `js/` and `styles/` are not loaded by it.
- `main` at the repository root publishes to GitHub Pages. Treat changes to `main` as a public deployment.
- Preserve browser-local game data, backup/import behaviour, offline support and the original project credit and licence notes.
- Keep scoring changes tied to the documented house rules; do not present one convention as universal.
