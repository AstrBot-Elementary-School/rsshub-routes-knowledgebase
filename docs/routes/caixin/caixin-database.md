# 财新网 - 财新数据通

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新网`
- Route Path: `/caixin/database`
- Route Name: `财新数据通`
- Example: `/caixin/database`
- URL: `database.caixin.com/news/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `database.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `database.caixin.com/news/`
  - `database.caixin.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/caixin/database",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "database.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "财新数据通",
  "parameters": {},
  "path": "/database",
  "radar": [
    {
      "source": [
        "database.caixin.com/news/",
        "database.caixin.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "财新数据通 - 专享资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59040048063587328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://database.caixin.com/news/",
      "title": "财新数据通 - 专享资讯",
      "type": "feed",
      "url": "rsshub://caixin/database"
    }
  ],
  "url": "database.caixin.com/news/"
}
```
