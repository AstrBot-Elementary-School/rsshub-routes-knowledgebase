# Anhui Museum - Special Exhibition

## Coverage
`index-only`

## Route
- Namespace: `ahm`
- Namespace Name: `Anhui Museum`
- Route Path: `/ahm/exhibition/xztj`
- Route Name: `Special Exhibition`
- Example: `/ahm/exhibition/xztj`
- URL: `www.ahm.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `xztj.tsx`
- Source Module: `_None_`

## Description
_None_

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
  - `www.ahm.cn/Exhibition/TListNow/xztj`
- `target`: `/exhibition/xztj`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/ahm/exhibition/xztj",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xztj.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Special Exhibition",
  "path": "/exhibition/xztj",
  "radar": [
    {
      "source": [
        "www.ahm.cn/Exhibition/TListNow/xztj"
      ],
      "target": "/exhibition/xztj"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
