# 泉州师范学院 - 首页

## Coverage
`index-only`

## Route
- Namespace: `qztc`
- Namespace Name: `泉州师范学院`
- Route Path: `/qztc/home/:type`
- Route Name: `首页`
- Example: `/qztc/home/2093`
- URL: `www.qztc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `iQNRen`
- Source Location: `home/index.ts`
- Source Module: `_None_`

## Description
| 板块     | 参数 |
| -------- | ---- |
| 泉师新闻 | 2093 |
| 通知公告 | 2094 |
| 采购公告 | 2095 |
| 学术资讯 | xszx |
| 招聘信息 | 2226 |

## Parameters
- `type`: 分类，见下表


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
  - `www.qztc.edu.cn/:type/list.htm`
- `target`: `/home/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块     | 参数 |\n| -------- | ---- |\n| 泉师新闻 | 2093 |\n| 通知公告 | 2094 |\n| 采购公告 | 2095 |\n| 学术资讯 | xszx |\n| 招聘信息 | 2226 |",
  "example": "/qztc/home/2093",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "home/index.ts",
  "maintainers": [
    "iQNRen"
  ],
  "name": "首页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/home/:type",
  "radar": [
    {
      "source": [
        "www.qztc.edu.cn/:type/list.htm"
      ],
      "target": "/home/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.qztc.edu.cn"
}
```
