# 东方财富 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/eastmoney/search/:keyword`
- Route Name: `搜索`
- Example: `/eastmoney/search/web3`
- URL: `data.eastmoney.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `drgnchan`
- Source Location: `search/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，可以设置为自己需要检索的关键词


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
  "example": "/eastmoney/search/web3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 483,
  "location": "search/index.ts",
  "maintainers": [
    "drgnchan"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键词，可以设置为自己需要检索的关键词"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "东方财富网 - 搜索'期货' - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73528214634595328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://so.eastmoney.com/News/s?KeyWord=%E6%9C%9F%E8%B4%A7",
      "title": "东方财富网 - 搜索'期货'",
      "type": "feed",
      "url": "rsshub://eastmoney/search/%E6%9C%9F%E8%B4%A7"
    },
    {
      "description": "东方财富网 - 搜索'web3' - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65980643863635968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://so.eastmoney.com/News/s?KeyWord=web3",
      "title": "东方财富网 - 搜索'web3'",
      "type": "feed",
      "url": "rsshub://eastmoney/search/web3"
    }
  ],
  "view": 0
}
```
