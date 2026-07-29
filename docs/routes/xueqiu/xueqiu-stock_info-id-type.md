# 雪球 - 股票信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/stock_info/:id/:type?`
- Route Name: `股票信息`
- Example: `/xueqiu/stock_info/SZ000002`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `YuYang`
- Source Location: `stock-info.ts`
- Source Module: `_None_`

## Description
| 全部 | 讨论    | 交易  | 资讯 | 公告         |
| ---- | ------- | ----- | ---- | ------------ |
| all  | discuss | trans | news | announcement |

## Parameters
- `id`: 股票代码（需要带上交易所）
- `type`: 动态的类型, 不填则为股票公告


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/S/:id`
  - `xueqiu.com/s/:id`
- `target`: `/stock_info/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 全部 | 讨论    | 交易  | 资讯 | 公告         |\n| ---- | ------- | ----- | ---- | ------------ |\n| all  | discuss | trans | news | announcement |",
  "example": "/xueqiu/stock_info/SZ000002",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 31,
  "location": "stock-info.ts",
  "maintainers": [
    "YuYang"
  ],
  "name": "股票信息",
  "parameters": {
    "id": "股票代码（需要带上交易所）",
    "type": "动态的类型, 不填则为股票公告"
  },
  "path": "/stock_info/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id",
        "xueqiu.com/s/:id"
      ],
      "target": "/stock_info/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "兆易创新 - 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64923928046286858",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603986",
      "title": "SH603986 兆易创新 - 资讯",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603986/news"
    },
    {
      "description": "豪威集团 - 公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64923928046286863",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603501",
      "title": "SH603501 豪威集团 - 公告",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603501"
    }
  ]
}
```
