# Epic Games Store - Free games

## Coverage
`index-only`

## Route
- Namespace: `epicgames`
- Namespace Name: `Epic Games Store`
- Route Path: `/epicgames/freegames/:locale?/:country?`
- Route Name: `Free games`
- Example: `/epicgames/freegames/en-US/US`
- URL: `store.epicgames.com`
- Language: `_None_`
- Categories: `game, popular`
- Maintainers: `DIYgod, NeverBehave, Zyx-A, junfengP, nczitzk, KotaHv`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locale`: {"default": "en-US", "description": "Locale"}
- `country`: {"default": "US", "description": "Country"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `store.epicgames.com/:locale/free-games`
- `target`: `/freegames/:locale`

## Raw JSON
```json
{
  "categories": [
    "game",
    "popular"
  ],
  "example": "/epicgames/freegames/en-US/US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 44879,
  "location": "index.tsx",
  "maintainers": [
    "DIYgod",
    "NeverBehave",
    "Zyx-A",
    "junfengP",
    "nczitzk",
    "KotaHv"
  ],
  "name": "Free games",
  "parameters": {
    "country": {
      "default": "US",
      "description": "Country"
    },
    "locale": {
      "default": "en-US",
      "description": "Locale"
    }
  },
  "path": "/freegames/:locale?/:country?",
  "radar": [
    {
      "source": [
        "store.epicgames.com/:locale/free-games"
      ],
      "target": "/freegames/:locale"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Epic Games Store - Free Games - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41503779521380352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.epicgames.com/en-US/free-games?lang=en-US",
      "title": "Epic Games Store - Free Games",
      "type": "feed",
      "url": "rsshub://epicgames/freegames/en-US/US"
    },
    {
      "description": "Epic Games Store - Free Games - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "43374760408291328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://store.epicgames.com/zh-CN/free-games?lang=zh-CN",
      "title": "Epic Games Store - Free Games",
      "type": "feed",
      "url": "rsshub://epicgames/freegames/zh-CN/CN"
    }
  ],
  "view": 5
}
```
