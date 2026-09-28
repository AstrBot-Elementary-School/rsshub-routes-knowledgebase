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
  "heat": 351,
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
    "code": 0
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
