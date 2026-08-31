# 西南石油大学 - 电气信息学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/dxy/:code`
- Route Name: `电气信息学院`
- Example: `/swpu/dxy/1156`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `CYTMWIA`
- Source Location: `dxy.ts`
- Source Module: `_None_`

## Description
| 栏目 | 学院新闻 | 学院通知 |
| ---- | -------- | -------- |
| 代码 | 1122     | 1156     |

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
  "description": "| 栏目 | 学院新闻 | 学院通知 |\n| ---- | -------- | -------- |\n| 代码 | 1122     | 1156     |",
  "example": "/swpu/dxy/1156",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dxy.ts",
  "maintainers": [
    "CYTMWIA"
  ],
  "name": "电气信息学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/dxy/:code",
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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "swpu.edu.cn/"
}
```
