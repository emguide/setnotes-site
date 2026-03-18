# SetNotes Marketing Site

This is the standalone marketing/landing site for **SetNotes** (iOS workout logging app). It lives in its own git repository, separate from the main iOS app repo.

## Project Structure

```
setnotes-site/
├── index.html           # Main landing page
├── privacy-policy.html  # Privacy policy page
├── assets/              # Images, icons, SVGs
│   ├── appicon.png
│   ├── apple-touch-icon.png
│   ├── favicon-32.png
│   ├── muscles-anterior.svg
│   ├── muscles-posterior.svg
│   └── onboarding-*.svg
└── screenshots/         # App screenshots used on the site
```

## Tech Stack

- **Pure HTML/CSS/JS** — no build tools, no framework, no npm
- Hosted as static files (GitHub Pages or similar)
- Google Fonts: Barlow Condensed, Barlow, Fira Code

## Design System

- **Brand color**: `--orange: #FF6B00`
- **Background**: near-black `#0A0A0A`
- **Text**: warm off-white `#F0EDE8`
- Dark-mode-first aesthetic matching the iOS app

## Related Repos

- **iOS App**: `../RepJournal Main` — the main Xcode project (SwiftUI, SwiftData)

## Working Notes

- No build step needed — edit HTML/CSS directly and open in browser
- Screenshots in `screenshots/` are actual device captures from the iOS app
- Keep the site self-contained; avoid external JS dependencies
