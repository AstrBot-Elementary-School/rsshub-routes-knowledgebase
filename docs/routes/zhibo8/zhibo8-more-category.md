# 直播吧 - 滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `zhibo8`
- Namespace Name: `直播吧`
- Route Path: `/zhibo8/more/:category?`
- Route Name: `滚动新闻`
- Example: `/zhibo8/more/nba`
- URL: `zhibo8.cc`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `more.ts`
- Source Module: `_None_`

## Description
| NBA | 足球  | 电竞     | 综合   |
| --- | ----- | -------- | ------ |
| nba | zuqiu | dianjing | zonghe |

## Parameters
- `category`: 分类，见下表，默认为 NBA


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
  - `news.zhibo8.cc/:category`
- `target`: `/more/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| NBA | 足球  | 电竞     | 综合   |\n| --- | ----- | -------- | ------ |\n| nba | zuqiu | dianjing | zonghe |",
  "example": "/zhibo8/more/nba",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 228,
  "location": "more.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "滚动新闻",
  "parameters": {
    "category": "分类，见下表，默认为 NBA"
  },
  "path": "/more/:category?",
  "radar": [
    {
      "source": [
        "news.zhibo8.cc/:category"
      ],
      "target": "/more/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "足球 - 直播吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61588318218478611",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.zhibo8.cc/zuqiu/more.htm",
      "title": "足球 - 直播吧",
      "type": "feed",
      "url": "rsshub://zhibo8/more/zuqiu"
    },
    {
      "description": "NBA - 直播吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63118600077338626",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.zhibo8.cc/nba/more.htm",
      "title": "NBA - 直播吧",
      "type": "feed",
      "url": "rsshub://zhibo8/more/nba"
    }
  ]
}
```
