# 酷安 - 图文

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/tuwen/:type?`
- Route Name: `图文`
- Example: `/coolapk/tuwen`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `tuwen.ts`
- Source Module: `_None_`

## Description
| 参数名称 | 编辑精选 | 最新   |
| -------- | -------- | ------ |
| type     | hot      | latest |

## Parameters
- `type`: 默认为hot


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
  "description": "| 参数名称 | 编辑精选 | 最新   |\n| -------- | -------- | ------ |\n| type     | hot      | latest |",
  "example": "/coolapk/tuwen",
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
  "heat": 1081,
  "location": "tuwen.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "图文",
  "parameters": {
    "type": "默认为hot"
  },
  "path": "/tuwen/:type?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "酷安图文 - 编辑精选 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54083984224404480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "酷安图文 - 编辑精选",
      "type": "feed",
      "url": "rsshub://coolapk/tuwen"
    },
    {
      "description": "酷安 - 新鲜图文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59083231915003968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "酷安 - 新鲜图文",
      "type": "feed",
      "url": "rsshub://coolapk/tuwen/latest"
    }
  ]
}
```
