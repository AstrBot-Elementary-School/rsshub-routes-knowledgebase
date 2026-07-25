# 乳首ふぇち - Category

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/chikubi/category/:keyword`
- Route Name: `Category`
- Example: `/chikubi/category/nipple-lesbian`
- URL: `chikubi.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Category`
- `source`:
  - `chikubi.jp/category/:keyword`
- `target`: `/category/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/category/nipple-lesbian",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 43,
  "location": "category.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Category",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/category/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/category/:keyword"
      ],
      "target": "/category/:keyword",
      "title": "Category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Category: 乳首レズ - chikubi.jp - Powered by RSSHub",
      "errorAt": "2026-07-24T06:58:50.220Z",
      "errorMessage": "Unexpected token '<', \"<!DOCTYPE \"... is not valid JSON\n",
      "id": "61928846657635328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chikubi.jp/category/nipple-lesbian",
      "title": "Category: 乳首レズ - chikubi.jp",
      "type": "feed",
      "url": "rsshub://chikubi/category/nipple-lesbian"
    },
    {
      "description": "Category: 管理人オススメ - chikubi.jp - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "119079828973887488",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chikubi.jp/category/recommend-of-webmaster",
      "title": "Category: 管理人オススメ - chikubi.jp",
      "type": "feed",
      "url": "rsshub://chikubi/category/recommend-of-webmaster"
    }
  ]
}
```
