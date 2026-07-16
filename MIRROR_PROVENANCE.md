# Scope-reduced mirror — for RubberDuck indexing only

This repository is a **scope-reduced snapshot** of the public repo
`openclaw/openclaw`, created solely to fit within RubberDuck's ~20,000-file
indexing cap (the upstream repo exceeds it).

- Upstream: https://github.com/openclaw/openclaw
- Pinned source commit: `58f43c703eea2fc691b681fecebbf4567bf9e332` (branch `main`)
- Files removed to fit the cap: 8,321 non-core TypeScript files
  - `*.test.ts` / `*.spec.ts` (7,842)
  - `scripts/` build/dev tooling (450)
  - `*.d.ts` generated declarations (24)
  - `fixtures/` and `__mocks__/` (11)
- Result: 17,568 files total, 12,344 TypeScript files.

No source files were modified; only whole files were removed. Git history was
stripped and re-initialized. This mirror is not a fork for development.
