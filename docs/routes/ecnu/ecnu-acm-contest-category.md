# East China Normal University 华东师范大学 - ACM Online-Judge contests list

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/acm/contest/:category?`
- Route Name: `ACM Online-Judge contests list`
- Example: `/ecnu/acm/contest/public`
- URL: `acm.ecnu.edu.cn/contest/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `a180285`
- Source Location: `contest.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: category is optional, default is all, use `public` for public only contests


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
  - `acm.ecnu.edu.cn/contest/`
  - `acm.ecnu.edu.cn/`
- `target`: `/acm/contest/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/acm/contest/public",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "contest.tsx",
  "maintainers": [
    "a180285"
  ],
  "name": "ACM Online-Judge contests list",
  "parameters": {
    "category": "category is optional, default is all, use `public` for public only contests"
  },
  "path": "/acm/contest/:category?",
  "radar": [
    {
      "source": [
        "acm.ecnu.edu.cn/contest/",
        "acm.ecnu.edu.cn/"
      ],
      "target": "/acm/contest/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:597:9)\n    at processTimers (node:internal/timers:571:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "acm.ecnu.edu.cn/contest/"
}
```
