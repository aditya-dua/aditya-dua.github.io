# aditya-dua.github.io

Personal site for **adityadua.com** — Aditya Dua.

## Pages

| File | URL |
|---|---|
| `index.html` | `/` — hero, build-in-progress panel, the three pillars |
| `experience.html` | `/experience.html` — GitHub-style README prose + `db.career.find()` documents |
| `works.html` | `/works.html` — courses, bootcamps and open source |

Content is sourced from the LinkedIn profile and the `AdityaDuaIntroCBA` one-pager.
Static HTML + one stylesheet, no build step. `.nojekyll` is set, so files are served as-is.

## Routing for other repos

The custom domain is set on **this** user-site repo, so every other `aditya-dua/*` repo
with GitHub Pages enabled is automatically published at:

```
https://adityadua.com/<repo-name>/
```

Do **not** add a `CNAME` file or custom domain to those repos — it overrides this and
breaks the path-based routing. The only per-repo setting needed is the asset base path,
e.g. `baseurl: /<repo>` (Jekyll), `base: '/<repo>/'` (Vite), `basePath` (Next.js).
