# 3DMGame - 游戏资讯

## Coverage
`index-only`

## Route
- Namespace: `3dmgame`
- Namespace Name: `3DMGame`
- Route Path: `/3dmgame/games/:name/:type?`
- Route Name: `游戏资讯`
- Example: `/3dmgame/games/detroitbecomehuman/news`
- URL: `3dmgame.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `sinchang, yangkghjh, HenryQW, lyqluis`
- Source Location: `game.ts`
- Source Module: `_None_`

## Description
| 新闻 | 攻略 | 资源     |
| ---- | ---- | -------- |
| news | gl   | resource |

## Parameters
- `name`: 游戏名字，可以在专题页的 url 中找到
- `type`: 资讯类型，见下表，默认为 `news`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `3dmgame.com/games/:name/:type`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻 | 攻略 | 资源     |\n| ---- | ---- | -------- |\n| news | gl   | resource |",
  "example": "/3dmgame/games/detroitbecomehuman/news",
  "heat": 0,
  "location": "game.ts",
  "maintainers": [
    "sinchang",
    "yangkghjh",
    "HenryQW",
    "lyqluis"
  ],
  "name": "游戏资讯",
  "parameters": {
    "name": "游戏名字，可以在专题页的 url 中找到",
    "type": "资讯类型，见下表，默认为 `news`"
  },
  "path": "/games/:name/:type?",
  "radar": [
    {
      "source": [
        "3dmgame.com/games/:name/:type"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
