# 金色财经 - 首页

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/jinse/timeline/:category?`
- Route Name: `首页`
- Example: `/jinse/timeline`
- URL: `jinse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
| 头条   | 独家 | 铭文    | 产业       | 项目 |
| ------ | ---- | ------- | ---------- | ---- |
| 政策   | AI   | Web 3.0 | 以太坊 2.0 | DeFi |
| Layer2 | NFT  | DAO     | 百科       |      |

## Parameters
- `category`: {"default": "头条", "description": "分类", "options": [{"label": "头条", "value": "头条"}, {"label": "独家", "value": "独家"}, {"label": "铭文", "value": "铭文"}, {"label": "产业", "value": "产业"}, {"label": "项目", "value": "项目"}, {"label": "政策", "value": "政策"}, {"label": "AI", "value": "AI"}, {"label": "Web 3.0", "value": "Web 3.0"}, {"label": "以太坊 2.0", "value": "以太坊 2.0"}, {"label": "DeFi", "value": "DeFi"}, {"label": "Layer2", "value": "Layer2"}, {"label": "NFT", "value": "NFT"}, {"label": "DAO", "value": "DAO"}, {"label": "百科", "value": "百科"}]}


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
  "description": "| 头条   | 独家 | 铭文    | 产业       | 项目 |\n| ------ | ---- | ------- | ---------- | ---- |\n| 政策   | AI   | Web 3.0 | 以太坊 2.0 | DeFi |\n| Layer2 | NFT  | DAO     | 百科       |      |",
  "example": "/jinse/timeline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 231,
  "location": "timeline.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "首页",
  "parameters": {
    "category": {
      "default": "头条",
      "description": "分类",
      "options": [
        {
          "label": "头条",
          "value": "头条"
        },
        {
          "label": "独家",
          "value": "独家"
        },
        {
          "label": "铭文",
          "value": "铭文"
        },
        {
          "label": "产业",
          "value": "产业"
        },
        {
          "label": "项目",
          "value": "项目"
        },
        {
          "label": "政策",
          "value": "政策"
        },
        {
          "label": "AI",
          "value": "AI"
        },
        {
          "label": "Web 3.0",
          "value": "Web 3.0"
        },
        {
          "label": "以太坊 2.0",
          "value": "以太坊 2.0"
        },
        {
          "label": "DeFi",
          "value": "DeFi"
        },
        {
          "label": "Layer2",
          "value": "Layer2"
        },
        {
          "label": "NFT",
          "value": "NFT"
        },
        {
          "label": "DAO",
          "value": "DAO"
        },
        {
          "label": "百科",
          "value": "百科"
        }
      ]
    }
  },
  "path": "/timeline/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "undefined - 头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72573294615394304",
      "image": "https://staticn.jinse.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jinse.com.cn/",
      "title": "undefined - 头条",
      "type": "feed",
      "url": "rsshub://jinse/timeline/%E5%A4%B4%E6%9D%A1"
    },
    {
      "description": "undefined - Web 3.0 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73179190070635520",
      "image": "https://staticn.jinse.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://www.jinse.com.cn/",
      "title": "undefined - Web 3.0",
      "type": "feed",
      "url": "rsshub://jinse/timeline/Web%203.0"
    }
  ],
  "view": 0
}
```
