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
  "heat": 21,
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "守望先锋新闻 - Powered by RSSHub",
      "errorAt": "2026-07-25T22:35:24.720Z",
      "errorMessage": "[GET] \"https://shop.battlenet.com.cn/zh-cn/product/blizzcon-celebration-collection\": 401 \n[GET] \"https://shop.battlenet.com.cn/zh-cn/product/blizzcon-celebration-collection\": 401 \n",
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
      "errorAt": "2026-07-23T00:58:12.178Z",
      "errorMessage": "[GET] \"https://shop.battlenet.com.cn/zh-cn/product/blizzcon-celebration-collection\": 401 \n",
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
