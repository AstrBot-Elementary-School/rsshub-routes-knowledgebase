# GoFans - 最新限免 / 促销应用

## Coverage
`index-only`

## Route
- Namespace: `gofans`
- Namespace Name: `GoFans`
- Route Path: `/gofans/:kind?`
- Route Name: `最新限免 / 促销应用`
- Example: `/gofans`
- URL: `gofans.cn`
- Language: `_None_`
- Categories: `program-update, popular`
- Maintainers: `HenryQW`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `kind`: Platform, either `macos` or `ios`, empty means both (default)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update",
    "popular"
  ],
  "example": "/gofans",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2721,
  "location": "index.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "name": "最新限免 / 促销应用",
  "parameters": {
    "kind": "Platform, either `macos` or `ios`, empty means both (default)"
  },
  "path": "/:kind?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(5) ] to not include 'https://gofans.cn/app/8cdf1858-88f8-4…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "GoFans：最新限免 / 促销应用 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56186320238063616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gofans.cn/",
      "title": "最新限免 / 促销应用",
      "type": "feed",
      "url": "rsshub://gofans"
    },
    {
      "description": "GoFans：最新限免 / 促销应用 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82638766362757120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gofans.cn/",
      "title": "最新限免 / 促销应用",
      "type": "feed",
      "url": "rsshub://gofans/ios"
    }
  ]
}
```
