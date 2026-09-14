# VQActFlow Project Website (redirect)

This repository previously hosted the VQActFlow project page. That page has
moved, and this repository now serves only a redirect so existing links
(including the URL cited in the preprint) continue to resolve.

Canonical project page: <https://vqactflow.github.io/vqactflow/>

## Structure

```
index.html   redirect page (meta refresh + canonical link + JS fallback)
.nojekyll    tells GitHub Pages to skip Jekyll processing
```

GitHub Pages serves this repository from the `main` branch, `/ (root)`.
Static HTML only — no build step and no dependencies.
