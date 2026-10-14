# 微博 - 用户收藏动态

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/user_bookmarks/:uid/:routeParams?`
- Route Name: `用户收藏动态`
- Example: `/weibo/user_bookmarks/1195230310`
- URL: `weibo.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `cztchoice`
- Source Location: `user-bookmarks.ts`
- Source Module: `_None_`

## Description
::: warning
此方案必须使用用户`Cookie`进行抓取，只可以获取本人的收藏动态

因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知

微博用户 Cookie 的配置可参照部署文档
:::

## Parameters
- `uid`: 用户 id, 博主主页打开控制台执行 `$CONFIG.oid` 获取
- `routeParams`: 额外参数；请参阅上面的说明和表格；特别地，当 `routeParams=1` 时开启微博视频显示


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
- `target`: `/user_bookmarks/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\n此方案必须使用用户`Cookie`进行抓取，只可以获取本人的收藏动态\n\n因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知\n\n微博用户 Cookie 的配置可参照部署文档\n:::",
  "example": "/weibo/user_bookmarks/1195230310",
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
  "location": "user-bookmarks.ts",
  "maintainers": [
    "cztchoice"
  ],
  "name": "用户收藏动态",
  "parameters": {
    "routeParams": "额外参数；请参阅上面的说明和表格；特别地，当 `routeParams=1` 时开启微博视频显示",
    "uid": "用户 id, 博主主页打开控制台执行 `$CONFIG.oid` 获取"
  },
  "path": "/user_bookmarks/:uid/:routeParams?",
  "radar": [
    {
      "source": [
        "weibo.com/"
      ],
      "target": "/user_bookmarks/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "weibo.com/"
}
```
