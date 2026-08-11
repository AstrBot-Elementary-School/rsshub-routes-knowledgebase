# 中国国际航空公司 - 服务公告

## Coverage
`index-only`

## Route
- Namespace: `airchina`
- Namespace Name: `中国国际航空公司`
- Route Path: `/airchina/announcement`
- Route Name: `服务公告`
- Example: `/airchina/announcement`
- URL: `www.airchina.com.cn/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `LandonLi`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `www.airchina.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/airchina/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "LandonLi"
  ],
  "name": "服务公告",
  "parameters": {},
  "path": "/announcement",
  "radar": [
    {
      "source": [
        "www.airchina.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.airchina.com.cn/"
}
```
