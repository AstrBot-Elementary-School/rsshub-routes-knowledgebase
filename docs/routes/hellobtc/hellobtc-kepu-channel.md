# 白话区块链 - 科普

## Coverage
`index-only`

## Route
- Namespace: `hellobtc`
- Namespace Name: `白话区块链`
- Route Path: `/hellobtc/kepu/:channel?`
- Route Name: `科普`
- Example: `/hellobtc/kepu/latest`
- URL: `hellobtc.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `kepu.ts`
- Source Module: `_None_`

## Description
| latest | bitcoin | ethereum | defi | inter\_blockchain | mining | safety | satoshi\_nakomoto | public\_blockchain |
| ------ | ------- | -------- | ---- | ----------------- | ------ | ------ | ----------------- | ------------------ |
| 最新   | 比特币  | 以太坊   | DeFi | 跨链              | 挖矿   | 安全   | 中本聪            | 公链               |

## Parameters
- `channel`: 类型，见下表，默认为最新


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
  "description": "| latest | bitcoin | ethereum | defi | inter\\_blockchain | mining | safety | satoshi\\_nakomoto | public\\_blockchain |\n| ------ | ------- | -------- | ---- | ----------------- | ------ | ------ | ----------------- | ------------------ |\n| 最新   | 比特币  | 以太坊   | DeFi | 跨链              | 挖矿   | 安全   | 中本聪            | 公链               |",
  "example": "/hellobtc/kepu/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 139,
  "location": "kepu.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "科普",
  "parameters": {
    "channel": "类型，见下表，默认为最新"
  },
  "path": "/kepu/:channel?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "白话区块链 - 科普 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68130315498749952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hellobtc.com/kepu.html",
      "title": "白话区块链 - 科普 最新",
      "type": "feed",
      "url": "rsshub://hellobtc/kepu"
    },
    {
      "description": "白话区块链 - 科普 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52357479509098526",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hellobtc.com/kepu.html",
      "title": "白话区块链 - 科普 最新",
      "type": "feed",
      "url": "rsshub://hellobtc/kepu/latest"
    }
  ]
}
```
