# TheBlock - Category

## Coverage
`index-only`

## Route
- Namespace: `theblock`
- Namespace Name: `TheBlock`
- Route Path: `/theblock/category/:category`
- Route Name: `Category`
- Example: `/theblock/category/crypto-ecosystems`
- URL: `theblock.co`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Get latest news from TheBlock by category. Note that due to website limitations, only article summaries may be available.

## Parameters
- `category`: News category


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
  - `theblock.co/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from TheBlock by category. Note that due to website limitations, only article summaries may be available.",
  "example": "/theblock/category/crypto-ecosystems",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "index.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Category",
  "parameters": {
    "category": "News category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "theblock.co/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Latest articles from TheBlock in the markets category - Powered by RSSHub",
      "errorAt": "2026-05-27T10:15:45.019Z",
      "errorMessage": "Failed to fetch\n",
      "id": "185526378093555743",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theblock.co/category/markets",
      "title": "TheBlock - Markets",
      "type": "feed",
      "url": "rsshub://theblock/category/markets"
    },
    {
      "description": "Latest articles from TheBlock in the crypto-ecosystems category - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "124086111503666176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theblock.co/category/crypto-ecosystems",
      "title": "TheBlock - Crypto ecosystems",
      "type": "feed",
      "url": "rsshub://theblock/category/crypto-ecosystems"
    }
  ]
}
```
