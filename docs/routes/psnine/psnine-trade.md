# PSN 中文站 - 闲游

## Coverage
`index-only`

## Route
- Namespace: `psnine`
- Namespace Name: `PSN 中文站`
- Route Path: `/psnine/trade`
- Route Name: `闲游`
- Example: `/psnine/trade`
- URL: `psnine.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `betta-cyber`
- Source Location: `trade.ts`
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
  - `psnine.com/trade`
  - `psnine.com`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/psnine/trade",
  "heat": 1,
  "location": "trade.ts",
  "maintainers": [
    "betta-cyber"
  ],
  "name": "闲游",
  "path": "/trade",
  "radar": [
    {
      "source": [
        "psnine.com/trade",
        "psnine.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "闲游 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130453903130988544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.psnine.com/trade",
      "title": "闲游",
      "type": "feed",
      "url": "rsshub://psnine/trade"
    }
  ]
}
```
