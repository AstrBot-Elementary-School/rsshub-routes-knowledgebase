# 虎扑 - 手机虎扑网

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/dept/:category?`
- Route Name: `手机虎扑网`
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
  - `m.hupu.com/:category`
  - `m.hupu.com/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n电竞分类参见 [游戏热帖](https://bbs.hupu.com/all-gg) 的对应路由 [`/hupu/all/all-gg`](https://rsshub.app/hupu/all/all-gg)。\n:::",
  "example": "/hupu/nba",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "hyoban"
  ],
  "name": "手机虎扑网",
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
  "path": [
    "/dept/:category?",
    "/:category?"
  ],
  "radar": [
    {
      "source": [
        "m.hupu.com/:category",
        "m.hupu.com/"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "虎扑 - NBA - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77971487620786176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.hupu.com/nba",
      "title": "虎扑 - NBA",
      "type": "feed",
      "url": "rsshub://hupu/dept/nba"
    }
  ],
  "url": "m.hupu.com"
}
```
