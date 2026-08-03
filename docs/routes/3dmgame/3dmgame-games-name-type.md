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
- Maintainers: `sinchang, jacky2001114, HenryQW, lyqluis`
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
    "jacky2001114",
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
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
