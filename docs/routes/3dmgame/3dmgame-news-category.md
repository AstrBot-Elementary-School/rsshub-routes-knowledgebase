# 3DMGame - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `3dmgame`
- Namespace Name: `3DMGame`
- Route Path: `/3dmgame/news/:category?`
- Route Name: `新闻中心`
- Example: `/3dmgame/news`
- URL: `3dmgame.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `zhboner, lyqluis`
- Source Location: `news-center.ts`
- Source Module: `_None_`

## Description
| 新闻推荐 | 游戏新闻 | 动漫影视 | 智能数码 | 时事焦点    |
| -------- | -------- | -------- | -------- | ----------- |
|          | game     | acg      | next     | news\_36\_1 |

## Parameters
- `category`: 分类名或 ID，见下表，默认为新闻推荐，ID 可从分类 URL 中找到，如 Steam 为 `22221`


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
  - `3dmgame.com/news/:category?`
  - `3dmgame.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻推荐 | 游戏新闻 | 动漫影视 | 智能数码 | 时事焦点    |\n| -------- | -------- | -------- | -------- | ----------- |\n|          | game     | acg      | next     | news\\_36\\_1 |",
  "example": "/3dmgame/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 778,
  "location": "news-center.ts",
  "maintainers": [
    "zhboner",
    "lyqluis"
  ],
  "name": "新闻中心",
  "parameters": {
    "category": "分类名或 ID，见下表，默认为新闻推荐，ID 可从分类 URL 中找到，如 Steam 为 `22221`"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "3dmgame.com/news/:category?",
        "3dmgame.com/news"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "3DM新闻中心为广大互联网用户提供前沿的新闻资讯，让玩家及时了解到最新的游戏新闻、动漫影视、智能数码、游戏硬件和时事焦点等相关资讯。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55939235463397394",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.3dmgame.com/news/",
      "title": "3DM - 新闻中心",
      "type": "feed",
      "url": "rsshub://3dmgame/news"
    },
    {
      "description": "3DM新闻中心为广大互联网用户提供前沿的游戏新闻资讯，让玩家及时了解到最新的单机资讯、游戏杂谈、游戏周边和厂商动态等相关资讯。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60199571398524974",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.3dmgame.com/news/game",
      "title": "3DM - 游戏新闻",
      "type": "feed",
      "url": "rsshub://3dmgame/news/game"
    }
  ]
}
```
