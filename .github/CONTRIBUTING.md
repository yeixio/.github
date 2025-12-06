# Contributing to Yeix.io

Thanks for your interest in contributing! This document describes how we work across Yeix.io projects.

---

## Repos and projects

We maintain multiple repos for different products, including:

- `pacificnorthnorth.com` – tourism marketplace web app
- `fundr.science` – science funding platform
- `dungeonparty.ai` – AI DM + multiplayer RPG
- Various shared libs, infra, and internal tools

Each repo should have its own `README.md` and may add extra contributing details. If anything is unclear, open an issue.

---

## Getting started

1. **Pick an issue**  
   - Look for labels like `good first issue` or `help wanted`.
   - Ask in the issue if you want to take it.

2. **Fork and branch**  
   - Fork the repo (if external contributor).  
   - Create a branch from `main` (or as specified in the repo) using a clear name:
     - `feature/pnn-trip-packages`
     - `bugfix/dungeonparty-login-loop`
     - `chore/update-deps`

3. **Setup locally**  
   - Follow the project’s `README.md`.
   - For Go projects: `go test ./...`  
   - For frontend projects (React/Next/etc.): `npm test` and `npm run lint` (or repo-specific commands).

---

## Commit and PR style

- Make commits small and focused.
- Write clear messages, e.g.:
  - `fix: handle null user in session middleware`
  - `feat: add PNN vendor dashboard cards`
  - `chore: bump Next.js to 15.x`

**Pull requests:**

- Fill out the PR template.  
- Reference issues with `Fixes #123` where applicable.  
- Prefer multiple small PRs over one huge one.

---

## Code quality

- Aim for **readability over cleverness**.
- Add tests for:
  - New functionality.
  - Bug fixes (regressions).
- Try to keep breaking changes explicitly called out in the PR description.

---

## Reporting security issues

Please **do not** open a public issue for security vulnerabilities.  
Instead, follow the process in [`SECURITY.md`](./SECURITY.md).

---

## License and CLA

By contributing, you agree that your contributions may be used by Yeix.io under the project’s license. If we later need a Contributor License Agreement, we’ll document it here.