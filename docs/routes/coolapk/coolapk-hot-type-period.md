# 酷安 - 热榜

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/hot/:type?/:period?`
- Route Name: `热榜`
- Example: `/coolapk/hot`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
| 参数名称 | 今日热门 | 点赞榜 | 评论榜 | 收藏榜 | 酷图榜 |
| -------- | -------- | ------ | ------ | ------ | ------ |
| type     | jrrm     | dzb    | plb    | scb    | ktb    |

| 参数名称 | 日榜  | 周榜   |
| -------- | ----- | ------ |
| period   | daily | weekly |

::: tip
今日热门没有周榜，酷图榜日榜的参数会变成周榜，周榜的参数会变成月榜。
:::

## Parameters
- `type`: 默认为`jrrm`
- `period`: 默认为`daily`


## Features
- `requireConfig`: [{"description": "设置为`true`并添加`image_hotlink_template`参数来代理图片", "name": "ALLOW_USER_HOTLINK_TEMPLATE", "optional": true}]
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
    "social-media"
  ],
  "description": "| 参数名称 | 今日热门 | 点赞榜 | 评论榜 | 收藏榜 | 酷图榜 |\n| -------- | -------- | ------ | ------ | ------ | ------ |\n| type     | jrrm     | dzb    | plb    | scb    | ktb    |\n\n| 参数名称 | 日榜  | 周榜   |\n| -------- | ----- | ------ |\n| period   | daily | weekly |\n\n::: tip\n今日热门没有周榜，酷图榜日榜的参数会变成周榜，周榜的参数会变成月榜。\n:::",
  "example": "/coolapk/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "设置为`true`并添加`image_hotlink_template`参数来代理图片",
        "name": "ALLOW_USER_HOTLINK_TEMPLATE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 416,
  "location": "hot.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "热榜",
  "parameters": {
    "period": "默认为`daily`",
    "type": "默认为`jrrm`"
  },
  "path": "/hot/:type?/:period?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "热榜-今日热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53366652701156360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "今日热门",
      "type": "feed",
      "url": "rsshub://coolapk/hot"
    },
    {
      "description": "热榜-收藏榜-周榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61940628618176512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "收藏榜-周榜",
      "type": "feed",
      "url": "rsshub://coolapk/hot/scb/weekly"
    }
  ]
}
```
