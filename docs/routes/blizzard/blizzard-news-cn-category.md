# Blizzard - 暴雪游戏国服新闻

## Coverage
`index-only`

## Route
- Namespace: `blizzard`
- Namespace Name: `Blizzard`
- Route Path: `/blizzard/news-cn/:category?`
- Route Name: `暴雪游戏国服新闻`
- Example: `/blizzard/news-cn/ow`
- URL: `news.blizzard.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `zhangpeng2k`
- Source Location: `news-cn.ts`
- Source Module: `_None_`

## Description
| 守望先锋 | 炉石传说 | 魔兽世界 |
| -------- | -------- | -------- |
| ow       | hs       | wow      |

## Parameters
- `category`: 游戏类别, 默认为 ow


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
  - `ow.blizzard.cn`
- `target`: `/news-cn/`
### Rule 2
- `source`:
  - `wow.blizzard.cn`
- `target`: `/news-cn/`
### Rule 3
- `source`:
  - `hs.blizzard.cn`
- `target`: `/news-cn/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 守望先锋 | 炉石传说 | 魔兽世界 |\n| -------- | -------- | -------- |\n| ow       | hs       | wow      |",
  "example": "/blizzard/news-cn/ow",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "news-cn.ts",
  "maintainers": [
    "zhangpeng2k"
  ],
  "name": "暴雪游戏国服新闻",
  "parameters": {
    "category": "游戏类别, 默认为 ow"
  },
  "path": "/news-cn/:category?",
  "radar": [
    {
      "source": [
        "ow.blizzard.cn"
      ],
      "target": "/news-cn/"
    },
    {
      "source": [
        "wow.blizzard.cn"
      ],
      "target": "/news-cn/"
    },
    {
      "source": [
        "hs.blizzard.cn"
      ],
      "target": "/news-cn/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "守望先锋新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "101228634856437760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ow.blizzard.cn/news",
      "title": "守望先锋新闻",
      "type": "feed",
      "url": "rsshub://blizzard/news-cn/ow"
    },
    {
      "description": "守望先锋新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102293253660793856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ow.blizzard.cn/news",
      "title": "守望先锋新闻",
      "type": "feed",
      "url": "rsshub://blizzard/news-cn"
    }
  ]
}
```
