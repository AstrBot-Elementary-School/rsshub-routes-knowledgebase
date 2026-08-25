# DailyArt 每日艺术 - DailyArt

## Coverage
`index-only`

## Route
- Namespace: `getdailyart`
- Namespace Name: `DailyArt 每日艺术`
- Route Path: `/getdailyart/:language?`
- Route Name: `DailyArt`
- Example: `/getdailyart/en`
- URL: `www.getdailyart.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Support en, es, fr, de, it, zh, jp, etc. English by default.


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/getdailyart/en",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "DailyArt",
  "parameters": {
    "language": "Support en, es, fr, de, it, zh, jp, etc. English by default."
  },
  "path": "/:language?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
