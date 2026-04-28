# Repository Instruction for OpenCode

This repository contains a static HTML website for the personal portfolio of Sharath Aradhyamath. It has no build, test, or tooling steps beyond standard git operations.

**To edit**
- Open `index.html` and change the HTML/CSS/JS directly.

**To preview locally**
- Run a simple HTTP server.
  ```bash
  python -m http.server 8000
  ```
  then visit `http://localhost:8000`.

**To publish changes**
- Commit any edited files.
- Push to `master`. GitHub Pages is configured to build from the `master` branch.
  ```bash
  git add index.html
  git commit -m "Update site"
  git push origin master
  ```

There are no tests, linter, or formatting tools. The repository is intentionally minimal. If you add new assets, commit and push them in the same way.

**Common pitfalls**
- Forgetting to push the `master` branch after changes. As of now the only branch served by GitHub Pages is `master`.
- Editing the file outside the workspace or modifying a non‑existent branch.