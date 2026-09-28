# 人人都是产品经理 - 热门文章

## Coverage
`index-only`

## Route
- Namespace: `woshipm`
- Namespace Name: `人人都是产品经理`
- Route Path: `/woshipm/popular/:range?`
- Route Name: `热门文章`
- Example: `/woshipm/popular`
- URL: `woshipm.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `WenryXu`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
| 日榜  | 周榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `range`: 时间，见下表，默认为 `daily`


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
  - `woshipm.com/`
- `target`: `/popular`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 日榜  | 周榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/woshipm/popular",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 794,
  "location": "popular.ts",
  "maintainers": [
    "WenryXu"
  ],
  "name": "热门文章",
  "parameters": {
    "range": "时间，见下表，默认为 `daily`"
  },
  "path": "/popular/:range?",
  "radar": [
    {
      "source": [
        "woshipm.com/"
      ],
      "target": "/popular"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "热门文章 - 日榜 - 人人都是产品经理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41843691623908352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.woshipm.com/",
      "title": "热门文章 - 日榜 - 人人都是产品经理",
      "type": "feed",
      "url": "rsshub://woshipm/popular"
    },
    {
      "description": "热门文章 - 周榜 - 人人都是产品经理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62029871009936384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.woshipm.com/",
      "title": "热门文章 - 周榜 - 人人都是产品经理",
      "type": "feed",
      "url": "rsshub://woshipm/popular/weekly"
    }
  ],
  "url": "woshipm.com/"
}
```
