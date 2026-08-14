# 软餐 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `ruancan`
- Namespace Name: `软餐`
- Route Path: `/ruancan/search/:keyword?`
- Route Name: `搜索`
- Example: `/ruancan/search/Windows`
- URL: `ruancan.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键字


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ruancan.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ruancan/search/Windows",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "keyword": "关键字"
  },
  "path": "/search/:keyword?",
  "radar": [
    {
      "source": [
        "ruancan.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "undefined - 搜索结果 - 软餐 - Powered by RSSHub",
      "errorAt": "2026-08-13T05:03:15.250Z",
      "errorMessage": "Failed to fetch\n",
      "id": "88750451518989312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ruancan.com/?s=undefined",
      "title": "undefined - 搜索结果 - 软餐",
      "type": "feed",
      "url": "rsshub://ruancan/search"
    }
  ],
  "url": "ruancan.com/"
}
```
