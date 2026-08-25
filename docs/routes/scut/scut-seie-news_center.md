# 华南理工大学 - 电子与信息学院 - 新闻速递

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/scut/seie/news_center`
- Route Name: `电子与信息学院 - 新闻速递`
- Example: `/scut/seie/news_center`
- URL: `www2.scut.edu.cn/ee/16285/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `auto-bot-ty`
- Source Location: `seie/news-ccenter.ts`
- Source Module: `_None_`

## Description
::: warning
由于学院官网对非大陆 IP 的访问存在限制，需自行部署。
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
  - `www2.scut.edu.cn/ee/16285/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: warning\n由于学院官网对非大陆 IP 的访问存在限制，需自行部署。\n:::",
  "example": "/scut/seie/news_center",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "seie/news-ccenter.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "name": "电子与信息学院 - 新闻速递",
  "parameters": {},
  "path": "/seie/news_center",
  "radar": [
    {
      "source": [
        "www2.scut.edu.cn/ee/16285/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:597:9)\n    at processTimers (node:internal/timers:571:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www2.scut.edu.cn/ee/16285/list.htm"
}
```
