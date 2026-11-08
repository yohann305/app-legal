# Public URLs

GitHub Pages site for this repository (`main` branch, site root `/`):

## Portfolio

- https://yohann305.github.io/app-legal/
- https://yohann305.github.io/app-legal/llms.txt
- https://yohann305.github.io/app-legal/llms-full.txt
- https://yohann305.github.io/app-legal/sitemap.xml
- https://yohann305.github.io/app-legal/robots.txt

`robots.txt` in this project is published at `/app-legal/robots.txt`. Crawlers of `yohann305.github.io` read `https://yohann305.github.io/robots.txt`, which is outside this repository.

## Green Screen Live Video Record

- https://yohann305.github.io/app-legal/greenscreen-ios/
- https://yohann305.github.io/app-legal/greenscreen-ios/privacy.html
- https://yohann305.github.io/app-legal/greenscreen-ios/terms.html
- https://yohann305.github.io/app-legal/greenscreen-ios/support.html

## Video Teleprompter Pro

- https://yohann305.github.io/app-legal/video-teleprompter-pro/
- https://yohann305.github.io/app-legal/video-teleprompter-pro/privacy.html
- https://yohann305.github.io/app-legal/video-teleprompter-pro/terms.html
- https://yohann305.github.io/app-legal/video-teleprompter-pro/support.html
- https://yohann305.github.io/app-legal/video-teleprompter-pro/privacy-android.html

## Colorblind Eye Exam Test

- https://yohann305.github.io/app-legal/colorblind/
- https://yohann305.github.io/app-legal/colorblind/privacy.html
- https://yohann305.github.io/app-legal/colorblind/terms.html
- https://yohann305.github.io/app-legal/colorblind/support.html

## Bachata Dance App

- https://yohann305.github.io/app-legal/bachata-ios/
- https://yohann305.github.io/app-legal/bachata-ios/privacy.html
- https://yohann305.github.io/app-legal/bachata-ios/terms.html
- https://yohann305.github.io/app-legal/bachata-ios/support.html
- https://yohann305.github.io/app-legal/bachata-ios/instructor.html

## WordSearch Winners

- https://yohann305.github.io/app-legal/wordsearch-winners/
- https://yohann305.github.io/app-legal/wordsearch-winners/privacy.html
- https://yohann305.github.io/app-legal/wordsearch-winners/terms.html
- https://yohann305.github.io/app-legal/wordsearch-winners/support.html

## Word Guess Daily Brain Trainer

- https://yohann305.github.io/app-legal/wordguess/
- https://yohann305.github.io/app-legal/wordguess/privacy.html
- https://yohann305.github.io/app-legal/wordguess/terms.html
- https://yohann305.github.io/app-legal/wordguess/support.html

## Enabling Pages

These URLs respond with **200** only after GitHub Pages is turned on.

The Pages create API was attempted:

```bash
gh api -X POST repos/yohann305/app-legal/pages -f build_type=legacy -f source[branch]=main -f source[path]=/
```

It returned **403 Resource not accessible by integration**. A repo admin needs to run that command, or enable Pages in GitHub: **Settings → Pages → Deploy from a branch → `main` / (root)**.
