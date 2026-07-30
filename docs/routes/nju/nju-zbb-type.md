# 南京大学 - 招标办公室

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/zbb/:type`
- Route Name: `招标办公室`
- Example: `/nju/zbb/cgxx`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `zbb.ts`
- Source Module: `_None_`

## Description
| 采购信息 | 成交公示 | 政府采购意向公开 |
| -------- | -------- | ---------------- |
| cgxx     | cjgs     | zfcgyxgk         |

## Parameters
- `type`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 采购信息 | 成交公示 | 政府采购意向公开 |\n| -------- | -------- | ---------------- |\n| cgxx     | cjgs     | zfcgyxgk         |",
  "example": "/nju/zbb/cgxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "zbb.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "招标办公室",
  "parameters": {
    "type": "分类名"
  },
  "path": "/zbb/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "采购信息 - Powered by RSSHub",
      "errorAt": "2025-05-20T00:31:11.844Z",
      "errorMessage": "[GET] \"https://zbb.nju.edu.cn/cgxxfw/index.chtml\": 403 Forbidden\n",
      "id": "62660944911329280",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zbb.nju.edu.cn/cgxxhw/index.chtml",
      "title": "采购信息",
      "type": "feed",
      "url": "rsshub://nju/zbb/cgxx"
    }
  ]
}
```
