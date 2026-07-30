# 消费者报道 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `ccreports`
- Namespace Name: `消费者报道`
- Route Path: `/ccreports/article`
- Route Name: `要闻`
- Example: `/ccreports/article`
- URL: `www.ccreports.com.cn/`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `EsuRt, Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.ccreports.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ccreports/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 305,
  "location": "index.ts",
  "maintainers": [
    "EsuRt",
    "Fatpandac"
  ],
  "name": "要闻",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ccreports.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "消费者报道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55939235463397390",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ccreports.com.cn/",
      "title": "消费者报道",
      "type": "feed",
      "url": "rsshub://ccreports/article"
    }
  ],
  "url": "www.ccreports.com.cn/"
}
```
