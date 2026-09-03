# 雪球 - 蛋卷基金净值更新

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/fund/:id`
- Route Name: `蛋卷基金净值更新`
- Example: `/xueqiu/fund/040008`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `HenryQW, NathanDai`
- Source Location: `fund.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 基金代码, 可在基金主页 URL 中找到. 此路由的数据为场外基金 (`F`开头)


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
  "example": "/xueqiu/fund/040008",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "fund.ts",
  "maintainers": [
    "HenryQW",
    "NathanDai"
  ],
  "name": "蛋卷基金净值更新",
  "parameters": {
    "id": "基金代码, 可在基金主页 URL 中找到. 此路由的数据为场外基金 (`F`开头)"
  },
  "path": "/fund/:id",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "基金代码 019305 <br> 今日净值(2026-08-31) ¥1.6919 <br> 日跌跌 -0.2711% - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64899751385970688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://danjuanapp.com/funding/019305",
      "title": "摩根标普500指数(QDII)人民币C",
      "type": "feed",
      "url": "rsshub://xueqiu/fund/019305"
    },
    {
      "description": "基金代码 017093 <br> 今日净值(2026-08-31) ¥2.8260 <br> 日跌跌 -0.0743% - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64899487882088448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://danjuanapp.com/funding/017093",
      "title": "景顺长城纳斯达克科技指数（QDII）C人民币",
      "type": "feed",
      "url": "rsshub://xueqiu/fund/017093"
    }
  ]
}
```
