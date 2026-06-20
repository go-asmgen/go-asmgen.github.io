<p align="center"><img src="https://raw.githubusercontent.com/go-asmgen/brand/main/social/go-asmgen.png" alt="go-asmgen/go-asmgen.github.io" width="720"></p>

# go-asmgen.github.io

The organization's institutional landing page, served at
<https://go-asmgen.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`, target cards driven by
`[[params.targets]]` in `hugo.toml`).

Documentation lives in a separate repository,
[go-asmgen/docs](https://github.com/go-asmgen/docs) — MkDocs Material versioned
with [mike](https://github.com/jimporter/mike), served at
<https://go-asmgen.github.io/docs/>. This page links there.

`.github/workflows/deploy.yml` builds the landing with Hugo and deploys it to
GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
