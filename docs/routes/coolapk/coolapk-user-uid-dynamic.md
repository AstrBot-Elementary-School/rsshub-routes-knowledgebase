# 酷安 - 用户

## Coverage
`index-only`

## Route
- Namespace: `coolapk`
- Namespace Name: `酷安`
- Route Path: `/coolapk/user/:uid/dynamic`
- Route Name: `用户`
- Example: `/coolapk/user/3177668/dynamic`
- URL: `coolapk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xizeyoupan`
- Source Location: `user-dynamic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 在个人界面右上分享-复制链接获取


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
  "example": "/coolapk/user/3177668/dynamic",
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
  "heat": 104,
  "location": "user-dynamic.ts",
  "maintainers": [
    "xizeyoupan"
  ],
  "name": "用户",
  "parameters": {
    "uid": "在个人界面右上分享-复制链接获取"
  },
  "path": "/user/:uid/dynamic",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "酷安个人动态-那片梧桐那场雨 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73404595408532480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/u/1080570",
      "title": "酷安个人动态-那片梧桐那场雨",
      "type": "feed",
      "url": "rsshub://coolapk/user/1080570/dynamic"
    },
    {
      "description": "酷安个人动态-晨钟酱 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68924893291413504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coolapk.com/u/630380",
      "title": "酷安个人动态-晨钟酱",
      "type": "feed",
      "url": "rsshub://coolapk/user/630380/dynamic"
    }
  ]
}
```
