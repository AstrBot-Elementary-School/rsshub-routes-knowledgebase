# 白话区块链 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `hellobtc`
- Namespace Name: `白话区块链`
- Route Path: `/hellobtc/news`
- Route Name: `快讯`
- Example: `/hellobtc/news`
- URL: `hellobtc.com/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `news.ts`
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
  - `hellobtc.com/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hellobtc/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 187,
  "location": "news.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "hellobtc.com/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "白话区块链 - 快讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56160660953715712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hellobtc.com/news",
      "title": "白话区块链 - 快讯",
      "type": "feed",
      "url": "rsshub://hellobtc/news"
    }
  ],
  "url": "hellobtc.com/news"
}
```
