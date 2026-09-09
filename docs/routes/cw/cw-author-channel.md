# 天下雜誌 - 作者

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/author/:channel`
- Route Name: `作者`
- Example: `/cw/author/57`
- URL: `cw.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 作者 ID，可在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/author/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/author/57",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "作者",
  "parameters": {
    "channel": "作者 ID，可在 URL 中找到"
  },
  "path": "/author/:channel",
  "radar": [
    {
      "source": [
        "cw.com.tw/author/:channel"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "《天下雜誌》是《經濟學人》獨家授權的合作媒體。歡迎搜尋Podcast《經濟學人＠天下》，獲得最新一期《經濟學人》獨家解讀。 - Powered by RSSHub",
      "errorAt": "2026-08-25T03:21:27.144Z",
      "errorMessage": "Target page, context or browser has been closed\nCall log:\n  - waiting for locator('.caption') to be visible\n    - waiting for \"https://www.cw.com.tw/author/57\" navigation to finish...\n    - navigated to \"https://www.cw.com.tw/author/57\"\n\n",
      "id": "69435755254558720",
      "image": "https://cdn-www.cw.com.tw/article/201909/article-5d75f21940867.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/author/57",
      "title": "經濟學人｜最新文章｜天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/author/57"
    }
  ]
}
```
