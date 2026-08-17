# GoCN - 每日新闻

## Coverage
`index-only`

## Route
- Namespace: `gocn`
- Namespace Name: `GoCN`
- Route Path: `/gocn/topics`
- Route Name: `每日新闻`
- Example: `/gocn/topics`
- URL: `gocn.vip/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `AtlanCI, CcccFz`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `gocn.vip/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gocn/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "topics.ts",
  "maintainers": [
    "AtlanCI",
    "CcccFz"
  ],
  "name": "每日新闻",
  "parameters": {},
  "path": "/topics",
  "radar": [
    {
      "source": [
        "gocn.vip/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "gocn.vip/"
}
```
