# Lo-Fi City Ambience — Production Agents

Production pipeline for the Lo-Fi City Ambience YouTube channel.
Built by Mel Thomson. GitHub: MelThomo

## Agents

| Agent | Status | Purpose |
|-------|--------|---------|
| Agent 1 — City Research | ✅ Live | Generates city intelligence JSON via Claude API |
| Agent 2 — Scene Generator | 🔨 Building | Creates 10-15 cinematic scene concepts |
| Agent 3 — Image Prompt | 🔨 Building | Builds Leonardo.ai ready prompts |

## Pipeline

City Name → JSON Research → Scene Concepts → Image Prompt → Leonardo.ai → Animation → 10hr Video

## Stack
- HTML / CSS / JS (no framework)
- Claude API (claude-sonnet-4-20250514)
- Hosted on Netlify via GitHub

## Setup
Clone repo, connect to Netlify. No build step required — pure static HTML.
