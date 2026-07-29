# 南京大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/gra`
- Route Name: `研究生院`
- Example: `/nju/gra`
- URL: `grawww.nju.edu.cn/main.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `gra.ts`
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
  - `grawww.nju.edu.cn/main.htm`
  - `grawww.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/gra",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "gra.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "研究生院",
  "parameters": {},
  "path": "/gra",
  "radar": [
    {
      "source": [
        "grawww.nju.edu.cn/main.htm",
        "grawww.nju.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "研究生院-动态通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62660915118210048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://grawww.nju.edu.cn/905/list.htm",
      "title": "研究生院-动态通知",
      "type": "feed",
      "url": "rsshub://nju/gra"
    }
  ],
  "url": "grawww.nju.edu.cn/main.htm"
}
```
