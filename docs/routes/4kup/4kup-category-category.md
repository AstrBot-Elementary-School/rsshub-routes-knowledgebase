# 4KUP - Category

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/4kup/category/:category`
- Route Name: `Category`
- Example: `/4kup/category/coser`
- URL: `4kup.net/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category


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
- `source`:
  - `4kup.net/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/category/coser",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 567,
  "location": "category.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "4kup.net/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "4KUP - Category: coser - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "106512243168497664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/category/coser/",
      "title": "4KUP - Category: coser",
      "type": "feed",
      "url": "rsshub://4kup/category/coser"
    },
    {
      "description": "4KUP - Category: korean - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "109198226159069184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://4kup.net/category/korean/",
      "title": "4KUP - Category: korean",
      "type": "feed",
      "url": "rsshub://4kup/category/korean"
    }
  ],
  "url": "4kup.net/"
}
```
