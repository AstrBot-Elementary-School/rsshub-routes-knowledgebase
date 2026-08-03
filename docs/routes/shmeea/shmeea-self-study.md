# 上海市教育考试院 - 自学考试通知公告

## Coverage
`index-only`

## Route
- Namespace: `shmeea`
- Namespace Name: `上海市教育考试院`
- Route Path: `/shmeea/self-study`
- Route Name: `自学考试通知公告`
- Example: `/shmeea/self-study`
- URL: `www.shmeea.edu.cn/page/04000/index.html`
- Language: `_None_`
- Categories: `study`
- Maintainers: `h2ws`
- Source Location: `self-study.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.shmeea.edu.cn/page/04000/index.html`
  - `www.shmeea.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/shmeea/self-study",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "self-study.ts",
  "maintainers": [
    "h2ws"
  ],
  "name": "自学考试通知公告",
  "parameters": {},
  "path": "/self-study",
  "radar": [
    {
      "source": [
        "www.shmeea.edu.cn/page/04000/index.html",
        "www.shmeea.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.shmeea.edu.cn/page/04000/index.html"
}
```
