# Rumble - Channel

## Coverage
`index-only`

## Route
- Namespace: `rumble`
- Namespace Name: `Rumble`
- Route Path: `/rumble/c/:channel/:embed?`
- Route Name: `Channel`
- Example: `/rumble/c/MikhailaPeterson`
- URL: `rumble.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `luckycold`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
Fetches full Rumble video descriptions without embedding the player by default.

## Parameters
- `channel`: Channel slug from `https://rumble.com/c/<channel>`
- `embed`: Default to not embed the video, set to `embed` to enable embedding


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `rumble.com/c/:channel`
  - `rumble.com/c/:channel/videos`
- `target`: `/c/:channel`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches full Rumble video descriptions without embedding the player by default.",
  "example": "/rumble/c/MikhailaPeterson",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel.ts",
  "maintainers": [
    "luckycold"
  ],
  "name": "Channel",
  "parameters": {
    "channel": "Channel slug from `https://rumble.com/c/<channel>`",
    "embed": "Default to not embed the video, set to `embed` to enable embedding"
  },
  "path": "/c/:channel/:embed?",
  "radar": [
    {
      "source": [
        "rumble.com/c/:channel",
        "rumble.com/c/:channel/videos"
      ],
      "target": "/c/:channel"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 3
}
```
