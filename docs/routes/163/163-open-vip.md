# 网易公开课 - 精品课程

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/open/vip`
- Route Name: `精品课程`
- Example: `/163/open/vip`
- URL: `vip.open.163.com/`
- Language: `_None_`
- Categories: `study`
- Maintainers: `hoilc`
- Source Location: `open/vip.tsx`
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
  - `vip.open.163.com/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/163/open/vip",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "open/vip.tsx",
  "maintainers": [
    "hoilc"
  ],
  "name": "精品课程",
  "parameters": {},
  "path": "/open/vip",
  "radar": [
    {
      "source": [
        "vip.open.163.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(29) ] to not include 'https://vip.open.163.com/courses/C3BB…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "网易公开课 - 精品课程 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56449674745420800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vip.open.163.com/",
      "title": "网易公开课 - 精品课程",
      "type": "feed",
      "url": "rsshub://163/open/vip"
    }
  ],
  "url": "vip.open.163.com/"
}
```
