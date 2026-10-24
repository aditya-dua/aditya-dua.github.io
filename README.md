# aditya-dua.github.io

Root site for **adityadua.com**.

Because the custom domain is set on this user-site repo, every other
`aditya-dua/*` repo with GitHub Pages enabled is automatically published at:

```
https://adityadua.com/<repo-name>/
```

No `CNAME` file and no custom-domain setting is needed in those repos —
adding one there would override this and break the path-based routing.

The only per-repo setting required is the asset base path, e.g.
`baseurl: /<repo>` (Jekyll), `base: '/<repo>/'` (Vite), `basePath` (Next.js).
