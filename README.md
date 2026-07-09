# wbgeo.github.io

This repository hosts the [WBGeo](https://github.com/WBGeo) organization's GitHub Pages site.

**📖 The documentation itself lives at: https://wbgeo.github.io/**

The site content is built with [MkDocs](https://www.mkdocs.org/) from the `docs/` folder of the
[`codebase`](https://github.com/WBGeo/codebase) repository (WBGeo's backend), and deployed here
automatically via CI to the `gh-pages` branch. **Don't edit files on `gh-pages` directly** — they're
a build output and get overwritten on every deploy. To change the documentation, edit
[`codebase`'s `docs/`](https://github.com/WBGeo/codebase/tree/main/docs) instead.

## Branches

| Branch | Purpose |
|---|---|
| `main` | This README — not deployed by GitHub Pages. |
| `gh-pages` | Auto-deployed MkDocs build — the live site. |
| `redirect` | A minimal redirect page. |
