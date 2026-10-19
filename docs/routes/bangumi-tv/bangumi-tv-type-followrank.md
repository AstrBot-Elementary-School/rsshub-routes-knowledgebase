# Bangumi 番组计划 - 成员关注榜

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/:type/followrank`
- Route Name: `成员关注榜`
- Example: `/bangumi.tv/anime/followrank`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `honue, zhoukuncheng, NekoAria`
- Source Location: `other/followrank.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 类型：anime - 动画，book - 图书，music - 音乐，game - 游戏，real - 三次元


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
  - `bgm.tv/:type`
- `target`: `/:type/followrank`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/anime/followrank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "other/followrank.ts",
  "maintainers": [
    "honue",
    "zhoukuncheng",
    "NekoAria"
  ],
  "name": "成员关注榜",
  "parameters": {
    "type": "类型：anime - 动画，book - 图书，music - 音乐，game - 游戏，real - 三次元"
  },
  "path": "/:type/followrank",
  "radar": [
    {
      "source": [
        "bgm.tv/:type"
      ],
      "target": "/:type/followrank"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "BangumiTV 首页 - 成员关注游戏榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "217190992522227712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/game",
      "title": "BangumiTV 成员关注游戏榜",
      "type": "feed",
      "url": "rsshub://bangumi.tv/game/followrank"
    },
    {
      "description": "BangumiTV 首页 - 成员关注动画榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74067850437124096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/anime",
      "title": "BangumiTV 成员关注动画榜",
      "type": "feed",
      "url": "rsshub://bangumi.tv/anime/followrank"
    }
  ]
}
```
