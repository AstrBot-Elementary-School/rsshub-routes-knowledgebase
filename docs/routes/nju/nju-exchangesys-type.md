# 南京大学 - 本科生交换生系统

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/exchangesys/:type`
- Route Name: `本科生交换生系统`
- Example: `/nju/exchangesys/proj`
- URL: `admission.nju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cqjjjzr`
- Source Location: `exchangesys.ts`
- Source Module: `_None_`

## Description
| 新闻通知 | 交换生项目 |
| -------- | ---------- |
| news     | proj       |

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
  "description": "| 新闻通知 | 交换生项目 |\n| -------- | ---------- |\n| news     | proj       |",
  "example": "/nju/exchangesys/proj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "exchangesys.ts",
  "maintainers": [
    "cqjjjzr"
  ],
  "name": "本科生交换生系统",
  "parameters": {
    "type": "分类名"
  },
  "path": "/exchangesys/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
