# 地震速报 - 中国地震台

## Coverage
`index-only`

## Route
- Namespace: `earthquake`
- Namespace Name: `地震速报`
- Route Path: `/earthquake/ceic/:type?`
- Route Name: `中国地震台`
- Example: `/earthquake/ceic/1`
- URL: `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `SettingDust`
- Source Location: `ceic.ts`
- Source Module: `_None_`

## Description
| 参数 | 类型                        |
| ---- | --------------------------- |
| 1    | 最近 24 小时地震信息        |
| 2    | 最近 48 小时地震信息        |
| 5    | 最近一年 3.0 级以上地震信息 |
| 7    | 最近一年 3.0 级以下地震     |
| 8    | 最近一年 4.0 级以上地震信息 |
| 9    | 最近一年 5.0 级以上地震信息 |
| 0    | 最近一年 6.0 级以上地震信息 |

可通过全局过滤参数订阅您感兴趣的地区.

## Parameters
- `type`: 类型，见下表


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
  - `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
  - `www.cea.gov.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| 参数 | 类型                        |\n| ---- | --------------------------- |\n| 1    | 最近 24 小时地震信息        |\n| 2    | 最近 48 小时地震信息        |\n| 5    | 最近一年 3.0 级以上地震信息 |\n| 7    | 最近一年 3.0 级以下地震     |\n| 8    | 最近一年 4.0 级以上地震信息 |\n| 9    | 最近一年 5.0 级以上地震信息 |\n| 0    | 最近一年 6.0 级以上地震信息 |\n\n可通过全局过滤参数订阅您感兴趣的地区.",
  "example": "/earthquake/ceic/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "ceic.ts",
  "maintainers": [
    "SettingDust"
  ],
  "name": "中国地震台",
  "parameters": {
    "type": "类型，见下表"
  },
  "path": "/ceic/:type?",
  "radar": [
    {
      "source": [
        "www.cea.gov.cn/cea/xwzx/zqsd/index.html",
        "www.cea.gov.cn/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最近24小时地震信息 - Powered by RSSHub",
      "errorAt": "2024-09-29T07:49:59.550Z",
      "errorMessage": "Unexpected token '!', \"!doctype h\"... is not valid JSON\n",
      "id": "55611775416893440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.ceic.ac.cn/speedsearch",
      "title": "最近24小时地震信息",
      "type": "feed",
      "url": "rsshub://earthquake/ceic/1"
    }
  ],
  "url": "www.cea.gov.cn/cea/xwzx/zqsd/index.html"
}
```
