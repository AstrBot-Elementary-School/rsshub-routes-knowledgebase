# Hunan Museum - HNM News

## Coverage
`index-only`

## Route
- Namespace: `hnmuseum`
- Namespace Name: `Hunan Museum`
- Route Path: `/hnmuseum/hnmnews`
- Route Name: `HNM News`
- Example: `/hnmuseum/hnmnews`
- URL: `www.hnmuseum.com/zh-hans`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `hnmnews.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.hnmuseum.com/zh-hans/xiangbo_dongtai_news`
- `target`: `/hnmnews`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/hnmuseum/hnmnews",
  "heat": 0,
  "location": "hnmnews.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "HNM News",
  "path": "/hnmnews",
  "radar": [
    {
      "source": [
        "www.hnmuseum.com/zh-hans/xiangbo_dongtai_news"
      ],
      "target": "/hnmnews"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processTimers (node:internal/timers:538:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
