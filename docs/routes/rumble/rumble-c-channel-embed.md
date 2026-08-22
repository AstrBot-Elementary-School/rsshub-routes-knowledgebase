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
  "topFeeds": [],
  "view": 3
}
```
