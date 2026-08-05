# iThome 台灣 - 热榜

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ithome/ranking/:type`
- Route Name: `热榜`
- Example: `/ithome/ranking/24h`
- URL: `ithome.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `immmortal, luyuhuang`
- Source Location: `ranking.ts`
- Source Module: `_None_`

## Description
| 24h           | 7days    | monthly |
| ------------- | -------- | ------- |
| 24 小时阅读榜 | 7 天最热 | 月榜    |

## Parameters
- `type`: 类别


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
    "new-media"
  ],
  "description": "| 24h           | 7days    | monthly |\n| ------------- | -------- | ------- |\n| 24 小时阅读榜 | 7 天最热 | 月榜    |",
  "example": "/ithome/ranking/24h",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1214,
  "location": "ranking.ts",
  "maintainers": [
    "immmortal",
    "luyuhuang"
  ],
  "name": "热榜",
  "parameters": {
    "type": "类别"
  },
  "path": "/ranking/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "IT之家-24 小时最热 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905679",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/",
      "title": "IT之家-24 小时最热",
      "type": "feed",
      "url": "rsshub://ithome/ranking/24h"
    },
    {
      "description": "IT之家-7 天最热 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com/",
      "title": "IT之家-7 天最热",
      "type": "feed",
      "url": "rsshub://ithome/ranking/7days"
    }
  ]
}
```
