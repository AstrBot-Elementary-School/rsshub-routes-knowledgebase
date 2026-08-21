# indienova 独立游戏 - 文章

## Coverage
`index-only`

## Route
- Namespace: `indienova`
- Namespace Name: `indienova 独立游戏`
- Route Path: `/indienova/:type`
- Route Name: `文章`
- Example: `/indienova/article`
- URL: `indienova.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `GensouSakuya, kt286`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 类型: `article` 文章，`development` 开发


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
  "example": "/indienova/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 310,
  "location": "article.ts",
  "maintainers": [
    "GensouSakuya",
    "kt286"
  ],
  "name": "文章",
  "parameters": {
    "type": "类型: `article` 文章，`development` 开发"
  },
  "path": "/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "独立游戏资讯 | indienova 独立游戏 - Powered by RSSHub",
      "errorAt": "2026-08-19T08:36:18.828Z",
      "errorMessage": "[GET] \"https://indienova.com/indie-game-news/\": <no response> fetch failed (Connect Timeout Error (attempted address: indienova.com:443, timeout: 10000ms))\n[GET] \"https://indienova.com/indie-game-review/doloc-town-review/\": <no response> fetch failed (Connect Timeout Error (attempted address: indienova.com:443, timeout: 10000ms))\n530 \n[GET] \"https://indienova.com/indie-game-news/\": <no response> fetch failed (Connect Timeout Error (attempted address: indienova.com:443, timeout: 10000ms))\n",
      "id": "55619197325901824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://indienova.com/indie-game-news/",
      "title": "独立游戏资讯 | indienova 独立游戏",
      "type": "feed",
      "url": "rsshub://indienova/article"
    },
    {
      "description": "独立游戏资讯 | indienova 独立游戏 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63456671097359360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://indienova.com/indie-game-development/",
      "title": "独立游戏开发 | indienova 独立游戏",
      "type": "feed",
      "url": "rsshub://indienova/development"
    }
  ]
}
```
