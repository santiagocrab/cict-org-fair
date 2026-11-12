# CICT Org Fair

**Live web app:** https://santiagocrab.github.io/cict-org-fair/

Flutter app for the CICT Org Fair (James Remegio, BSIT 3-A). Events load from Contentful at runtime.

## Local run

1. Copy `cms.example.json` to `cms.json` and fill in your Contentful space id and **Content Delivery** (read-only) token.
2. Run:

```bash
flutter pub get
flutter run -d chrome --dart-define-from-file=cms.json
```

## Release notes

- App version: `1.1.0+2` (About shows `Version 1.1.0 (build 2)`).
- Web and Android branding: **CICT Org Fair**.
- CI analyzes, tests, and builds on pull requests and pushes.
- Deploy publishes to GitHub Pages after tests pass on `main`.
