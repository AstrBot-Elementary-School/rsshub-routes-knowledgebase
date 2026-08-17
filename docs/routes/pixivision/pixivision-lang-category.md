# pixivision - Category

## Coverage
`index-only`

## Route
- Namespace: `pixivision`
- Namespace Name: `pixivision`
- Route Path: `/pixivision/:lang/:category?`
- Route Name: `Category`
- Example: `/pixivision/zh-tw`
- URL: `www.pixivision.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
`https://www.pixivision.net/zh-tw/c/interview` → `/pixivision/zh-tw/interview`
:::

## Parameters
- `lang`: Language
- `category`: Category


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
  - `www.pixivision.net/:lang`
- `target`: `/:lang`
### Rule 2
- `source`:
  - `www.pixivision.net/:lang/c/:category`
- `target`: `/:lang/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n`https://www.pixivision.net/zh-tw/c/interview` → `/pixivision/zh-tw/interview`\n:::",
  "example": "/pixivision/zh-tw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 313,
  "location": "index.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category",
    "lang": "Language"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "www.pixivision.net/:lang"
      ],
      "target": "/:lang"
    },
    {
      "source": [
        "www.pixivision.net/:lang/c/:category"
      ],
      "target": "/:lang/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "New - pixivision - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58887079850550272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixivision.net/zh-tw",
      "title": "New - pixivision",
      "type": "feed",
      "url": "rsshub://pixivision/zh-tw"
    },
    {
      "description": "New - pixivision - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72857212239056896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixivision.net/zh",
      "title": "New - pixivision",
      "type": "feed",
      "url": "rsshub://pixivision/zh"
    }
  ],
  "view": 0
}
```
