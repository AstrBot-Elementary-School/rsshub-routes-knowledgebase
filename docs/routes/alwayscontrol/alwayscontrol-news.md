# Always Control - 最新动态

## Coverage
`index-only`

## Route
- Namespace: `alwayscontrol`
- Namespace Name: `Always Control`
- Route Path: `/alwayscontrol/news`
- Route Name: `最新动态`
- Example: `/alwayscontrol/news`
- URL: `alwayscontrol.com.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `moss-xxh`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
Always Control（旭衡电子）智能能源管理系统解决方案专家的最新动态

## Parameters
_None_


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
  - `www.alwayscontrol.com.cn/zh-CN/about/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Always Control（旭衡电子）智能能源管理系统解决方案专家的最新动态",
  "example": "/alwayscontrol/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "moss-xxh"
  ],
  "name": "最新动态",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.alwayscontrol.com.cn/zh-CN/about/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "alwayscontrol.com.cn"
}
```
