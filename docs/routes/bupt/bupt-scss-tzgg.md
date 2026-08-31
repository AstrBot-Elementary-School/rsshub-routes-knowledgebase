# 北京邮电大学 - 网络空间安全学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/scss/tzgg`
- Route Name: `网络空间安全学院 - 通知公告`
- Example: `/bupt/scss/tzgg`
- URL: `scss.bupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ziri2004`
- Source Location: `scss.ts`
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
  - `scss.bupt.edu.cn/index/tzgg1.htm`
- `target`: `/scss/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bupt/scss/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "scss.ts",
  "maintainers": [
    "ziri2004"
  ],
  "name": "网络空间安全学院 - 通知公告",
  "parameters": {},
  "path": "/scss/tzgg",
  "radar": [
    {
      "source": [
        "scss.bupt.edu.cn/index/tzgg1.htm"
      ],
      "target": "/scss/tzgg"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北京邮电大学网络空间安全学院 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-10-21T11:17:42.076Z",
      "errorMessage": "[GET] \"https://scss.bupt.edu.cn/index/tzgg1.htm\": 412 Precondition Failed\n",
      "id": "154793132955114496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://scss.bupt.edu.cn/index/tzgg1.htm",
      "title": "北京邮电大学网络空间安全学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://bupt/scss/tzgg"
    }
  ],
  "url": "scss.bupt.edu.cn"
}
```
