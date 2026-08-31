# 链捕手 ChainCatcher - 快讯

## Coverage
`index-only`

## Route
- Namespace: `chaincatcher`
- Namespace Name: `链捕手 ChainCatcher`
- Route Path: `/chaincatcher/news`
- Route Name: `快讯`
- Example: `/chaincatcher/news`
- URL: `chaincatcher.com/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
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
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `chaincatcher.com/news`
  - `chaincatcher.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/chaincatcher/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "chaincatcher.com/news",
        "chaincatcher.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "chaincatcher.com/news"
}
```
