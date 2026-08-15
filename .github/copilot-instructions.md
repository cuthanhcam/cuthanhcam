# Workspace instructions

This multi-root workspace contains five independent Git repositories. Treat each repository as an isolated project: run commands from its root, respect its lockfiles and tool versions, and never move code or dependencies between projects unless explicitly requested.

- `Aegis`: .NET authorization platform with a React/TypeScript frontend.
- `lens-of-charlie`: Astro content site with React islands.
- `forge`: React/TypeScript/Vite developer toolbox under `orcace/forge`.
- `learn-dotnet`: progressive C#/.NET learning repository.
- `learn-rust`: Rust learning repository and Cargo workspace.
- `docs`, `temp`, and `other`: supporting notes and scratch material; do not treat them as deployable products.

Prefer the smallest change that follows the conventions already present in the target repository. Do not edit generated output (`bin`, `obj`, `dist`, `.astro`, `target`, or `node_modules`). Before finishing, run the narrowest relevant formatter, lint, test, type-check, or build command documented by that project.

Read the target repository's `AGENTS.md` before making changes. Apply the language-specific instruction files in `.github/instructions` when their file patterns match.
