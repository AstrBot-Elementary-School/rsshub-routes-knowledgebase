# 掘金 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/dynamic/:id`
- Route Name: `用户动态`
- Example: `/juejin/dynamic/3051900006845944`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `CaoMeiYouRen`
- Source Location: `dynamic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户页 URL 中找到


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
  - `juejin.cn/user/:id`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "example": "/juejin/dynamic/3051900006845944",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2514,
  "location": "dynamic.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在用户页 URL 中找到"
  },
  "path": "/dynamic/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "转转研发中心及业界小伙伴们的技术学习交流平台，定期分享一线的实战经验及业界前沿的技术话题。 关注公众号「转转技术」，各种干货实践，欢迎交流分享~ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60581256245570560",
      "image": "https://p26-passport.byteacctimg.com/img/user-avatar/5569c2276ef448736bde1221ea5fc846~300x300.image",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/user/606586148237431/",
      "title": "掘金用户动态-转转技术团队",
      "type": "feed",
      "url": "rsshub://juejin/dynamic/606586148237431"
    },
    {
      "description": "闻道有先后 术业有专攻 如是而已 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76079396595293184",
      "image": "https://p6-passport.byteacctimg.com/img/user-avatar/c5da4b562bd2afd428bc1ea82c2b42ab~300x300.image",
      "ownerUserId": "43445829338141696",
      "siteUrl": "https://juejin.cn/user/1816846860560749/",
      "title": "掘金用户动态-Gracker",
      "type": "feed",
      "url": "rsshub://juejin/dynamic/1816846860560749"
    }
  ]
}
```
