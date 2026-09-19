# Public URLs

GitHub Pages site for this repository (`main` branch, site root `/`):

- https://yohann305.github.io/app-legal/
- https://yohann305.github.io/app-legal/wordsearch-winners/privacy.html
- https://yohann305.github.io/app-legal/wordsearch-winners/terms.html

## Enabling Pages

These URLs respond with **200** only after GitHub Pages is turned on.

The Pages create API was attempted:

```bash
gh api -X POST repos/yohann305/app-legal/pages -f build_type=legacy -f source[branch]=main -f source[path]=/
```

It returned **403 Resource not accessible by integration**. A repo admin needs to run that command, or enable Pages in GitHub: **Settings → Pages → Deploy from a branch → `main` / (root)**.
