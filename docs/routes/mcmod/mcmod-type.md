# MC百科 - 最新MOD

## Coverage
`index-only`

## Route
- Namespace: `mcmod`
- Namespace Name: `MC百科`
- Route Path: `/mcmod/:type`
- Route Name: `最新MOD`
- Example: `/mcmod/new`
- URL: `www.mcmod.cn`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hualiong`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
`:type` 类型可选如下

| 随机显示 MOD | 最新收录 MOD | 最近编辑 MOD |
| ------------ | ------------ | ------------ |
| random       | new          | edit         |

## Parameters
- `type`: 查询类型，详见下表


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
  "description": "`:type` 类型可选如下\n\n| 随机显示 MOD | 最新收录 MOD | 最近编辑 MOD |\n| ------------ | ------------ | ------------ |\n| random       | new          | edit         |",
  "example": "/mcmod/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "index.tsx",
  "maintainers": [
    "hualiong"
  ],
  "name": "最新MOD",
  "parameters": {
    "type": "查询类型，详见下表"
  },
  "path": "/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "MC百科首页|我的世界MOD百科，提供Minecraft(我的世界)MOD(模组)物品资料介绍教程攻略和MOD下载。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56355911890850816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mcmod.cn/",
      "title": "MC百科最新收录的的MOD - MC百科",
      "type": "feed",
      "url": "rsshub://mcmod/new"
    },
    {
      "description": "MC百科首页|我的世界MOD百科，提供Minecraft(我的世界)MOD(模组)物品资料介绍教程攻略和MOD下载。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "132060968710740992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mcmod.cn/",
      "title": "最近被编辑的MOD - MC百科",
      "type": "feed",
      "url": "rsshub://mcmod/edit"
    }
  ]
}
```
