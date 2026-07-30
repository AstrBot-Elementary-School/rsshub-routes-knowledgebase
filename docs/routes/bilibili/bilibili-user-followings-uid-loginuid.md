# 哔哩哔哩 bilibili - UP 主关注用户

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/followings/:uid/:loginUid`
- Route Name: `UP 主关注用户`
- Example: `/bilibili/user/followings/2267573/3`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `followings.ts`
- Source Module: `_None_`

## Description
::: warning
UP 主关注用户现在需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `loginUid`: 用于登入的用户id,需要配置对应的 Cookie 值


## Features
- `requireConfig`: [{"description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie", "name": "BILIBILI_COOKIE_*"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `space.bilibili.com/:uid`
- `target`: `/user/followings/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\nUP 主关注用户现在需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/bilibili/user/followings/2267573/3",
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
  "heat": 8,
  "location": "followings.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "UP 主关注用户",
  "parameters": {
    "loginUid": "用于登入的用户id,需要配置对应的 Cookie 值",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/followings/:uid/:loginUid",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/followings/:uid"
    }
  ],
  "topFeeds": [
    {
      "description": "PH64E 的 bilibili 关注 - Powered by RSSHub",
      "errorAt": "2026-01-30T03:44:41.001Z",
      "errorMessage": "缺少对应 loginUid 的 Bilibili 用户登录后的 Cookie 值 <a href=\"https://docs.rsshub.app/zh/deploy/config#route-specific-configurations\">bilibili 用户关注动态系列路由</a>\n缺少对应 loginUid 的 Bilibili 用户登录后的 Cookie 值 <a href=\"https://docs.rsshub.app/zh/deploy/config#route-specific-configurations\">bilibili 用户关注动态系列路由</a>\n",
      "id": "198984620760968192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/291241870/#/fans/follow",
      "title": "PH64E 的 bilibili 关注",
      "type": "feed",
      "url": "rsshub://bilibili/user/followings/291241870/114145696"
    },
    {
      "description": "w小璃 的 bilibili 关注 - Powered by RSSHub",
      "errorAt": "2026-01-30T03:43:23.009Z",
      "errorMessage": "缺少对应 loginUid 的 Bilibili 用户登录后的 Cookie 值 <a href=\"https://docs.rsshub.app/zh/deploy/config#route-specific-configurations\">bilibili 用户关注动态系列路由</a>\n缺少对应 loginUid 的 Bilibili 用户登录后的 Cookie 值 <a href=\"https://docs.rsshub.app/zh/deploy/config#route-specific-configurations\">bilibili 用户关注动态系列路由</a>\n",
      "id": "198986045293407232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/36084148/#/fans/follow",
      "title": "w小璃 的 bilibili 关注",
      "type": "feed",
      "url": "rsshub://bilibili/user/followings/36084148/114145696"
    }
  ]
}
```
