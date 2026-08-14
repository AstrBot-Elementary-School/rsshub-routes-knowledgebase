# 酷安 - 话题

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/huati/:tag`
- Route Name: `话题`
- Example: `/coolapk/huati/iPhone`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `huati.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 话题名称


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
  "example": "/coolapk/huati/iPhone",
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
  "heat": 1041,
  "location": "huati.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "话题",
  "parameters": {
    "tag": "话题名称"
  },
  "path": "/huati/:tag",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "酷安话题-薅羊毛小分队 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59083231915003967",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "酷安话题-薅羊毛小分队",
      "type": "feed",
      "url": "rsshub://coolapk/huati/%E8%96%85%E7%BE%8A%E6%AF%9B%E5%B0%8F%E5%88%86%E9%98%9F"
    },
    {
      "description": "酷安话题-酷安夜话 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69604119970038786",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/",
      "title": "酷安话题-酷安夜话",
      "type": "feed",
      "url": "rsshub://coolapk/huati/%E9%85%B7%E5%AE%89%E5%A4%9C%E8%AF%9D"
    }
  ]
}
```
