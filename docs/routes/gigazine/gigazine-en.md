# GIGAZINE - English News

## Coverage
`index-only`

## Route
- Namespace: `gigazine`
- Namespace Name: `GIGAZINE`
- Route Path: `/gigazine/en`
- Route Name: `English News`
- Example: `/gigazine/en`
- URL: `gigazine.net/gsc_news/en/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `chansantheman`
- Source Location: `en.ts`
- Source Module: `_None_`

## Description
Full-text English articles from GIGAZINE. Detail pages are cached, and the common `limit` parameter controls how many recent entries are fetched.

## Parameters
_None_


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
  - `gigazine.net/gsc_news/en/`
  - `gigazine.net/gsc_news/en`
- `target`: `/en`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Full-text English articles from GIGAZINE. Detail pages are cached, and the common `limit` parameter controls how many recent entries are fetched.",
  "example": "/gigazine/en",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "en.ts",
  "maintainers": [
    "chansantheman"
  ],
  "name": "English News",
  "path": "/en",
  "radar": [
    {
      "source": [
        "gigazine.net/gsc_news/en/",
        "gigazine.net/gsc_news/en"
      ],
      "target": "/en"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "gigazine.net/gsc_news/en/",
  "view": 0
}
```
