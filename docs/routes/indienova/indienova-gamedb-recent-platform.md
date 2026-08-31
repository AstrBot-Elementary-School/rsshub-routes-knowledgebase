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
  "heat": 1,
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
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "游戏库 - 最近发行的游戏（全平台） | indienova GameDB 游戏库 - Powered by RSSHub",
      "errorAt": "2026-08-29T17:35:32.279Z",
      "errorMessage": "[GET] \"https://indienova.com/game/custom-romance-city-3d3\": 404 Not Found\n",
      "id": "63456437927240704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "游戏库 - 最近发行的游戏（全平台） | indienova GameDB 游戏库",
      "type": "feed",
      "url": "rsshub://indienova/gamedb/recent"
    }
  ]
}
```
