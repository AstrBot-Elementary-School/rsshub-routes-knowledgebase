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
  "heat": 98,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "信報網站(www.hkej.com)即時新聞，提供全天候即時港股、香港財經、國際金融和經濟新聞、中國經濟新聞資訊和分析。 - Powered by RSSHub",
      "errorAt": "2026-08-19T05:45:46.853Z",
      "errorMessage": "[GET] \"https://www2.hkej.com/instantnews/stock/article/4487518\": 429 Too Many Requests\n[GET] \"https://www2.hkej.com/instantnews/current/article/4487471\": 429 Too Many Requests\n",
      "id": "69975396806332416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www2.hkej.com/instantnews/",
      "title": "信報網站 - 即時香港中國 國際金融 股市經濟新聞 - 信報網站 hkej.com",
      "type": "feed",
      "url": "rsshub://hkej/index"
    },
    {
      "description": "信報網站(www.hkej.com)即時新聞，提供全天候即時港股、香港財經、國際金融和經濟新聞、中國經濟新聞資訊和分析。 - Powered by RSSHub",
      "errorAt": "2026-08-17T15:32:45.840Z",
      "errorMessage": "[GET] \"https://www2.hkej.com/instantnews/international/article/4487194\": 429 Too Many Requests\n",
      "id": "155622231834300416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www2.hkej.com/instantnews/",
      "title": "信報網站 - 即時香港中國 國際金融 股市經濟新聞 - 信報網站 hkej.com",
      "type": "feed",
      "url": "rsshub://hkej"
    }
  ],
  "url": "hkej.com/"
}
```
