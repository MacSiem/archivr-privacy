# Archivr Privacy Policy Repo

Repo-local `CLAUDE.md`.

This repo is the public privacy-policy surface for Archivr, not the main application repo.

Canonical project memory:
- `~/Claude/maciej/development/projects/archivr/_PROJECT.md`
- `~/Claude/maciej/development/projects/archivr/_PROJECT_CHARTER.md`
- `~/Claude/maciej/development/projects/archivr/_LESSONS_LEARNED.md`

## Public URL
https://macsiem.github.io/archivr-privacy/

The root `index.html` auto-redirects to `/pl/` for Polish browsers and `/en/` for everyone else. Both language pages exist and are linked via `hreflang` tags.

## Working rules

- Keep changes narrow and user-facing
- Preserve public URL stability — these URLs are referenced from the app, ASC App Information, Play Console privacy URL field, and possibly stored in app analytics declarations
- Coordinate app-facing text changes with the main Archivr project (`~/Projects/Archivr/`) and store metadata when relevant
- Mirror meaningful user-facing updates in Notion (`Archivr — App Hub`)
- Update the "Last updated" date at the top of `pl/` and `en/` whenever policy text changes substantively
- When a new SDK is added to the app (new ads/analytics/storage integration), update both language pages BEFORE shipping the change

## GitHub

- This repo IS public by design (it hosts the privacy policy via GitHub Pages)
- Do not store secrets, tokens, or internal-only notes here
- Branch protection: `main` is the source for GitHub Pages; preview/draft policy changes in feature branches and merge after review

## Color scheme

- Primary: `#1e40af` (blue-800)
- Hover/dark: `#1e3a8a` (blue-900)
- Strong text accent: `#1e3a8a`

(Mote uses purple `#7c3aed`; Compresser uses its own scheme. Archivr uses cooler blue palette per `_PROJECT_CHARTER.md`.)
