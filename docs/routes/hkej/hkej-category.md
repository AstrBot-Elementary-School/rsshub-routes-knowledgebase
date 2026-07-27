# 信报财经新闻 - 即时新闻

## Coverage
`index-only`

## Route
- Namespace: `hkej`
- Namespace Name: `信报财经新闻`
- Route Path: `/hkej/:category?`
- Route Name: `即时新闻`
- Example: `/hkej/index`
- URL: `hkej.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| index    | stock    | hongkong | china    | international | property | current  |
| -------- | -------- | -------- | -------- | ------------- | -------- | -------- |
| 全部新闻 | 港股直击 | 香港财经 | 中国财经 | 国际财经      | 地产新闻 | 时事脉搏 |

## Parameters
- `category`: 分类，默认为全部新闻


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
  - `hkej.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| index    | stock    | hongkong | china    | international | property | current  |\n| -------- | -------- | -------- | -------- | ------------- | -------- | -------- |\n| 全部新闻 | 港股直击 | 香港财经 | 中国财经 | 国际财经      | 地产新闻 | 时事脉搏 |",
  "example": "/hkej/index",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 93,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "即时新闻",
  "parameters": {
    "category": "分类，默认为全部新闻"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "hkej.com/"
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
      "errorAt": null,
      "errorMessage": null,
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
      "errorAt": null,
      "errorMessage": null,
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
