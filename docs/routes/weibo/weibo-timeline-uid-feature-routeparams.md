# 微博 - 个人时间线

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/timeline/:uid/:feature?/:routeParams?`
- Route Name: `个人时间线`
- Example: `/weibo/timeline/3306934123`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `zytomorrow, DIYgod, Rongronggg9`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
::: warning
需要对应用户打开页面进行授权生成 token 才能生成内容

自部署需要申请并配置微博 key，具体见部署文档
:::

## Parameters
- `uid`: 用户的uid
- `feature`: 过滤类型ID，0：全部、1：原创、2：图片、3：视频、4：音乐，默认为0。
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_APP_KEY"}, {"description": "", "name": "WEIBO_REDIRECT_URL"}]
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
  "description": "::: warning\n需要对应用户打开页面进行授权生成 token 才能生成内容\n\n自部署需要申请并配置微博 key，具体见部署文档\n:::",
  "example": "/weibo/timeline/3306934123",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_APP_KEY"
      },
      {
        "description": "",
        "name": "WEIBO_REDIRECT_URL"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 19,
  "location": "timeline.ts",
  "maintainers": [
    "zytomorrow",
    "DIYgod",
    "Rongronggg9"
  ],
  "name": "个人时间线",
  "parameters": {
    "feature": "过滤类型ID，0：全部、1：原创、2：图片、3：视频、4：音乐，默认为0。",
    "routeParams": "额外参数；请参阅上面的说明和表格",
    "uid": "用户的uid"
  },
  "path": "/timeline/:uid/:feature?/:routeParams?",
  "topFeeds": [
    {
      "description": "undefined - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70642816621002752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://weibo/timeline/3306934123/0"
    },
    {
      "description": "undefined - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "188856372339459072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://weibo/timeline/5058738299"
    }
  ]
}
```
