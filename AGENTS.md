# AGENTS.md

Guidance for AI coding agents working in this repository.

## Project overview

- This is a lightweight front-end web game.
- Main app file: `index.html` (contains structure, styles, and game logic).
- Documentation and meta files: `README.md`, `LICENSE`, and this file.

## Working conventions

- Keep the project dependency-free unless explicitly requested.
- Prefer small, targeted changes and keep the app runnable by opening `index.html`.
- For JavaScript updates, preserve current gameplay behavior unless the task requests gameplay changes.
- For UI updates, favor mobile-friendly behavior and avoid breaking touch interactions.

## Validation checklist

Before finishing work:

1. Confirm files changed are minimal and relevant to the request.
2. Run a quick sanity check by opening/serving `index.html` when behavior changes.
3. Update `README.md` whenever user-facing controls or setup steps change.
4. Keep license and authorship information intact unless explicitly instructed otherwise.

## PR guidance

- Use concise, descriptive commit messages.
- Summarize what changed and why.
- Include testing/check steps run locally.
