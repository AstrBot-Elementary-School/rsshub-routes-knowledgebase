# CNTV - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cntv`
- Namespace Name: `CNTV`
- Route Path: `/cntv/:column`
- Route Name: `栏目`
- Example: `/cntv/TOPC1451528971114112`
- URL: `navi.cctv.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `WhoIsSure, Fatpandac`
- Source Location: `column.tsx`
- Source Module: `_None_`

## Description
::: tip
栏目 ID 查找示例:
打开栏目具体某一期页面，F12 控制台输入`column_id`得到栏目 ID。
:::

栏目

| 新闻联播             | 新闻周刊             | 天下足球             |
| -------------------- | -------------------- | -------------------- |
| TOPC1451528971114112 | TOPC1451559180488841 | TOPC1451551777876756 |

## Parameters
- `column`: 栏目ID, 可在对应CNTV栏目页面找到


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
  - `navi.cctv.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n栏目 ID 查找示例:\n打开栏目具体某一期页面，F12 控制台输入`column_id`得到栏目 ID。\n:::\n\n栏目\n\n| 新闻联播             | 新闻周刊             | 天下足球             |\n| -------------------- | -------------------- | -------------------- |\n| TOPC1451528971114112 | TOPC1451559180488841 | TOPC1451551777876756 |",
  "example": "/cntv/TOPC1451528971114112",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 206,
  "location": "column.tsx",
  "maintainers": [
    "WhoIsSure",
    "Fatpandac"
  ],
  "name": "栏目",
  "parameters": {
    "column": "栏目ID, 可在对应CNTV栏目页面找到"
  },
  "path": "/:column",
  "radar": [
    {
      "source": [
        "navi.cctv.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "新闻联播 栏目的视频更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59850111609529344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "CNTV 栏目 - 新闻联播",
      "type": "feed",
      "url": "rsshub://cntv/TOPC1451528971114112"
    },
    {
      "description": "新闻周刊 栏目的视频更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55873602868576259",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "CNTV 栏目 - 新闻周刊",
      "type": "feed",
      "url": "rsshub://cntv/TOPC1451559180488841"
    }
  ],
  "url": "navi.cctv.com/"
}
```
