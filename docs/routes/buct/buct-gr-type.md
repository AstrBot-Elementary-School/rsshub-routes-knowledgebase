# 北京化工大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `buct`
- Namespace Name: `北京化工大学`
- Route Path: `/buct/gr/:type`
- Route Name: `研究生院`
- Example: `/buct/gr/jzml`
- URL: `buct.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Epic-Creeper`
- Source Location: `gr.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "信息类型，可选值：tzgg（通知公告），jzml（简章目录），xgzc（相关政策）", "options": [{"label": "通知公告", "value": "tzgg"}, {"label": "简章目录", "value": "jzml"}, {"label": "相关政策", "value": "xgzc"}]}


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
  - `graduate.buct.edu.cn/1392/list.htm`
- `target`: `/gr/tzgg`
### Rule 2
- `source`:
  - `graduate.buct.edu.cn/jzml/list.htm`
- `target`: `/gr/jzml`
### Rule 3
- `source`:
  - `graduate.buct.edu.cn/1393/list.htm`
- `target`: `/gr/xgzc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/buct/gr/jzml",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gr.ts",
  "maintainers": [
    "Epic-Creeper"
  ],
  "name": "研究生院",
  "parameters": {
    "type": {
      "description": "信息类型，可选值：tzgg（通知公告），jzml（简章目录），xgzc（相关政策）",
      "options": [
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "简章目录",
          "value": "jzml"
        },
        {
          "label": "相关政策",
          "value": "xgzc"
        }
      ]
    }
  },
  "path": "/gr/:type",
  "radar": [
    {
      "source": [
        "graduate.buct.edu.cn/1392/list.htm"
      ],
      "target": "/gr/tzgg"
    },
    {
      "source": [
        "graduate.buct.edu.cn/jzml/list.htm"
      ],
      "target": "/gr/jzml"
    },
    {
      "source": [
        "graduate.buct.edu.cn/1393/list.htm"
      ],
      "target": "/gr/xgzc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "buct.edu.cn/"
}
```
