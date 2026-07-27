# 東立出版社 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `tongli`
- Namespace Name: `東立出版社`
- Route Path: `/tongli/news/:type`
- Route Name: `新聞`
- Example: `/tongli/news/6`
- URL: `tongli.com.tw`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `CokeMine`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 分類，可以在“新聞”鏈接中找到


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
    "reading"
  ],
  "example": "/tongli/news/6",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "CokeMine"
  ],
  "name": "新聞",
  "parameters": {
    "type": "分類，可以在“新聞”鏈接中找到"
  },
  "path": "/news/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "T-NEWS首頁 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78620198692811776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "T-NEWS首頁",
      "type": "feed",
      "url": "rsshub://tongli/news/6"
    }
  ]
}
```
