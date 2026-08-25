# 安徽农业大学 - 人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `ahau`
- Namespace Name: `安徽农业大学`
- Route Path: `/ahau/cs_news/:type`
- Route Name: `人工智能学院`
- Example: `/ahau/cs_news/tzgg`
- URL: `xzxy.ahau.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SimonHu-HN`
- Source Location: `cs-news.ts`
- Source Module: `_None_`

## Description
| 学院要闻 | 通知公告 |
| -------- | -------- |
| xyyw     | tzgg     |

## Parameters
- `type`: 类型名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `xzxy.ahau.edu.cn/index/:type.htm`
- `target`: `/cs_news/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院要闻 | 通知公告 |\n| -------- | -------- |\n| xyyw     | tzgg     |",
  "example": "/ahau/cs_news/tzgg",
  "heat": 0,
  "location": "cs-news.ts",
  "maintainers": [
    "SimonHu-HN"
  ],
  "name": "人工智能学院",
  "parameters": {
    "type": "类型名"
  },
  "path": "/cs_news/:type",
  "radar": [
    {
      "source": [
        "xzxy.ahau.edu.cn/index/:type.htm"
      ],
      "target": "/cs_news/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "xzxy.ahau.edu.cn"
}
```
