# East China Normal University 华东师范大学 - 本科生院通知

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/bksy`
- Route Name: `本科生院通知`
- Example: `/ecnu/bksy`
- URL: `www.ecnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrozenStarrrr, ChiyoYuki, ECNU-minus`
- Source Location: `bksy.ts`
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
  - `bksy.ecnu.edu.cn`
- `target`: `/bksy`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/bksy",
  "heat": 0,
  "location": "bksy.ts",
  "maintainers": [
    "FrozenStarrrr",
    "ChiyoYuki",
    "ECNU-minus"
  ],
  "name": "本科生院通知",
  "path": "/bksy",
  "radar": [
    {
      "source": [
        "bksy.ecnu.edu.cn"
      ],
      "target": "/bksy"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
