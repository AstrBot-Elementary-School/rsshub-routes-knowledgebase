# pixiv - Keyword

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/search/:keyword/:order?/:mode?/:include_ai?`
- Route Name: `Keyword`
- Example: `/pixiv/search/Nezuko/popular`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: keyword
- `order`: {"default": "date", "description": "rank mode, empty or other for time order, popular for popular order", "options": [{"label": "time order", "value": "date"}, {"label": "popular order", "value": "popular"}]}
- `mode`: {"default": "no", "description": "filte R18 content", "options": [{"label": "only not R18", "value": "safe"}, {"label": "only R18", "value": "r18"}, {"label": "no filter", "value": "no"}]}
- `include_ai`: {"default": "yes", "description": "whether AI-generated content is included", "options": [{"label": "does not include AI-generated content", "value": "no"}, {"label": "include AI-generated content", "value": "yes"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/pixiv/search/Nezuko/popular",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1973,
  "location": "search.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Keyword",
  "parameters": {
    "include_ai": {
      "default": "yes",
      "description": "whether AI-generated content is included",
      "options": [
        {
          "label": "does not include AI-generated content",
          "value": "no"
        },
        {
          "label": "include AI-generated content",
          "value": "yes"
        }
      ]
    },
    "keyword": "keyword",
    "mode": {
      "default": "no",
      "description": "filte R18 content",
      "options": [
        {
          "label": "only not R18",
          "value": "safe"
        },
        {
          "label": "only R18",
          "value": "r18"
        },
        {
          "label": "no filter",
          "value": "no"
        }
      ]
    },
    "order": {
      "default": "date",
      "description": "rank mode, empty or other for time order, popular for popular order",
      "options": [
        {
          "label": "time order",
          "value": "date"
        },
        {
          "label": "popular order",
          "value": "popular"
        }
      ]
    }
  },
  "path": "/search/:keyword/:order?/:mode?/:include_ai?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Palworld 的 pixiv 热门内容 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805276726320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/tags/Palworld/artworks",
      "title": "Palworld 的 pixiv 热门内容",
      "type": "feed",
      "url": "rsshub://pixiv/search/Palworld/popular"
    },
    {
      "description": "ELDENRING 的 pixiv 热门内容 - Powered by RSSHub",
      "errorAt": "2026-08-30T16:50:25.520Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n",
      "id": "41147805276726316",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/tags/ELDENRING/artworks",
      "title": "ELDENRING 的 pixiv 热门内容",
      "type": "feed",
      "url": "rsshub://pixiv/search/ELDENRING/popular"
    }
  ],
  "view": 2
}
```
