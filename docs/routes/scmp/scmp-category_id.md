# Corona Virus Disease 2019 - News

## Coverage
`index-only`

## Route
- Namespace: `scmp`
- Namespace Name: `Corona Virus Disease 2019`
- Route Path: `/scmp/:category_id`
- Route Name: `News`
- Example: `/scmp/3`
- URL: `scmp.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `proletarius101`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.

## Parameters
- `category_id`: Category


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
  - `scmp.com/rss/:category_id/feed`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.",
  "example": "/scmp/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 173,
  "location": "index.ts",
  "maintainers": [
    "proletarius101"
  ],
  "name": "News",
  "parameters": {
    "category_id": "Category"
  },
  "path": "/:category_id",
  "radar": [
    {
      "source": [
        "scmp.com/rss/:category_id/feed"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "The latest breaking news from China. - Powered by RSSHub",
      "errorAt": "2026-07-20T02:26:53.107Z",
      "errorMessage": "Cannot read properties of undefined (reading 'summary')\n",
      "id": "58381798255721484",
      "image": "https://assets.i-scmp.com/static/img/icons/scmp-meta-1200x630.png",
      "ownerUserId": null,
      "siteUrl": "https://www.scmp.com/rss/4/feed",
      "title": "China - South China Morning Post",
      "type": "feed",
      "url": "rsshub://scmp/4"
    },
    {
      "description": "Breaking news, analysis and opinion from the SCMP's Asia edition. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58381798255721483",
      "image": "https://assets.i-scmp.com/static/img/icons/scmp-meta-1200x630.png",
      "ownerUserId": null,
      "siteUrl": "https://www.scmp.com/rss/3/feed",
      "title": "Asia - South China Morning Post",
      "type": "feed",
      "url": "rsshub://scmp/3"
    }
  ]
}
```
