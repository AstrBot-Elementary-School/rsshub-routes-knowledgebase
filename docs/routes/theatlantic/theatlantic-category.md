# The Atlantic - News

## Coverage
`index-only`

## Route
- Namespace: `theatlantic`
- Namespace Name: `The Atlantic`
- Route Path: `/theatlantic/:category`
- Route Name: `News`
- Example: `/theatlantic/latest`
- URL: `www.theatlantic.com`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `EthanWng97, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Popular      | Latest | Politics | Technology | Business |
| ------------ | ------ | -------- | ---------- | -------- |
| most-popular | latest | politics | technology | business |

More categories (except photo) can be found within the navigation bar at <https://www.theatlantic.com>

## Parameters
- `category`: category, see below


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
  - `www.theatlantic.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "| Popular      | Latest | Politics | Technology | Business |\n| ------------ | ------ | -------- | ---------- | -------- |\n| most-popular | latest | politics | technology | business |\n\nMore categories (except photo) can be found within the navigation bar at <https://www.theatlantic.com>",
  "example": "/theatlantic/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1390,
  "location": "news.ts",
  "maintainers": [
    "EthanWng97",
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {
    "category": "category, see below"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.theatlantic.com/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The Atlantic - LATEST - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61228164717836288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theatlantic.com/latest/",
      "title": "The Atlantic - LATEST",
      "type": "feed",
      "url": "rsshub://theatlantic/latest"
    },
    {
      "description": "The Atlantic - TECHNOLOGY - Powered by RSSHub",
      "errorAt": "2025-06-11T19:44:17.689Z",
      "errorMessage": "Cannot read properties of undefined (reading 'data')\nCannot read properties of undefined (reading 'data')\n",
      "id": "62408054287669248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.theatlantic.com/technology/",
      "title": "The Atlantic - TECHNOLOGY",
      "type": "feed",
      "url": "rsshub://theatlantic/technology"
    }
  ]
}
```
