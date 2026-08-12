# EA Games - APEX Legends 官网资讯

## Coverage
`index-only`

## Route
- Namespace: `ea`
- Namespace Name: `EA Games`
- Route Path: `/ea/apex-news/:lang?/:type?`
- Route Name: `APEX Legends 官网资讯`
- Example: `/ea/apex-news/zh-hant/game-updates`
- URL: `www.ea.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `IceChestnut`
- Source Location: `apex-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "语言", "options": [{"label": "中文(繁体)", "value": "zh-hant"}, {"label": "English", "value": "en"}]}
- `type`: {"default": "latest", "description": "资讯类型（可选）", "options": [{"label": "最新消息", "value": "news-article"}, {"label": "游戏更新", "value": "game-updates"}, {"label": "全部", "value": "latest"}]}


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
    "game"
  ],
  "example": "/ea/apex-news/zh-hant/game-updates",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "apex-news.ts",
  "maintainers": [
    "IceChestnut"
  ],
  "name": "APEX Legends 官网资讯",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "语言",
      "options": [
        {
          "label": "中文(繁体)",
          "value": "zh-hant"
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    },
    "type": {
      "default": "latest",
      "description": "资讯类型（可选）",
      "options": [
        {
          "label": "最新消息",
          "value": "news-article"
        },
        {
          "label": "游戏更新",
          "value": "game-updates"
        },
        {
          "label": "全部",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/apex-news/:lang?/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Apex Legends 官网资讯（最新消息） - Powered by RSSHub",
      "errorAt": "2025-10-02T17:55:45.883Z",
      "errorMessage": "Cannot read properties of undefined (reading 'featured')\n",
      "id": "143374026862942208",
      "image": "https://drop-assets.ea.com/images/F1GeiHWipvvKj7GtUVP3U/31bb122451e2dea6d14c9b497f8e09d4/apex-white-nav-logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.ea.com/zh-hant/games/apex-legends/apex-legends/news?type=news-article",
      "title": "Apex Legends 官网资讯（最新消息）",
      "type": "feed",
      "url": "rsshub://ea/apex-news/zh-hant/news-article"
    },
    {
      "description": "Apex Legends 官网资讯（游戏更新） - Powered by RSSHub",
      "errorAt": "2025-10-02T19:48:59.917Z",
      "errorMessage": "Cannot read properties of undefined (reading 'featured')\n",
      "id": "143373614588382208",
      "image": "https://drop-assets.ea.com/images/F1GeiHWipvvKj7GtUVP3U/31bb122451e2dea6d14c9b497f8e09d4/apex-white-nav-logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.ea.com/zh-hant/games/apex-legends/apex-legends/news?type=game-updates",
      "title": "Apex Legends 官网资讯（游戏更新）",
      "type": "feed",
      "url": "rsshub://ea/apex-news/zh-hant/game-updates"
    }
  ],
  "view": 0
}
```
