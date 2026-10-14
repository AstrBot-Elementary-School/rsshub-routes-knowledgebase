# 少女前线 - 情报局

## Coverage
`index-only`

## Route
- Namespace: `gf-cn`
- Namespace Name: `少女前线`
- Route Path: `/gf-cn/news/:category?`
- Route Name: `情报局`
- Example: `/gf-cn/news`
- URL: `gf-cn.sunborngame.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 新闻 | 公告 |
| ---- | ---- |
| 1    | 3    |

## Parameters
- `category`: 分类，见下表，默认为新闻


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
  - `gf-cn.sunborngame.com/News`
  - `gf-cn.sunborngame.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻 | 公告 |\n| ---- | ---- |\n| 1    | 3    |",
  "example": "/gf-cn/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "情报局",
  "parameters": {
    "category": "分类，见下表，默认为新闻"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "gf-cn.sunborngame.com/News",
        "gf-cn.sunborngame.com/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新闻 - 少女前线 - 情报局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74302230794164224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gf-cn.sunborngame.com/News",
      "title": "新闻 - 少女前线 - 情报局",
      "type": "feed",
      "url": "rsshub://gf-cn/news"
    }
  ]
}
```
