# LVV2 - 24 小时点击排行 Top 10

## Coverage
`index-only`

## Route
- Namespace: `lvv2`
- Namespace Name: `LVV2`
- Route Path: `/lvv2/top/:channel/:sort?`
- Route Name: `24 小时点击排行 Top 10`
- Example: `/lvv2/top/sort-score`
- URL: `lvv2.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
|   热门   |   最新   |    得分    |   24 小时榜   |
| :------: | :------: | :--------: | :-----------: |
| sort-hot | sort-new | sort-score | sort-realtime |

| 排序方式 | 一小时内 | 一天内 | 一个周内 | 一个月内 |
| :------: | :------: | :----: | :------: | :------: |
|          |  t-hour  |  t-day |  t-week  |  t-month |

## Parameters
- `channel`: 频道，见下表
- `sort`: 排序方式，仅得分和24小时榜可选填该参数，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "|   热门   |   最新   |    得分    |   24 小时榜   |\n| :------: | :------: | :--------: | :-----------: |\n| sort-hot | sort-new | sort-score | sort-realtime |\n\n| 排序方式 | 一小时内 | 一天内 | 一个周内 | 一个月内 |\n| :------: | :------: | :----: | :------: | :------: |\n|          |  t-hour  |  t-day |  t-week  |  t-month |",
  "example": "/lvv2/top/sort-score",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "top.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "24 小时点击排行 Top 10",
  "parameters": {
    "channel": "频道，见下表",
    "sort": "排序方式，仅得分和24小时榜可选填该参数，见下表"
  },
  "path": "/top/:channel/:sort?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "lvv2 - 得分 一周内 24小时点击 Top 10 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62540429081283584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lvv2.com/sort-score/t-week",
      "title": "lvv2 - 得分 一周内 24小时点击 Top 10",
      "type": "feed",
      "url": "rsshub://lvv2/top/sort-score"
    },
    {
      "description": "lvv2 - 24小时榜 一天内 24小时点击 Top 10 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129077369739870449",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lvv2.com/sort-realtime/t-day",
      "title": "lvv2 - 24小时榜 一天内 24小时点击 Top 10",
      "type": "feed",
      "url": "rsshub://lvv2/top/sort-realtime/t-day"
    }
  ]
}
```
