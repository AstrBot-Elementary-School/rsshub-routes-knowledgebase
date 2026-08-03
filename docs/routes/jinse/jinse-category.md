# 金色财经 - 分类

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/jinse/:category?`
- Route Name: `分类`
- Example: `/jinse/zhengce`
- URL: `jinse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `catalogue.ts`
- Source Module: `_None_`

## Description
| 政策    | 行情         | DeFi | 矿业  | 以太坊 2.0 |
| ------- | ------------ | ---- | ----- | ---------- |
| zhengce | fenxishishuo | defi | kuang | 以太坊 2.0 |

| 产业     | IPFS | 技术 | 百科  | 研报          |
| -------- | ---- | ---- | ----- | ------------- |
| industry | IPFS | tech | baike | capitalmarket |

## Parameters
- `category`: 分类，见下表，默认为政策


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
  "description": "| 政策    | 行情         | DeFi | 矿业  | 以太坊 2.0 |\n| ------- | ------------ | ---- | ----- | ---------- |\n| zhengce | fenxishishuo | defi | kuang | 以太坊 2.0 |\n\n| 产业     | IPFS | 技术 | 百科  | 研报          |\n| -------- | ---- | ---- | ----- | ------------- |\n| industry | IPFS | tech | baike | capitalmarket |",
  "example": "/jinse/zhengce",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 207,
  "location": "catalogue.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为政策"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "undefined - 研报 - Powered by RSSHub",
      "errorAt": "2026-05-12T16:51:00.404Z",
      "errorMessage": "[GET] \"https://www.jinse.com/blockchain/3736402.html\": <no response> fetch failed (Client network socket disconnected before secure TLS connection was established)\n",
      "id": "67468126492383233",
      "image": "https://staticn.jinse.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jinse.com.cn/",
      "title": "undefined - 研报",
      "type": "feed",
      "url": "rsshub://jinse/capitalmarket"
    },
    {
      "description": "金色财经是集行业新闻、资讯、行情、数据等一站式区块链产业服务平台，我们追求及时、全面、专业、准确的资讯与数据，致力于为区块链创业者以及数字货币投资者提供最好的产品和服务。 - Powered by RSSHub",
      "errorAt": "2025-12-23T11:28:11.575Z",
      "errorMessage": "[GET] \"https://www.jinse.com/blockchain/3735949.html\": <no response> fetch failed (Client network socket disconnected before secure TLS connection was established)\n",
      "id": "73947446139746304",
      "image": "https://staticn.jinse.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jinse.cn/",
      "title": "金色财经 - 技术",
      "type": "feed",
      "url": "rsshub://jinse/tech"
    }
  ]
}
```
