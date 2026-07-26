# Google - News

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/news/:category/:locale`
- Route Name: `News`
- Example: `/google/news/Top stories/hl=en-US&gl=US&ceid=US:en`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `zoenglinghou, pseudoyu`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category Title
- `locale`: locales, could be found behind `?`, including `hl`, `gl`, and `ceid` as parameters


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
    "new-media"
  ],
  "example": "/google/news/Top stories/hl=en-US&gl=US&ceid=US:en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 22,
  "location": "news.tsx",
  "maintainers": [
    "zoenglinghou",
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {
    "category": "Category Title",
    "locale": "locales, could be found behind `?`, including `hl`, `gl`, and `ceid` as parameters"
  },
  "path": "/news/:category/:locale",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Google News - Headlines - Powered by RSSHub",
      "errorAt": "2024-11-02T18:50:31.393Z",
      "errorMessage": "200 ",
      "id": "66057583919692800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.google.com/topics/CAAqJggKIiBDQkFTRWdvSUwyMHZNRFZxYUdjU0FtVnVHZ0pWVXlnQVAB?hl=en-US&gl=US&ceid=US%3Aen",
      "title": "Google News - Headlines",
      "type": "feed",
      "url": "rsshub://google/news/Top%20stories/hl=en-US&gl=US&ceid=US:en"
    },
    {
      "description": null,
      "errorAt": "2025-09-19T00:56:30.820Z",
      "errorMessage": "200 ",
      "id": "191666157347082243",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://google/news/%E7%84%A6%E7%82%B9%E6%96%B0%E9%97%BB/hl=zh-CN&gl=CN&ceid=CN:zh-Hans"
    }
  ]
}
```
