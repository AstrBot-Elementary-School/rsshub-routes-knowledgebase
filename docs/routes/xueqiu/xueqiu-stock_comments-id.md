# 雪球 - 股票评论

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/stock_comments/:id`
- Route Name: `股票评论`
- Example: `/xueqiu/stock_comments/SZ002626`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `zytomorrow`
- Source Location: `stock-comments.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 股票代码（需要带上交易所）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/S/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/stock_comments/SZ002626",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "stock-comments.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "股票评论",
  "parameters": {
    "id": "股票代码（需要带上交易所）"
  },
  "path": "/stock_comments/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "\"\" - 评论 - Powered by RSSHub",
      "errorAt": "2026-05-26T14:41:40.577Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "80941534035664896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SZ002626",
      "title": "SZ002626 \"\" - 评论",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_comments/SZ002626"
    },
    {
      "description": "\"\" - 评论 - Powered by RSSHub",
      "errorAt": "2026-05-26T10:38:11.486Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "80193087383814144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/HK00700",
      "title": "HK00700 \"\" - 评论",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_comments/HK00700"
    }
  ]
}
```
