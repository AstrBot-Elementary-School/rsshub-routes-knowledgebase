# 酷安 - 头条

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/toutiao/:type?`
- Route Name: `头条`
- Example: `/coolapk/toutiao`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `toutiao.ts`
- Source Module: `_None_`

## Description
| 参数名称 | 历史头条 | 最新   |
| -------- | -------- | ------ |
| type     | history  | latest |

## Parameters
- `type`: 默认为history


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
  "description": "| 参数名称 | 历史头条 | 最新   |\n| -------- | -------- | ------ |\n| type     | history  | latest |",
  "example": "/coolapk/toutiao",
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
  "heat": 102,
  "location": "toutiao.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "头条",
  "parameters": {
    "type": "默认为history"
  },
  "path": "/toutiao/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "历史头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54905314771686400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "历史头条",
      "type": "feed",
      "url": "rsshub://coolapk/toutiao"
    },
    {
      "description": "最新动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56569874911161344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "最新动态",
      "type": "feed",
      "url": "rsshub://coolapk/toutiao/latest"
    }
  ]
}
```
