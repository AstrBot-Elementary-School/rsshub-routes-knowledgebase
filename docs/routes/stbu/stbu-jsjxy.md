# 四川工商学院 - 计算机学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `stbu`
- Namespace Name: `四川工商学院`
- Route Path: `/stbu/jsjxy`
- Route Name: `计算机学院 - 通知公告`
- Example: `/stbu/jsjxy`
- URL: `jsjxy.stbu.edu.cn/news`
- Language: `_None_`
- Categories: `university`
- Maintainers: `HyperCherry`
- Source Location: `jsjxy.ts`
- Source Module: `_None_`

## Description
::: warning
计算机学院通知公告疑似禁止了非大陆 IP 访问，使用路由需要自行 [部署](https://docs.rsshub.app/deploy/)。
:::

## Parameters
_None_


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
  - `jsjxy.stbu.edu.cn/news`
  - `jsjxy.stbu.edu.cn`
### Rule 2
- `source`:
  - `stbu.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: warning\n计算机学院通知公告疑似禁止了非大陆 IP 访问，使用路由需要自行 [部署](https://docs.rsshub.app/deploy/)。\n:::",
  "example": "/stbu/jsjxy",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jsjxy.ts",
  "maintainers": [
    "HyperCherry"
  ],
  "name": "计算机学院 - 通知公告",
  "parameters": {},
  "path": "/jsjxy",
  "radar": [
    {
      "source": [
        "jsjxy.stbu.edu.cn/news",
        "jsjxy.stbu.edu.cn"
      ]
    },
    {
      "source": [
        "stbu.edu.cn"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jsjxy.stbu.edu.cn/news"
}
```
