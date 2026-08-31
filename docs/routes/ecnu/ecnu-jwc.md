# East China Normal University 华东师范大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/jwc`
- Route Name: `教务处通知`
- Example: `/ecnu/jwc`
- URL: `www.ecnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `markbang`
- Source Location: `jwc.ts`
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
  - `www.jwc.ecnu.edu.cn`
- `target`: `/tzgg`
### Rule 2
- `source`:
  - `www.ecnu.edu.cn`
- `target`: `/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/jwc",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "markbang"
  ],
  "name": "教务处通知",
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "www.jwc.ecnu.edu.cn"
      ],
      "target": "/tzgg"
    },
    {
      "source": [
        "www.ecnu.edu.cn"
      ],
      "target": "/tzgg"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
