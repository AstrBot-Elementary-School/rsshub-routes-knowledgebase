# East China Normal University 华东师范大学 - 光华书院通知公告

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/ghcollege`
- Route Name: `光华书院通知公告`
- Example: `/ecnu/ghcollege`
- URL: `www.ecnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrozenStarrrr, ChiyoYuki, ECNU-minus`
- Source Location: `ghcollege.ts`
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
  - `www.ghcollege.ecnu.edu.cn`
- `target`: `/ghcollege`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/ghcollege",
  "heat": 0,
  "location": "ghcollege.ts",
  "maintainers": [
    "FrozenStarrrr",
    "ChiyoYuki",
    "ECNU-minus"
  ],
  "name": "光华书院通知公告",
  "path": "/ghcollege",
  "radar": [
    {
      "source": [
        "www.ghcollege.ecnu.edu.cn"
      ],
      "target": "/ghcollege"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
