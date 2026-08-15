---
applyTo: "**/*.{ts,tsx,js,jsx,mjs,cjs,astro,css}"
---

# React and TypeScript instructions

- Use the package manager and exact version declared in `package.json`; do not mix npm, yarn, and pnpm lockfiles.
- Preserve strict TypeScript typing. Avoid `any`, non-null assertions, and type casts unless the boundary is validated and the reason is clear.
- Keep components focused, accessible, and consistent with the project's existing design system and state-management approach.
- Prefer existing utilities and dependencies before adding a package. Never hand-edit `dist`, `.astro`, or `node_modules`.
- Run the project's documented type-check, lint, test, and build commands appropriate to the change.
