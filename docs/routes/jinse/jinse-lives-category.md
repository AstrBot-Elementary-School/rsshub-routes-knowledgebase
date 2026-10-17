# 金色财经 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/jinse/lives/:category?`
- Route Name: `快讯`
- Example: `/jinse/lives`
- URL: `jinse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `lives.ts`
- Source Module: `_None_`

## Description
| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |
| ---- | ---- | ---- | ---- | --- | ---- |
| 0    | 1    | 2    | 3    | 4   | 5    |

## Parameters
- `category`: {"default": "0", "description": "分类", "options": [{"label": "全部", "value": "0"}, {"label": "精选", "value": "1"}, {"label": "政策", "value": "2"}, {"label": "数据", "value": "3"}, {"label": "NFT", "value": "4"}, {"label": "项目", "value": "5"}]}


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
  "description": "| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |\n| ---- | ---- | ---- | ---- | --- | ---- |\n| 0    | 1    | 2    | 3    | 4   | 5    |",
  "example": "/jinse/lives",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1056,
  "location": "lives.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "快讯",
  "parameters": {
    "category": {
      "default": "0",
      "description": "分类",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "精选",
          "value": "1"
        },
        {
          "label": "政策",
          "value": "2"
        },
        {
          "label": "数据",
          "value": "3"
        },
        {
          "label": "NFT",
          "value": "4"
        },
        {
          "label": "项目",
          "value": "5"
        }
      ]
    }
  },
  "path": "/lives/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "区块链新闻频道为您24小时提供最新区块链新闻信息，汇集全球各个区域最新消息，并为您提供最及时全面的区块链资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56701589104355328",
      "image": "https://staticn.jinse.com.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://jinse.com.cn/lives",
      "title": "金色财经 - 全部",
      "type": "feed",
      "url": "rsshub://jinse/lives/0"
    },
    {
      "description": "区块链新闻频道为您24小时提供最新区块链新闻信息，汇集全球各个区域最新消息，并为您提供最及时全面的区块链资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72606914246960128",
      "image": "https://staticn.jinse.com.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://jinse.com.cn/lives",
      "title": "金色财经 - 精选",
      "type": "feed",
      "url": "rsshub://jinse/lives/1"
    }
  ],
  "view": 5
}
```
