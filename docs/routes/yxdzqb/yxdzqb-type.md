# 游戏打折情报 - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `yxdzqb`
- Namespace Name: `游戏打折情报`
- Route Path: `/yxdzqb/:type`
- Route Name: `游戏折扣`
- Example: `/yxdzqb/popular_cn`
- URL: `yxdzqb.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| Steam 最新折扣 | Steam 热门游戏折扣 | Steam 热门中文游戏折扣 | Steam 历史低价 | Steam 中文游戏历史低价 |
| -------------- | ------------------ | ---------------------- | -------------- | ---------------------- |
| discount       | popular            | popular\_cn            | low            | low\_cn                |

## Parameters
- `type`: 折扣类型


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
  - `yxdzqb.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| Steam 最新折扣 | Steam 热门游戏折扣 | Steam 热门中文游戏折扣 | Steam 历史低价 | Steam 中文游戏历史低价 |\n| -------------- | ------------------ | ---------------------- | -------------- | ---------------------- |\n| discount       | popular            | popular\\_cn            | low            | low\\_cn                |",
  "example": "/yxdzqb/popular_cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 560,
  "location": "index.tsx",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "name": "游戏折扣",
  "parameters": {
    "type": "折扣类型"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "yxdzqb.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Steam 热门游戏历史低价-游戏打折情报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52721325092269088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yxdzqb.com/index_low.html",
      "title": "Steam 热门游戏历史低价-游戏打折情报",
      "type": "feed",
      "url": "rsshub://yxdzqb/low"
    },
    {
      "description": "中文热门游戏折扣合集-游戏打折情报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41476070206969860",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yxdzqb.com/index_popular_cn.html",
      "title": "中文热门游戏折扣合集-游戏打折情报",
      "type": "feed",
      "url": "rsshub://yxdzqb/popular_cn"
    }
  ],
  "url": "yxdzqb.com/"
}
```
