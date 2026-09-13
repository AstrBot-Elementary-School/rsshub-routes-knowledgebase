# 哔哩哔哩 bilibili - 用户关注视频动态

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/followings/video/:uid/:embed?`
- Route Name: `用户关注视频动态`
- Example: `/bilibili/followings/video/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `followings-video.ts`
- Source Module: `_None_`

## Description
::: warning
用户动态需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `uid`: 用户 id
- `embed`: 默认为开启内嵌视频，任意值为关闭


## Features
- `requireConfig`: [{"description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie", "name": "BILIBILI_COOKIE_*"}]
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
  "description": "::: warning\n用户动态需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/bilibili/followings/video/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie",
        "name": "BILIBILI_COOKIE_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "followings-video.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "用户关注视频动态",
  "parameters": {
    "embed": "默认为开启内嵌视频，任意值为关闭",
    "uid": "用户 id"
  },
  "path": "/followings/video/:uid/:embed?",
  "topFeeds": [
    {
      "description": "炎帝-采薇 关注视频动态 - Powered by RSSHub",
      "errorAt": "2025-06-17T14:53:46.317Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/space/wbi/acc/info?mid=102745329&token=&platform=web&web_location=1550101&w_rid=790070df915de56587db92810c429a60&wts=1789134361\": 412 Precondition Failed\n",
      "id": "154580129950460928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.bilibili.com/?tab=8",
      "title": "炎帝-采薇 关注视频动态",
      "type": "feed",
      "url": "rsshub://bilibili/followings/video/102745329"
    },
    {
      "description": "可知Elysia 关注视频动态 - Powered by RSSHub",
      "errorAt": "2026-03-31T11:15:13.852Z",
      "errorMessage": "缺少对应 uid 的 Bilibili 用户登录后的 Cookie 值\n",
      "id": "261624671766061056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.bilibili.com/?tab=8",
      "title": "可知Elysia 关注视频动态",
      "type": "feed",
      "url": "rsshub://bilibili/followings/video/78031804"
    }
  ]
}
```
