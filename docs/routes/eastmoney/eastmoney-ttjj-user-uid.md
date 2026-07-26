# 东方财富 - 天天基金用户动态

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/ttjj/user/:uid`
- Route Name: `天天基金用户动态`
- Example: `/eastmoney/ttjj/user/6551094298949188`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `zidekuls`
- Source Location: `ttjj/user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户id, 可以通过天天基金App分享用户主页到浏览器，在相应的URL中找到


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
    "finance"
  ],
  "example": "/eastmoney/ttjj/user/6551094298949188",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 63,
  "location": "ttjj/user.ts",
  "maintainers": [
    "zidekuls"
  ],
  "name": "天天基金用户动态",
  "parameters": {
    "uid": "用户id, 可以通过天天基金App分享用户主页到浏览器，在相应的URL中找到"
  },
  "path": "/ttjj/user/:uid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "范范爱养基 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63493307705393157",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fundbarmob.eastmoney.com/index.html?goPage=personDetailView&userid=7185105344679198",
      "title": "天天基金-范范爱养基的主页",
      "type": "feed",
      "url": "rsshub://eastmoney/ttjj/user/7185105344679198"
    },
    {
      "description": "herorose 的动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73927094898480128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://fundbarmob.eastmoney.com/index.html?goPage=personDetailView&userid=5262112004185016",
      "title": "天天基金-herorose的主页",
      "type": "feed",
      "url": "rsshub://eastmoney/ttjj/user/5262112004185016"
    }
  ],
  "view": 1
}
```
