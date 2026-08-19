# 円谷ステーション - ニュース

## Coverage
`index-only`

## Route
- Namespace: `m-78`
- Namespace Name: `円谷ステーション`
- Route Path: `/m-78/news/:category?`
- Route Name: `ニュース`
- Example: `/m-78/news`
- URL: `m-78.jp`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `KarasuShin`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "news", "description": "news category", "options": [{"label": "ニュース", "value": "news"}, {"label": "動画配信", "value": "streaming"}, {"label": "イベント", "value": "event"}, {"label": "放送", "value": "onair"}, {"label": "放送/配信", "value": "broadcast"}, {"label": "グッズ", "value": "goods"}, {"label": "ウルトラマン カードゲーム", "value": "ultraman-cardgame"}, {"label": "ショップ", "value": "shop"}, {"label": "Blu-ray・DVD", "value": "blu-ray_dvd"}, {"label": "デジタル", "value": "digital"}]}


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `m-78.jp/news`
- `target`: `/news`
### Rule 2
- `source`:
  - `m-78.jp/news/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/m-78/news",
  "features": {
    "supportRadar": true
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "ニュース",
  "parameters": {
    "category": {
      "default": "news",
      "description": "news category",
      "options": [
        {
          "label": "ニュース",
          "value": "news"
        },
        {
          "label": "動画配信",
          "value": "streaming"
        },
        {
          "label": "イベント",
          "value": "event"
        },
        {
          "label": "放送",
          "value": "onair"
        },
        {
          "label": "放送/配信",
          "value": "broadcast"
        },
        {
          "label": "グッズ",
          "value": "goods"
        },
        {
          "label": "ウルトラマン カードゲーム",
          "value": "ultraman-cardgame"
        },
        {
          "label": "ショップ",
          "value": "shop"
        },
        {
          "label": "Blu-ray・DVD",
          "value": "blu-ray_dvd"
        },
        {
          "label": "デジタル",
          "value": "digital"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "m-78.jp/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "m-78.jp/news/category/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "ニュース | ニュース - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82624813968150528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m-78.jp/news/category/news/",
      "title": "ニュース | ニュース",
      "type": "feed",
      "url": "rsshub://m-78/news"
    },
    {
      "description": "ニュース | ニュース - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1142847584033701888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m-78.jp/news/category/news/",
      "title": "ニュース | ニュース",
      "type": "feed",
      "url": "rsshub://m-78/news/news"
    }
  ],
  "view": 0
}
```
