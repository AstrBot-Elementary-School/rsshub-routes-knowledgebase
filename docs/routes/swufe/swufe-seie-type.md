# 西南财经大学 - 经济信息工程学院

## Coverage
`index-only`

## Route
- Namespace: `swufe`
- Namespace Name: `西南财经大学`
- Route Path: `/swufe/seie/:type?`
- Route Name: `经济信息工程学院`
- Example: `/swufe/seie/tzgg`
- URL: `it.swufe.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Hivol`
- Source Location: `seie.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 |
| -------- | -------- |
| xyxw     | tzgg     |

## Parameters
- `type`: 分类名，默认为 tzgg


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `it.swufe.edu.cn/index/tzgg.htm`
- `target`: `/seie/tzgg`
### Rule 2
- `source`:
  - `it.swufe.edu.cn/index/xyxw.htm`
- `target`: `/seie/xyxw`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 |\n| -------- | -------- |\n| xyxw     | tzgg     |",
  "example": "/swufe/seie/tzgg",
  "heat": 0,
  "location": "seie.ts",
  "maintainers": [
    "Hivol"
  ],
  "name": "经济信息工程学院",
  "parameters": {
    "type": "分类名，默认为 tzgg"
  },
  "path": "/seie/:type?",
  "radar": [
    {
      "source": [
        "it.swufe.edu.cn/index/tzgg.htm"
      ],
      "target": "/seie/tzgg"
    },
    {
      "source": [
        "it.swufe.edu.cn/index/xyxw.htm"
      ],
      "target": "/seie/xyxw"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
