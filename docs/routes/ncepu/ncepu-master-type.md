# 华北电力大学 - 北京校区研究生院

## Coverage
`index-only`

## Route
- Namespace: `ncepu`
- Namespace Name: `华北电力大学`
- Route Path: `/ncepu/master/:type`
- Route Name: `北京校区研究生院`
- Example: `/ncepu/master/tzgg`
- URL: `yjsy.ncepu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nilleo`
- Source Location: `master/masterinfo.ts`
- Source Module: `_None_`

## Description
| 类型 | 硕士招生信息 | 通知公告 | 研究生培养信息 |
| ---- | ------------ | -------- | -------------- |
| 参数 | zsxx         | tzgg     | pyxx           |

## Parameters
- `type`: 类型参数


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
  "description": "| 类型 | 硕士招生信息 | 通知公告 | 研究生培养信息 |\n| ---- | ------------ | -------- | -------------- |\n| 参数 | zsxx         | tzgg     | pyxx           |",
  "example": "/ncepu/master/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "master/masterinfo.ts",
  "maintainers": [
    "nilleo"
  ],
  "name": "北京校区研究生院",
  "parameters": {
    "type": "类型参数"
  },
  "path": "/master/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "华北电力大学研究生院通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65669192695359488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://yjsy.ncepu.edu.cn/tzgg",
      "title": "通知公告-华北电力大学研究生院",
      "type": "feed",
      "url": "rsshub://ncepu/master/tzgg"
    }
  ]
}
```
