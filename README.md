# app-legal

Public legal pages (privacy, terms) for Yohann Taieb apps, hosted on GitHub Pages.

## WordSearch Winners

Open-source word-search app (WordSearch International). Operator: Yohann Taieb.

- [Privacy Policy](wordsearch-winners/privacy.html)
- [Terms of Use](wordsearch-winners/terms.html) (draft)

## Live URLs

See [PUBLIC_URLS.md](PUBLIC_URLS.md):

- https://yohann305.github.io/app-legal/
- https://yohann305.github.io/app-legal/wordsearch-winners/privacy.html
- https://yohann305.github.io/app-legal/wordsearch-winners/terms.html

## GitHub Pages

This repo is meant to be served from **Deploy from a branch**: `main`, folder `/` (site root).

Enabling Pages via the API failed with **403 Resource not accessible by integration** (the automation token is not a repo admin). A repo admin can enable it with:

```bash
gh api -X POST repos/yohann305/app-legal/pages -f build_type=legacy -f source[branch]=main -f source[path]=/
```

Or in GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**.
