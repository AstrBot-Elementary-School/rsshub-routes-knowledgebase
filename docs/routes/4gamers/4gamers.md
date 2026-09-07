# 4Gamers - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/4gamers/`
- Route Name: `最新消息`
- Example: `/4gamers`
- URL: `www.4gamers.com.tw/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
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
  - `www.4gamers.com.tw/news`
  - `www.4gamers.com.tw/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4gamers",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "最新消息",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.4gamers.com.tw/news",
        "www.4gamers.com.tw/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.4gamers.com.tw/news"
}
```
