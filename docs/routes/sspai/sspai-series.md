# 少数派 sspai - 最新上架付费专栏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/series`
- Route Name: `最新上架付费专栏`
- Example: `/sspai/series`
- URL: `sspai.com/series`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
> 少数派专栏需要付费订阅，RSS 仅做更新提醒，不含付费内容.

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
  - `sspai.com/series`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "> 少数派专栏需要付费订阅，RSS 仅做更新提醒，不含付费内容.",
  "example": "/sspai/series",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 52,
  "location": "series.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "最新上架付费专栏",
  "parameters": {},
  "path": "/series",
  "radar": [
    {
      "source": [
        "sspai.com/series"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(25) ] to not include 'https://sspai.com/series/380'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "少数派 -- 最新上架付费专栏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55218960049839106",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/series",
      "title": "少数派 -- 最新上架付费专栏",
      "type": "feed",
      "url": "rsshub://sspai/series"
    }
  ],
  "url": "sspai.com/series"
}
```
