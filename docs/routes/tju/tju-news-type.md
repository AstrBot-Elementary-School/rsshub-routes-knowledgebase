# Tianjin University 天津大学 - News

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/tju/news/:type?`
- Route Name: `News`
- Example: `/tju/news/focus`
- URL: `cic.tju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AlanZeng423, SuperPung`
- Source Location: `news/index.ts`
- Source Module: `_None_`

## Description
| Focus on TJU | General News | Internal News | Media Report | Pictures of TJU |
| :----------: | :----------: | :-----------: | :----------: | :-------------: |
|     focus    |    general   |    internal   |     media    |     picture     |

## Parameters
- `type`: default `focus`


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
    "university"
  ],
  "description": "| Focus on TJU | General News | Internal News | Media Report | Pictures of TJU |\n| :----------: | :----------: | :-----------: | :----------: | :-------------: |\n|     focus    |    general   |    internal   |     media    |     picture     |",
  "example": "/tju/news/focus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news/index.ts",
  "maintainers": [
    "AlanZeng423",
    "SuperPung"
  ],
  "name": "News",
  "parameters": {
    "type": "default `focus`"
  },
  "path": "/news/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "链接失效http://news.tju.edu.cn/jjtd.htm - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "126468536462736405",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://news.tju.edu.cn/jjtd.htm",
      "title": "天津大学新闻网 - 聚焦天大",
      "type": "feed",
      "url": "rsshub://tju/news/focus"
    }
  ]
}
```
