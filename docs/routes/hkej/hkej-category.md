# 信报财经新闻 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `hkej`
- Namespace Name: `信报财经新闻`
- Route Path: `/hkej/:category?`
- Route Name: `即時新聞`
- Example: `/hkej/index`
- URL: `hkej.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| index    | stock    | hongkong | property | china    | international | current  | market   | announcement | hkex       |
| -------- | -------- | -------- | -------- | -------- | ------------- | -------- | -------- | ------------ | ---------- |
| 全部新闻 | 港股直擊 | 香港財經 | 地產新聞 | 中國財經 | 國際財經      | 時事脈搏 | 即巿股評 | 重要通告     | 港交所通告 |

## Parameters
- `category`: 分類，預設為全部新聞


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
  - `www.hkej.com/instantnews/:category`
  - `www.hkej.com/instantnews`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| index    | stock    | hongkong | property | china    | international | current  | market   | announcement | hkex       |\n| -------- | -------- | -------- | -------- | -------- | ------------- | -------- | -------- | ------------ | ---------- |\n| 全部新闻 | 港股直擊 | 香港財經 | 地產新聞 | 中國財經 | 國際財經      | 時事脈搏 | 即巿股評 | 重要通告     | 港交所通告 |",
  "example": "/hkej/index",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 95,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "即時新聞",
  "parameters": {
    "category": "分類，預設為全部新聞"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.hkej.com/instantnews/:category",
        "www.hkej.com/instantnews"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "即時新聞 - 全部 - 信報網站 - 即時香港中國 國際金融 股市經濟新聞 - hkej.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69975396806332416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hkej.com/instantnews",
      "title": "即時新聞 - 全部 - 信報網站 - 即時香港中國 國際金融 股市經濟新聞 - hkej.com",
      "type": "feed",
      "url": "rsshub://hkej/index"
    },
    {
      "description": "即時新聞 - 全部 - 信報網站 - 即時香港中國 國際金融 股市經濟新聞 - hkej.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155622231834300416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hkej.com/instantnews",
      "title": "即時新聞 - 全部 - 信報網站 - 即時香港中國 國際金融 股市經濟新聞 - hkej.com",
      "type": "feed",
      "url": "rsshub://hkej"
    }
  ],
  "url": "hkej.com/"
}
```
