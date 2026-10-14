# 微博 - 最新关注时间线

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/friends/:routeParams?`
- Route Name: `最新关注时间线`
- Example: `/weibo/friends`
- URL: `weibo.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `CaoMeiYouRen`
- Source Location: `friends.ts`
- Source Module: `_None_`

## Description
::: warning
此方案必须使用用户`Cookie`进行抓取

因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知

微博用户 Cookie 的配置可参照部署文档
:::

## Parameters
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `weibo.com/`
- `target`: `/friends`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\n此方案必须使用用户`Cookie`进行抓取\n\n因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知\n\n微博用户 Cookie 的配置可参照部署文档\n:::",
  "example": "/weibo/friends",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "friends.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "最新关注时间线",
  "parameters": {
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/friends/:routeParams?",
  "radar": [
    {
      "source": [
        "weibo.com/"
      ],
      "target": "/friends"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "weibo.com/"
}
```
