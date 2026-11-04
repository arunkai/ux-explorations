# ux-explorations

Arun Kai's UX explorations: small standalone sketches, each in its own folder (SDF button
hover effect, a cloudy shader, p5.js fireworks).

- Shared defaults live in `~/Dev/studio` ([arunkai/studio](https://github.com/arunkai/studio)): start with `agent/defaults.md`. This file overrides them where they differ.
- Read [`LEARNINGS.md`](LEARNINGS.md) before changing build or deploy setup.

## Stack

- Plain HTML/JS per folder; `fireworks/` uses p5.js from a CDN.

## Run, build, deploy

Open a folder's `index.html` in a browser. No build or deploy config.

## Rules

- This repo is **public**. Nothing private (accounts, IDs, unreleased work) goes here.
- Two folders have spaces in their names (`SDF Button (Hover Effect)/`, `cloudy thing/`). New folders use kebab-case; don't rename the old ones without Arun (it breaks links).
- No spaces in paths or names (kebab-case). Never commit `.env`, `.dev.vars` or keys; secrets go in `wrangler secret` / Workers Builds variables.
