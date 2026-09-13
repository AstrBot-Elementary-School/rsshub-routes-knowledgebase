# iRacing - News

## Coverage
`index-only`

## Route
- Namespace: `iracing`
- Namespace Name: `iRacing`
- Route Path: `/iracing/news`
- Route Name: `News`
- Example: `/iracing/news`
- URL: `iracing.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `canonnizq`
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
  - `www.iracing.com/category/news/sim-racing-news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/iracing/news",
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
    "canonnizq"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.iracing.com/category/news/sim-racing-news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
