# 哔哩哔哩 bilibili - 用户关注动态

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/followings/dynamic/:uid/:routeParams?`
- Route Name: `用户关注动态`
- Example: `/bilibili/followings/dynamic/109937383`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, JimenezLi`
- Source Location: `followings-dynamic.ts`
- Source Module: `_None_`

## Description
::: warning
用户动态需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `routeParams`: | 键         | 含义                              | 接受的值       | 默认值 |
| ---------- | --------------------------------- | -------------- | ------ |
| showEmoji  | 显示或隐藏表情图片                | 0/1/true/false | false  |
| embed      | 默认开启内嵌视频                  | 0/1/true/false |  true  |
| useAvid    | 视频链接使用 AV 号 (默认为 BV 号) | 0/1/true/false | false  |
| directLink | 使用内容直链                      | 0/1/true/false | false  |
| hideGoods  | 隐藏带货动态                      | 0/1/true/false | false  |

用例：`/bilibili/followings/dynamic/2267573/showEmoji=1&embed=0&useAvid=1`


## Features
- `requireConfig`: [{"description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  复制整段 Cookie，删掉其中的 `bili_ticket` 和 `bili_ticket_expires` 字段来延长有效期", "name": "BILIBILI_COOKIE_*"}]
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
  "example": "/bilibili/followings/dynamic/109937383",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  复制整段 Cookie，删掉其中的 `bili_ticket` 和 `bili_ticket_expires` 字段来延长有效期",
        "name": "BILIBILI_COOKIE_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "followings-dynamic.ts",
  "maintainers": [
    "TigerCubDen",
    "JimenezLi"
  ],
  "name": "用户关注动态",
  "parameters": {
    "routeParams": "\n| 键         | 含义                              | 接受的值       | 默认值 |\n| ---------- | --------------------------------- | -------------- | ------ |\n| showEmoji  | 显示或隐藏表情图片                | 0/1/true/false | false  |\n| embed      | 默认开启内嵌视频                  | 0/1/true/false |  true  |\n| useAvid    | 视频链接使用 AV 号 (默认为 BV 号) | 0/1/true/false | false  |\n| directLink | 使用内容直链                      | 0/1/true/false | false  |\n| hideGoods  | 隐藏带货动态                      | 0/1/true/false | false  |\n\n用例：`/bilibili/followings/dynamic/2267573/showEmoji=1&embed=0&useAvid=1`",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/followings/dynamic/:uid/:routeParams?",
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-25T07:36:40.420Z",
      "errorMessage": "缺少对应 uid 的 Bilibili 用户登录后的 Cookie 值\n",
      "id": "182658801734908928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://bilibili/followings/dynamic/399277904"
    },
    {
      "description": "myvirusKM 关注的动态 - Powered by RSSHub",
      "errorAt": "2025-03-30T14:11:30.397Z",
      "errorMessage": "Failed to fetch\n缺少对应 uid 的 Bilibili 用户登录后的 Cookie 值\n",
      "id": "128713010064425984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://t.bilibili.com/",
      "title": "myvirusKM 关注的动态",
      "type": "feed",
      "url": "rsshub://bilibili/followings/dynamic/318937631"
    }
  ]
}
```
