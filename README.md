# SecureGen — Password Generator

A client-side password generator. No backend, no network requests — everything runs in the browser.

## What it does

- Generates cryptographically random passwords instantly
- Adjustable length from 4 to 64 characters via a live-fill slider
- Four character set toggles: Uppercase, Lowercase, Numbers, Symbols
- Each toggle shows example characters so it's obvious what it includes
- Active toggles highlight so you always know what's selected
- Prevents deselecting all options (at least one must stay active)
- Strength meter updates live — Weak / Medium / Strong / Very Strong
- Copy button uses Clipboard API with a toast confirmation
- Regenerates automatically when any setting changes

## Stack

Pure HTML + CSS + JavaScript. Single file, no dependencies, no build step.

## Deployment

Just push `index.html` to GitHub and connect to Vercel — deploys as a static site automatically.
