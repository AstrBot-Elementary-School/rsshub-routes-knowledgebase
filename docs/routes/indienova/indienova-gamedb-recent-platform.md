# indienova 独立游戏 - GameDB 游戏库

## Coverage
`index-only`

## Route
- Namespace: `indienova`
- Namespace Name: `indienova 独立游戏`
- Route Path: `/indienova/gamedb/recent/:platform?`
- Route Name: `GameDB 游戏库`
- Example: `/indienova/gamedb/recent`
- URL: `indienova.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `gamedb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `platform`: {"default": "all", "description": "平台，留空为 `all`", "options": [{"label": "全部", "value": "all"}, {"label": "PS4", "value": "ps4"}, {"label": "XBOX One", "value": "xboxone"}, {"label": "Nintendo Switch", "value": "nintendo-switch"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/indienova/gamedb/recent",
  "heat": 0,
  "location": "gamedb.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "GameDB 游戏库",
  "parameters": {
    "platform": {
      "default": "all",
      "description": "平台，留空为 `all`",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "PS4",
          "value": "ps4"
        },
        {
          "label": "XBOX One",
          "value": "xboxone"
        },
        {
          "label": "Nintendo Switch",
          "value": "nintendo-switch"
        }
      ]
    }
  },
  "path": "/gamedb/recent/:platform?",
  "topFeeds": []
}
```
