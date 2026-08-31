# MusikGuru - News

## Coverage
`index-only`

## Route
- Namespace: `musikguru`
- Namespace Name: `MusikGuru`
- Route Path: `/musikguru/news`
- Route Name: `News`
- Example: `/musikguru/news`
- URL: `musikguru.de`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `musikguru.de/news`
- `target`: `news`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/musikguru/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "musikguru.de/news"
      ],
      "target": "news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "musikguru.de",
  "view": 0
}
```
