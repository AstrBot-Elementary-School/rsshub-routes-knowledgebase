# Anime1 - Anime

## Coverage
`index-only`

## Route
- Namespace: `anime1`
- Namespace Name: `Anime1`
- Route Path: `/anime1/anime/:category/:name`
- Route Name: `Anime`
- Example: `/anime1/anime/2024年夏季/神之塔-第二季`
- URL: `anime1.me`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `cxheng315`
- Source Location: `anime.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Anime1 Category
- `name`: Anime1 Name


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
  - `anime1.me/category/:category/:name`
- `target`: `/anime/:category/:name`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/anime1/anime/2024年夏季/神之塔-第二季",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "anime.ts",
  "maintainers": [
    "cxheng315"
  ],
  "name": "Anime",
  "parameters": {
    "category": "Anime1 Category",
    "name": "Anime1 Name"
  },
  "path": "/anime/:category/:name",
  "radar": [
    {
      "source": [
        "anime1.me/category/:category/:name"
      ],
      "target": "/anime/:category/:name"
    }
  ],
  "topFeeds": [
    {
      "description": "Re:從零開始的異世界生活 第三季 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65060176396811264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://anime1.me/category/2024%E5%B9%B4%E7%A7%8B%E5%AD%A3/re%E5%BE%9E%E9%9B%B6%E9%96%8B%E5%A7%8B%E7%9A%84%E7%95%B0%E4%B8%96%E7%95%8C%E7%94%9F%E6%B4%BB-%E7%AC%AC%E4%B8%89%E5%AD%A3",
      "title": "Re:從零開始的異世界生活 第三季",
      "type": "feed",
      "url": "rsshub://anime1/anime/2024%E5%B9%B4%E7%A7%8B%E5%AD%A3/re%E5%BE%9E%E9%9B%B6%E9%96%8B%E5%A7%8B%E7%9A%84%E7%95%B0%E4%B8%96%E7%95%8C%E7%94%9F%E6%B4%BB-%E7%AC%AC%E4%B8%89%E5%AD%A3"
    },
    {
      "description": "神之塔 第二季 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60966614188225536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://anime1.me/category/2024%E5%B9%B4%E5%A4%8F%E5%AD%A3/%E7%A5%9E%E4%B9%8B%E5%A1%94-%E7%AC%AC%E4%BA%8C%E5%AD%A3",
      "title": "神之塔 第二季",
      "type": "feed",
      "url": "rsshub://anime1/anime/2024%E5%B9%B4%E5%A4%8F%E5%AD%A3/%E7%A5%9E%E4%B9%8B%E5%A1%94-%E7%AC%AC%E4%BA%8C%E5%AD%A3"
    }
  ],
  "url": "anime1.me"
}
```
