# 上海证券交易所 - 可转换公司债券公告

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/sse/convert/:query?`
- Route Name: `可转换公司债券公告`
- Example: `/sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=股份`
- URL: `bond.sse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `kt286`
- Source Location: `convert.ts`
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
  "example": "/sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=股份",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "convert.ts",
  "maintainers": [
    "kt286"
  ],
  "name": "可转换公司债券公告",
  "parameters": {
    "query": "筛选条件，见示例"
  },
  "path": "/convert/:query?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上证债券信息网 - 可转换公司债券公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68288320197921792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bond.sse.com.cn/disclosure/announ/convertible/",
      "title": "上证债券信息网 - 可转换公司债券公告",
      "type": "feed",
      "url": "rsshub://sse/convert"
    },
    {
      "description": "上证债券信息网 - 可转换公司债券公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165445337069434885",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bond.sse.com.cn/disclosure/announ/convertible/",
      "title": "上证债券信息网 - 可转换公司债券公告",
      "type": "feed",
      "url": "rsshub://sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=%E8%82%A1%E4%BB%BD"
    }
  ]
}
```
