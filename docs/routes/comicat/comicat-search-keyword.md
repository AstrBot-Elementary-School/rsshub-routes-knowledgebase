# Comicat - 搜索关键词

## Coverage
`index-only`

## Route
- Namespace: `comicat`
- Namespace Name: `Comicat`
- Route Path: `/comicat/search/:keyword`
- Route Name: `搜索关键词`
- Example: `/comicat/search/喵萌奶茶屋+跃动青春+720P+简日`
- URL: `comicat.org`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Cyang39`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，请用`+`号连接


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
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
  "example": "/comicat/search/喵萌奶茶屋+跃动青春+720P+简日",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "Cyang39"
  ],
  "name": "搜索关键词",
  "parameters": {
    "keyword": "关键词，请用`+`号连接"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Comicat - 无职转生 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "191615269219045376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://comicat.org/search.php?keyword=%E6%97%A0%E8%81%8C%E8%BD%AC%E7%94%9F",
      "title": "Comicat - 无职转生",
      "type": "feed",
      "url": "rsshub://comicat/search/%E6%97%A0%E8%81%8C%E8%BD%AC%E7%94%9F"
    }
  ]
}
```
