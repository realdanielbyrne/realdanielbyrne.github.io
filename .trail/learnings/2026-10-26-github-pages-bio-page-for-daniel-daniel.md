---
title: GitHub Pages bio page for Daniel Byrne
author: Daniel
date: 2026-10-26
branch: main
touches:
  - index.html
---

## Decided
- Bio lives at realdanielbyrne/realdanielbyrne.github.io (public, single static index.html, Pages from main); local clone at ~/GitHub/realdanielbyrne.github.io.
- Content source: latest CTO resume HTML under ~/Downloads/Resumes/Job_Search/ (Aventis_CAITO) plus READMEs of personal repos.
- User chose "capabilities, no financials": no revenue/profit, no vendor/system names (Vista, UKG, HCSS, OEMs), no trucking, no exact savings figure. Contact = GitHub, LinkedIn, iCloud email; no phone.
- SunBurn-Consulting repos (all private client demos) left off.

## Tried and ruled out
- Local git email in rpm repos is the iCloud address; commit counts by author are per-repo and not used on the page.

## Watch out
- All RpmxConstruction repos are private; anything added to the page must stay high level.
- `gh api -X POST .../pages` printed "unexpected end of JSON input" but Pages was enabled anyway; verify with GET .../pages.
- Page was not visually checked in a browser, only HTTP 200.
