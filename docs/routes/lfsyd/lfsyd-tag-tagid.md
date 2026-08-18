# 旅法师营地 - 分区

## Coverage
`index-only`

## Route
- Namespace: `lfsyd`
- Namespace Name: `旅法师营地`
- Route Path: `/lfsyd/tag/:tagId?`
- Route Name: `分区`
- Example: `/lfsyd/tag/17`
- URL: `www.iyingdi.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `auto-bot-ty`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
| 炉石传说 | 万智牌 | 游戏王 | 昆特牌 | 影之诗 | 符文之地传奇 | 阴阳师百闻牌 |
| :------: | :----: | :----: | :----: | :----: | :----------: | :----------: |
|    17    |   18   |   16   |   19   |   20   |      329     |      221     |

| 英雄联盟 | 电子游戏 | 桌面游戏 | 卡牌游戏 | 玩家杂谈 | 二次元 |
| :------: | :------: | :------: | :------: | :------: | :----: |
|    112   |    389   |    24    |    102   |    23    |   117  |

## Parameters
- `tagId`: 订阅分区类型


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mob.iyingdi.com/fine/:tagId`
- `target`: `/tag/:tagId`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 炉石传说 | 万智牌 | 游戏王 | 昆特牌 | 影之诗 | 符文之地传奇 | 阴阳师百闻牌 |\n| :------: | :----: | :----: | :----: | :----: | :----------: | :----------: |\n|    17    |   18   |   16   |   19   |   20   |      329     |      221     |\n\n| 英雄联盟 | 电子游戏 | 桌面游戏 | 卡牌游戏 | 玩家杂谈 | 二次元 |\n| :------: | :------: | :------: | :------: | :------: | :----: |\n|    112   |    389   |    24    |    102   |    23    |   117  |",
  "example": "/lfsyd/tag/17",
  "heat": 90,
  "location": "tag.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "name": "分区",
  "parameters": {
    "tagId": "订阅分区类型"
  },
  "path": "/tag/:tagId?",
  "radar": [
    {
      "source": [
        "mob.iyingdi.com/fine/:tagId"
      ],
      "target": "/tag/:tagId"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "炉石传说 - 旅法师营地 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56204588915011588",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iyingdi.com/tz/tag/17",
      "title": "炉石传说 - 旅法师营地",
      "type": "feed",
      "url": "rsshub://lfsyd/tag/17"
    },
    {
      "description": "游戏王 - 旅法师营地 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60263446472040460",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iyingdi.com/tz/tag/16",
      "title": "游戏王 - 旅法师营地",
      "type": "feed",
      "url": "rsshub://lfsyd/tag/16"
    }
  ],
  "url": "www.iyingdi.com/"
}
```
