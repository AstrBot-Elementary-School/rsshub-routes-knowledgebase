# 上海海事大学 - 官网信息

## Coverage
`index-only`

## Route
- Namespace: `shmtu`
- Namespace Name: `上海海事大学`
- Route Path: `/shmtu/www/:type`
- Route Name: `官网信息`
- Example: `/shmtu/www/events`
- URL: `jwc.shmtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `imbytecat, simonsmh`
- Source Location: `www.ts`
- Source Module: `_None_`

## Description
| 学术讲座 | 通知公告 |
| -------- | -------- |
| events   | notes    |

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
  - `www.shmtu.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学术讲座 | 通知公告 |\n| -------- | -------- |\n| events   | notes    |",
  "example": "/shmtu/www/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "www.ts",
  "maintainers": [
    "imbytecat",
    "simonsmh"
  ],
  "name": "官网信息",
  "parameters": {
    "type": "类型名称"
  },
  "path": "/www/:type",
  "radar": [
    {
      "source": [
        "www.shmtu.edu.cn/:type"
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
