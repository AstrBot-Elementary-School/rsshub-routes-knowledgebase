# 华尔街见闻 - 最热文章

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/wallstreetcn/hot/:period?`
- Route Name: `最热文章`
- Example: `/wallstreetcn/hot`
- URL: `wallstreetcn.com/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `period`: 时期，可选 `day` 即 当日 或 `week` 即 当周，默认为当日


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
  - `wallstreetcn.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/wallstreetcn/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1156,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "最热文章",
  "parameters": {
    "period": "时期，可选 `day` 即 当日 或 `week` 即 当周，默认为当日"
  },
  "path": "/hot/:period?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "华尔街见闻 - 最热文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58447406078338048",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/",
      "title": "华尔街见闻 - 最热文章",
      "type": "feed",
      "url": "rsshub://wallstreetcn/hot"
    },
    {
      "description": "华尔街见闻 - 最热文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79704903500190720",
      "image": "https://static.wscn.net/wscn/_static/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://wallstreetcn.com/",
      "title": "华尔街见闻 - 最热文章",
      "type": "feed",
      "url": "rsshub://wallstreetcn/hot/day"
    }
  ],
  "url": "wallstreetcn.com/"
}
```
