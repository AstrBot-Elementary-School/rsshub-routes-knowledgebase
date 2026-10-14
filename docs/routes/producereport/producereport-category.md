# Produce Report - Category

## Coverage
`index-only`

## Route
- Namespace: `producereport`
- Namespace Name: `Produce Report`
- Route Path: `/producereport/:category{.+}?`
- Route Name: `Category`
- Example: `/producereport/produce/fresh-fruits/apples`
- URL: `www.producereport.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Apples](https://www.producereport.com/produce/fresh-fruits/apples), where the source URL is `https://www.producereport.com/produce/fresh-fruits/apples`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/producereport/produce/fresh-fruits/apples`](https://rsshub.app/producereport/produce/fresh-fruits/apples).
:::

## Parameters
- `category`: {"description": "Category, `Fresh Fruits - Apple` by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.producereport.com/*category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Apples](https://www.producereport.com/produce/fresh-fruits/apples), where the source URL is `https://www.producereport.com/produce/fresh-fruits/apples`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/producereport/produce/fresh-fruits/apples`](https://rsshub.app/producereport/produce/fresh-fruits/apples).\n:::",
  "example": "/producereport/produce/fresh-fruits/apples",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": {
      "description": "Category, `Fresh Fruits - Apple` by default"
    }
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.producereport.com/*category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.producereport.com",
  "view": 0
}
```
