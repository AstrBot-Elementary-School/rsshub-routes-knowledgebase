# Minhang Museum - 临时展览

## Coverage
`index-only`

## Route
- Namespace: `minhangmuseum`
- Namespace Name: `Minhang Museum`
- Route Path: `/minhangmuseum/interim`
- Route Name: `临时展览`
- Example: `/minhangmuseum/interim`
- URL: `minhangmuseum.shmh.gov.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `interim.tsx`
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
  - `minhangmuseum.shmh.gov.cn/weixin/interim/list.htm`
- `target`: `/interim`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/minhangmuseum/interim",
  "heat": 0,
  "location": "interim.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "临时展览",
  "path": "/interim",
  "radar": [
    {
      "source": [
        "minhangmuseum.shmh.gov.cn/weixin/interim/list.htm"
      ],
      "target": "/interim"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
