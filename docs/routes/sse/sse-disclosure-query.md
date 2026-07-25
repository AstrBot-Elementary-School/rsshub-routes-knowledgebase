# 上海证券交易所 - 上市公司信息最新公告披露

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/sse/disclosure/:query?`
- Route Name: `上市公司信息最新公告披露`
- Example: `/sse/disclosure/beginDate=2018-08-18&endDate=2020-08-25&productId=600696`
- URL: `bond.sse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `harveyqiu`
- Source Location: `disclosure.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: 筛选条件，见示例


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
  "example": "/sse/disclosure/beginDate=2018-08-18&endDate=2020-08-25&productId=600696",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 63,
  "location": "disclosure.ts",
  "maintainers": [
    "harveyqiu"
  ],
  "name": "上市公司信息最新公告披露",
  "parameters": {
    "query": "筛选条件，见示例"
  },
  "path": "/disclosure/:query?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海证券交易所 - 上市公司信息 - 东风股份最新公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "115958109880213504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sse.com.cn/assortment/stock/list/info/announcement/index.shtml?productId=undefined",
      "title": "上海证券交易所 - 上市公司信息 - 东风股份最新公告",
      "type": "feed",
      "url": "rsshub://sse/disclosure"
    },
    {
      "description": "上海证券交易所 - 上市公司信息 - 公牛集团最新公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64944303082021888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.sse.com.cn/assortment/stock/list/info/announcement/index.shtml?productId=603195",
      "title": "上海证券交易所 - 上市公司信息 - 公牛集团最新公告",
      "type": "feed",
      "url": "rsshub://sse/disclosure/productId=603195"
    }
  ]
}
```
