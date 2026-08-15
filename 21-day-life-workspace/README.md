# 21-Day Life Workspace PWA

A bilingual (Chinese / English) progressive web app for sleep, fitness, daily tasks, notes and local content insights.

## Features

- Monthly focus + monthly review history
- Date-based daily to-do list
- Notes timeline with category, mood, search and filters
- Independent 21-day sleep and Keep fitness challenges
- Local-only keyword / mood / topic idea analysis
- IndexedDB persistence with LocalStorage fallback
- JSON export/import backup
- `?lang=en` English mode
- Installable PWA + offline App Shell
- No framework, no external CDN

## Data

Primary: IndexedDB (`LifeWorkspaceDB`). Fallback: LocalStorage (`lifeWorkspaceV1`).

A `CloudSyncAdapter` interface is reserved in `core.js` for future Supabase/Firebase/API sync without rewriting the UI layer.

## GitHub Pages

This build uses only relative paths. It works from a repository root or a nested GitHub Pages path.

## Install

- Android Chrome / Desktop Chrome: use the in-app Install button when available.
- iPhone Safari: Share → Add to Home Screen.
