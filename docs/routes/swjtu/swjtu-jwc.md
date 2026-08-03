# 西南交通大学 - 教务网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/jwc`
- Route Name: `教务网`
- Example: `/swjtu/jwc`
- URL: `jwc.swjtu.edu.cn/vatuu/WebAction`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.swjtu.edu.cn/vatuu/WebAction`
  - `jwc.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/swjtu/jwc",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "jwc.ts",
  "maintainers": [
    "mobyw"
  ],
  "name": "教务网",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.swjtu.edu.cn/vatuu/WebAction",
        "jwc.swjtu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "西南交大-教务网通知 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72512219481102339",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://jwc.swjtu.edu.cn/vatuu/WebAction?setAction=newsList",
      "title": "西南交大-教务网通知",
      "type": "feed",
      "url": "rsshub://swjtu/jwc"
    }
  ],
  "url": "jwc.swjtu.edu.cn/vatuu/WebAction"
}
```
