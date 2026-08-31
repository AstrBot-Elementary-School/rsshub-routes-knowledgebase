# The Economist - Category

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/economist/:endpoint`
- Route Name: `Category`
- Example: `/economist/latest`
- URL: `economist.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `ImSingee`
- Source Location: `full.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `endpoint`: Category name, can be found on the [official page](https://www.economist.com/rss). For example, https://www.economist.com/china/rss.xml to china


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
  - `economist.com/:endpoint`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 918,
  "location": "full.ts",
  "maintainers": [
    "ImSingee"
  ],
  "name": "Category",
  "parameters": {
    "endpoint": "Category name, can be found on the [official page](https://www.economist.com/rss). For example, https://www.economist.com/china/rss.xml to china"
  },
  "path": "/:endpoint",
  "radar": [
    {
      "source": [
        "economist.com/:endpoint"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "The most recent blogs and online articles from The Economist - Powered by RSSHub",
      "errorAt": "2025-09-05T18:15:19.885Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.economist.com/podcasts/2026/08/29/laugh-think-move\": 403 Forbidden\n",
      "id": "54859243036899328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.economist.com/latest",
      "title": "Latest Updates",
      "type": "feed",
      "url": "rsshub://economist/latest"
    },
    {
      "description": "China - Powered by RSSHub",
      "errorAt": "2025-09-05T17:22:28.529Z",
      "errorMessage": "Failed to fetch\n530 \n[GET] \"https://www.economist.com/china/2026/08/17/a-glum-china-pines-for-the-1990s\": 403 Forbidden\n",
      "id": "41461870197170199",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.economist.com/china",
      "title": "China",
      "type": "feed",
      "url": "rsshub://economist/china"
    }
  ],
  "view": 0
}
```
