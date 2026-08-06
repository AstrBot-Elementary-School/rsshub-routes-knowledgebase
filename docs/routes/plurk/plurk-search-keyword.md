# Plurk - Search

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/plurk/search/:keyword`
- Route Name: `Search`
- Example: `/plurk/search/FGO`
- URL: `plurk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/plurk/search/FGO",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "search.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Search messages on Plurk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "137882266379326464",
      "image": "https://s.plurk.com/e8266f512246cdbc2721.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.plurk.com/search?q=%E4%B9%A0%E8%BF%91%E5%B9%B3",
      "title": "Search \"习近平\" - Plurk",
      "type": "feed",
      "url": "rsshub://plurk/search/%E4%B9%A0%E8%BF%91%E5%B9%B3"
    },
    {
      "description": "Search messages on Plurk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "119467460684037120",
      "image": "https://s.plurk.com/e8266f512246cdbc2721.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.plurk.com/search?q=%E4%B8%8D%E8%89%AF%E5%9F%B7%E5%BF%B5",
      "title": "Search \"不良執念\" - Plurk",
      "type": "feed",
      "url": "rsshub://plurk/search/%E4%B8%8D%E8%89%AF%E5%9F%B7%E5%BF%B5"
    }
  ]
}
```
