# Repository Guidelines

## Project Structure & Module Organization

This workspace currently contains no application source, tests, assets, or build configuration. The directory name is `asteroids-wasm`, but the language and WebAssembly toolchain have not been established. Inspect the repository again before choosing tools or adding modules.

As implementation begins, keep source code, tests, and static assets in clearly named directories such as `src/`, `tests/`, and `assets/`. Document the actual layout in this guide. Treat `.agents/`, `.codex/`, and `.aws/` as environment configuration; do not place application code there.

## Build, Test, and Development Commands

No build, test, or local development commands are currently configured. Do not assume that `npm test`, `cargo test`, or `make build` applies.

When introducing a toolchain, provide reproducible commands for installing dependencies, building WebAssembly, running locally, and executing tests. Record those commands in a README and update this guide. Keep generated output separate from source files.

## Coding Style & Naming Conventions

No formatter, linter, indentation standard, or naming convention is established yet. Follow the chosen language’s standard conventions and configure its formatter when adding the initial implementation. Use descriptive names and keep formatting consistent within each file. Avoid unrelated formatting changes in functional patches.

## Testing Guidelines

No testing framework or coverage threshold is configured. Add tests alongside new behavior using the selected framework’s naming conventions. Include deterministic checks for game logic and document any browser or WebAssembly integration checks. Explain how to run tests before requiring them in review.

## Commit & Pull Request Guidelines

No usable Git history is available to infer commit conventions. Use short, imperative commit subjects, such as `Add ship movement controls`.

Pull requests should describe the change, its purpose, and validation performed. Link related issues when applicable. Include screenshots or recordings for visible gameplay changes, and identify any setup requirements or untested behavior.
