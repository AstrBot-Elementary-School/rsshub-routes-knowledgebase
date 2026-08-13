# 白话区块链 - 首页

## Coverage
`index-only`

## Route
- Namespace: `hellobtc`
- Namespace Name: `白话区块链`
- Route Path: `/hellobtc/information/:channel?`
- Route Name: `首页`
- Example: `/hellobtc/information/latest`
- URL: `hellobtc.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `information.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 类型，可填 `latest` 和 `application` 及最新和应用，默认为最新


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
    "new-media"
  ],
  "example": "/hellobtc/information/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 353,
  "location": "information.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "首页",
  "parameters": {
    "channel": "类型，可填 `latest` 和 `application` 及最新和应用，默认为最新"
  },
  "path": "/information/:channel?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "白话区块链 - 首页 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84224879488972800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hellobtc.com/",
      "title": "白话区块链 - 首页 最新",
      "type": "feed",
      "url": "rsshub://hellobtc/information"
    },
    {
      "description": "白话区块链 - 首页 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56162621363945472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hellobtc.com/",
      "title": "白话区块链 - 首页 最新",
      "type": "feed",
      "url": "rsshub://hellobtc/information/latest"
    }
  ]
}
```
