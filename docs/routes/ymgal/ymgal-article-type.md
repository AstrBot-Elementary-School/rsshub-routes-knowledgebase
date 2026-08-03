# 月幕 Galgame - 文章

## Coverage
`index-only`

## Route
- Namespace: `ymgal`
- Namespace Name: `月幕 Galgame`
- Route Path: `/ymgal/article/:type?`
- Route Name: `文章`
- Example: `/ymgal/article`
- URL: `ymgal.games`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SunBK201`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 全部文章 | 资讯 | 专栏   |
| -------- | ---- | ------ |
| all      | news | column |

## Parameters
- `type`: 文章类型


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
    "anime"
  ],
  "description": "| 全部文章 | 资讯 | 专栏   |\n| -------- | ---- | ------ |\n| all      | news | column |",
  "example": "/ymgal/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 169,
  "location": "article.ts",
  "maintainers": [
    "SunBK201"
  ],
  "name": "文章",
  "parameters": {
    "type": "文章类型"
  },
  "path": "/article/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "月幕 Galgame - 全部文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41467081627747332",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ymgal.games/co/article",
      "title": "月幕 Galgame - 全部文章",
      "type": "feed",
      "url": "rsshub://ymgal/article"
    },
    {
      "description": "月幕 Galgame - 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63378738853540864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ymgal.games/co/article",
      "title": "月幕 Galgame - 资讯",
      "type": "feed",
      "url": "rsshub://ymgal/article/news"
    }
  ]
}
```
