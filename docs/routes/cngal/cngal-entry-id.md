# CnGal - 制作者 / 游戏新闻

## Coverage
`index-only`

## Route
- Namespace: `cngal`
- Namespace Name: `CnGal`
- Route Path: `/cngal/entry/:id`
- Route Name: `制作者 / 游戏新闻`
- Example: `/cngal/entry/2693`
- URL: `www.cngal.org`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kmod-midori`
- Source Location: `entry.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 词条ID，游戏或制作者页面URL的最后一串数字


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
  - `www.cngal.org/entries/index/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/cngal/entry/2693",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "entry.tsx",
  "maintainers": [
    "kmod-midori"
  ],
  "name": "制作者 / 游戏新闻",
  "parameters": {
    "id": "词条ID，游戏或制作者页面URL的最后一串数字"
  },
  "path": "/entry/:id",
  "radar": [
    {
      "source": [
        "www.cngal.org/entries/index/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(49) ] to not include 'https://weibo.com/7615758653/Ominv18wd'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "CnGal - Never Knows Best 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61405355190856704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cngal.org/entries/index/2693",
      "title": "CnGal - Never Knows Best 的动态",
      "type": "feed",
      "url": "rsshub://cngal/entry/2693"
    }
  ]
}
```
