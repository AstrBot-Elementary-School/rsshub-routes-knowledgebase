# 即刻 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `jike`
- Namespace Name: `即刻`
- Route Path: `/jike/user/:id`
- Route Name: `用户动态`
- Example: `/jike/user/3EE02BC9-C5B3-4209-8750-4ED1EE0F67BB`
- URL: `m.okjike.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, prnake`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在即刻分享出来的单条动态页点击用户头像进入个人主页，然后在个人主页的 URL 中找到，或者在单条动态页使用 RSSHub Radar 插件


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
  - `web.okjike.com/u/:uid`
- `target`: `/user/:uid`
### Rule 2
- `source`:
  - `m.okjike.com/users/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/jike/user/3EE02BC9-C5B3-4209-8750-4ED1EE0F67BB",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8876,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "prnake"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在即刻分享出来的单条动态页点击用户头像进入个人主页，然后在个人主页的 URL 中找到，或者在单条动态页使用 RSSHub Radar 插件"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "web.okjike.com/u/:uid"
      ],
      "target": "/user/:uid"
    },
    {
      "source": [
        "m.okjike.com/users/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "读书人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55441417631126528",
      "image": "https://cdnv2.ruguoapp.com/o_1aif987v84gp1jcb17p11p9714nni0j?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/1000x1000%3E",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/users/752D3103-1107-43A0-BA49-20EC29D09E36",
      "title": "李继刚的即刻动态",
      "type": "feed",
      "url": "rsshub://jike/user/752D3103-1107-43A0-BA49-20EC29D09E36"
    },
    {
      "description": "产品设计师、模型设计师、 不会代码的独立开发者。 关注人工智能、LLM 、 Stable Diffusion 和设计。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53641991802971136",
      "image": "https://cdnv2.ruguoapp.com/Fj5tDD16PIzqrasLRqqKXWgbyCdK.jpg?imageMogr2/auto-orient/heic-exif/1/format/jpeg/thumbnail/!1000x1000r/gravity/Center/crop/!1000x1000a0a0",
      "ownerUserId": null,
      "siteUrl": "https://m.okjike.com/users/0ae2afa7-9b10-4b3a-ab7e-15fbf847038d",
      "title": "歸藏的即刻动态",
      "type": "feed",
      "url": "rsshub://jike/user/0ae2afa7-9b10-4b3a-ab7e-15fbf847038d"
    }
  ],
  "view": 1
}
```
