# Lofter - Tag

## Coverage
`index-only`

## Route
- Namespace: `lofter`
- Namespace Name: `Lofter`
- Route Path: `/lofter/tag/:name?/:type?`
- Route Name: `Tag`
- Example: `/lofter/tag/cosplay/date`
- URL: `www.lofter.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc, nczitzk, LucunJi`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
::: warning
搜索标签下的最新内容需要 Lofter 登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

| new  | date | week | month | total |
| ---- | ---- | ---- | ----- | ----- |
| 最新 | 日榜 | 周榜 | 月榜  | 总榜  |

## Parameters
- `name`: tag name, such as `名侦探柯南`, `摄影` by default
- `type`: ranking type, see below, new by default


## Features
- `requireConfig`: [{"description": "LOFTER_COOKIE: 用于搜索标签相关内容，获取方式：\n    1.  登录 Lofter 并搜索任一标签，进入页面 https://www.lofter.com/tag/*\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 TagBean.seach.dwr 请求，找到 Cookie\n    4.  获取最新标签内容只要求 `LOFTER_SESS` 开始的字段", "name": "LOFTER_COOKIE"}]
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
  "description": "::: warning\n搜索标签下的最新内容需要 Lofter 登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::\n\n| new  | date | week | month | total |\n| ---- | ---- | ---- | ----- | ----- |\n| 最新 | 日榜 | 周榜 | 月榜  | 总榜  |",
  "example": "/lofter/tag/cosplay/date",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "LOFTER_COOKIE: 用于搜索标签相关内容，获取方式：\n    1.  登录 Lofter 并搜索任一标签，进入页面 https://www.lofter.com/tag/*\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 TagBean.seach.dwr 请求，找到 Cookie\n    4.  获取最新标签内容只要求 `LOFTER_SESS` 开始的字段",
        "name": "LOFTER_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 157,
  "location": "tag.ts",
  "maintainers": [
    "hoilc",
    "nczitzk",
    "LucunJi"
  ],
  "name": "Tag",
  "parameters": {
    "name": "tag name, such as `名侦探柯南`, `摄影` by default",
    "type": "ranking type, see below, new by default"
  },
  "path": "/tag/:name?/:type?",
  "topFeeds": [
    {
      "description": "摄影 - 最新 | LOFTER - Powered by RSSHub",
      "errorAt": "2025-06-07T12:21:11.609Z",
      "errorMessage": "Lofter 用户登录后的 Cookie 值\n",
      "id": "73253601886350336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lofter.com/tag/%E6%91%84%E5%BD%B1/new",
      "title": "摄影 - 最新 | LOFTER",
      "type": "feed",
      "url": "rsshub://lofter/tag"
    },
    {
      "description": "写真 - 日榜 | LOFTER - Powered by RSSHub",
      "errorAt": "2025-06-07T13:34:05.279Z",
      "errorMessage": "Lofter 用户登录后的 Cookie 值\nLofter 用户登录后的 Cookie 值\n",
      "id": "73656500688967680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lofter.com/tag/%E5%86%99%E7%9C%9F/date",
      "title": "写真 - 日榜 | LOFTER",
      "type": "feed",
      "url": "rsshub://lofter/tag/%E5%86%99%E7%9C%9F/date"
    }
  ]
}
```
