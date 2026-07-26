# 天下雜誌 - 最新上線

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/cw/today`
- Route Name: `最新上線`
- Example: `/cw/today`
- URL: `cw.com.tw/today`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/today`
  - `cw.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 38,
  "location": "today.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "最新上線",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "cw.com.tw/today",
        "cw.com.tw/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "天下雜誌每日精選財經、國際、管理、教育、經濟學人、評論、時尚，深入解讀世界脈動。 - Powered by RSSHub",
      "errorAt": "2025-05-25T17:41:59.652Z",
      "errorMessage": "route.continue: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: page.goto: Target page, context or browser has been closed\n",
      "id": "60230426333120512",
      "image": "https://www.cw.com.tw/assets_new/img/fbshare.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.cw.com.tw/today",
      "title": "今日最新－天下雜誌",
      "type": "feed",
      "url": "rsshub://cw/today"
    }
  ],
  "url": "cw.com.tw/today"
}
```
