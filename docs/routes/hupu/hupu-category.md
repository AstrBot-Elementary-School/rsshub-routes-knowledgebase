# 虎扑 - 移动版

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/:category?`
- Route Name: `移动版`
- Example: `/hupu/nba`
- URL: `m.hupu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, hyoban`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
电竞分类参见 [游戏热帖](https://bbs.hupu.com/all-gg) 的对应路由 [`/hupu/all/all-gg`](https://rsshub.app/hupu/all/all-gg)。
:::

## Parameters
- `category`: {"default": "", "description": "分类，可选值：nba、cba、soccer，默认为空（首页）", "options": [{"label": "NBA", "value": "nba"}, {"label": "CBA", "value": "cba"}, {"label": "足球", "value": "soccer"}, {"label": "首页", "value": ""}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.hupu.com/`
- `target`: `/`
### Rule 2
- `source`:
  - `m.hupu.com/nba`
- `target`: `/nba`
### Rule 3
- `source`:
  - `m.hupu.com/cba`
- `target`: `/cba`
### Rule 4
- `source`:
  - `m.hupu.com/soccer`
- `target`: `/soccer`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n电竞分类参见 [游戏热帖](https://bbs.hupu.com/all-gg) 的对应路由 [`/hupu/all/all-gg`](https://rsshub.app/hupu/all/all-gg)。\n:::",
  "example": "/hupu/nba",
  "heat": 149,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "hyoban"
  ],
  "name": "移动版",
  "parameters": {
    "category": {
      "default": "",
      "description": "分类，可选值：nba、cba、soccer，默认为空（首页）",
      "options": [
        {
          "label": "NBA",
          "value": "nba"
        },
        {
          "label": "CBA",
          "value": "cba"
        },
        {
          "label": "足球",
          "value": "soccer"
        },
        {
          "label": "首页",
          "value": ""
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "m.hupu.com/"
      ],
      "target": "/"
    },
    {
      "source": [
        "m.hupu.com/nba"
      ],
      "target": "/nba"
    },
    {
      "source": [
        "m.hupu.com/cba"
      ],
      "target": "/cba"
    },
    {
      "source": [
        "m.hupu.com/soccer"
      ],
      "target": "/soccer"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "虎扑 - 足球 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54771679943372802",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.hupu.com/soccer",
      "title": "虎扑 - 足球",
      "type": "feed",
      "url": "rsshub://hupu/soccer"
    },
    {
      "description": "虎扑 - NBA - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68969704374671360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.hupu.com/nba",
      "title": "虎扑 - NBA",
      "type": "feed",
      "url": "rsshub://hupu/nba"
    }
  ],
  "url": "m.hupu.com"
}
```
