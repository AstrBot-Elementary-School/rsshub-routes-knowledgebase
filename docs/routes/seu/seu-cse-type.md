# 东南大学 - 计算机技术与工程学院

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/seu/cse/:type?`
- Route Name: `计算机技术与工程学院`
- Example: `/seu/cse/xyxw`
- URL: `cse.seu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LogicJake`
- Source Location: `cse/index.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 教务信息 | 就业信息 | 学工事务 |
| -------- | -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | jwxx     | jyxx     | xgsw     |

## Parameters
- `type`: 分类名，默认为 `xyxw`


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
  - `cse.seu.edu.cn/:type/list.htm`
  - `cse.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 教务信息 | 就业信息 | 学工事务 |\n| -------- | -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | jwxx     | jyxx     | xgsw     |",
  "example": "/seu/cse/xyxw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cse/index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "计算机技术与工程学院",
  "parameters": {
    "type": "分类名，默认为 `xyxw`"
  },
  "path": "/cse/:type?",
  "radar": [
    {
      "source": [
        "cse.seu.edu.cn/:type/list.htm",
        "cse.seu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
