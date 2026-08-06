# AIbase - 资讯

## Coverage
`index-only`

## Route
- Namespace: `aibase`
- Namespace Name: `AIbase`
- Route Path: `/aibase/news`
- Route Name: `资讯`
- Example: `/aibase/news`
- URL: `www.aibase.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `zreo0`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
获取 AI 资讯列表

## Parameters
_None_


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
  - `www.aibase.com/zh/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "description": "获取 AI 资讯列表",
  "example": "/aibase/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1940,
  "location": "news.ts",
  "maintainers": [
    "zreo0"
  ],
  "name": "资讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.aibase.com/zh/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "AI新闻资讯 - 不错过全球AI革新的每一个时刻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69533603812632576",
      "image": "https://top.aibase.com/_static/img/Frame@2x.eddfa3e.png",
      "ownerUserId": null,
      "siteUrl": "https://www.aibase.com/zh/news",
      "title": "AI新闻资讯",
      "type": "feed",
      "url": "rsshub://aibase/news"
    }
  ],
  "url": "www.aibase.com"
}
```
