# 上海海事大学 - 数字平台

## Coverage
`index-only`

## Route
- Namespace: `shmtu`
- Namespace Name: `上海海事大学`
- Route Path: `/shmtu/portal/:type`
- Route Name: `数字平台`
- Example: `/shmtu/portal/bmtzgg`
- URL: `jwc.shmtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `imbytecat`
- Source Location: `portal.tsx`
- Source Module: `_None_`

## Description
| 部门通知公告 | 学术与大型活动公告 | 部门动态 |
| ------------ | ------------------ | -------- |
| bmtzgg       | xsydxhdgg          | bmdt     |

## Parameters
- `type`: 类型名称


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
  - `portal.shmtu.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 部门通知公告 | 学术与大型活动公告 | 部门动态 |\n| ------------ | ------------------ | -------- |\n| bmtzgg       | xsydxhdgg          | bmdt     |",
  "example": "/shmtu/portal/bmtzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "portal.tsx",
  "maintainers": [
    "imbytecat"
  ],
  "name": "数字平台",
  "parameters": {
    "type": "类型名称"
  },
  "path": "/portal/:type",
  "radar": [
    {
      "source": [
        "portal.shmtu.edu.cn/:type"
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
