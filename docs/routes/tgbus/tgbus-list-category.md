# 电玩巴士 TGBUS - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `tgbus`
- Namespace Name: `电玩巴士 TGBUS`
- Route Path: `/tgbus/list/:category`
- Route Name: `文章列表`
- Example: `/tgbus/list/news`
- URL: `tgbus.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Xzonn`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
| 最新资讯 | 游戏评测 | 游戏视频 | 巴士首页特稿 | 硬件资讯 |
| -------- | -------- | -------- | ------------ | -------- |
| news     | review   | video    | special      | hardware |

## Parameters
- `category`: 列表分类，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.tgbus.com/list/:category/`
- `target`: `/list/:category`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 最新资讯 | 游戏评测 | 游戏视频 | 巴士首页特稿 | 硬件资讯 |\n| -------- | -------- | -------- | ------------ | -------- |\n| news     | review   | video    | special      | hardware |",
  "example": "/tgbus/list/news",
  "heat": 56,
  "location": "list.ts",
  "maintainers": [
    "Xzonn"
  ],
  "name": "文章列表",
  "parameters": {
    "category": "列表分类，见下表"
  },
  "path": "/list/:category",
  "radar": [
    {
      "source": [
        "www.tgbus.com/list/:category/"
      ],
      "target": "/list/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "电玩巴士综合游戏门户站，一直致力于发展电玩产业和游戏事业，为全球用户24小时提供全面的游戏和主机资讯，游戏评测，游戏攻略，游戏视频，游戏资料库，以及打造拥有数千万会员的社交新媒体平台。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72602387683715072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tgbus.com/list/news/",
      "title": "最新资讯 - 电玩巴士",
      "type": "feed",
      "url": "rsshub://tgbus/list/news"
    }
  ]
}
```
