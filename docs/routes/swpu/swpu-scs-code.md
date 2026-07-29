# 西南石油大学 - 计算机与软件学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/scs/:code`
- Route Name: `计算机与软件学院`
- Example: `/swpu/scs/tzgg`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `scs.ts`
- Source Module: `_None_`

## Description
| 栏目 | 通知公告 | 新闻速递 |
| ---- | -------- | -------- |
| 代码 | tzgg     | xwsd     |

## Parameters
- `code`: 栏目代码


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
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 通知公告 | 新闻速递 |\n| ---- | -------- | -------- |\n| 代码 | tzgg     | xwsd     |",
  "example": "/swpu/scs/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "scs.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "name": "计算机与软件学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/scs/:code",
  "radar": [
    {
      "source": [
        "swpu.edu.cn/"
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
      "description": "西南石油大学计算机与软件学院 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "105536705249716224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.swpu.edu.cn/scs/index/tzgg.htm",
      "title": "西南石油大学计算机与软件学院",
      "type": "feed",
      "url": "rsshub://swpu/scs/tzgg"
    }
  ],
  "url": "swpu.edu.cn/"
}
```
