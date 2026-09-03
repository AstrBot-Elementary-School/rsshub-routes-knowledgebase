# 酷安 - 看看号

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/dyh/:dyhId`
- Route Name: `看看号`
- Example: `/coolapk/dyh/1524`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `dyh.ts`
- Source Module: `_None_`

## Description
::: tip
仅限于采集**站内订阅**的看看号的内容。看看号 ID 可在看看号界面右上分享 - 复制链接得到。
:::

## Parameters
- `dyhId`: 看看号ID


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
  "description": "::: tip\n仅限于采集**站内订阅**的看看号的内容。看看号 ID 可在看看号界面右上分享 - 复制链接得到。\n:::",
  "example": "/coolapk/dyh/1524",
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
  "heat": 24,
  "location": "dyh.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "看看号",
  "parameters": {
    "dyhId": "看看号ID"
  },
  "path": "/dyh/:dyhId",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "我们致力于 发表和集合对科技圈内事件或产品， 有独特见解和深入思考的评论和文章。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62825086347448325",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/dyh/2997",
      "title": "酷安看看号-拍案叫绝的好文",
      "type": "feed",
      "url": "rsshub://coolapk/dyh/2997"
    },
    {
      "description": "路由器开发教程 路由器教学 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76151852424894464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/dyh/4451",
      "title": "酷安看看号-家庭网络学堂",
      "type": "feed",
      "url": "rsshub://coolapk/dyh/4451"
    }
  ]
}
```
