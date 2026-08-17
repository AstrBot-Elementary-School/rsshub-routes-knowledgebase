# 西南石油大学 - 财经学院

## Coverage
`index-only`

## Route
- Namespace: `swpu`
- Namespace Name: `西南石油大学`
- Route Path: `/swpu/cjxy/:code`
- Route Name: `财经学院`
- Example: `/swpu/cjxy/xyxw`
- URL: `swpu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `RiverTwilight`
- Source Location: `cjxy.ts`
- Source Module: `_None_`

## Description
| 栏目 | 学院新闻 | 学院通知 |
| ---- | -------- | -------- |
| 代码 | xyxw     | xytz     |

## Parameters
- `code`: 栏目代码


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
  - `swpu.edu.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 栏目 | 学院新闻 | 学院通知 |\n| ---- | -------- | -------- |\n| 代码 | xyxw     | xytz     |",
  "example": "/swpu/cjxy/xyxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cjxy.ts",
  "maintainers": [
    "RiverTwilight"
  ],
  "name": "财经学院",
  "parameters": {
    "code": "栏目代码"
  },
  "path": "/cjxy/:code",
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
  "topFeeds": [],
  "url": "swpu.edu.cn/"
}
```
