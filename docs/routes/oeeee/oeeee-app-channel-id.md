# 南方都市报 - 南都客户端（按南都号 ID）

## Coverage
`index-only`

## Route
- Namespace: `oeeee`
- Namespace Name: `南方都市报`
- Route Path: `/oeeee/app/channel/:id`
- Route Name: `南都客户端（按南都号 ID）`
- Example: `/oeeee/app/channel/50`
- URL: `oeeee.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `app/channel.ts`
- Source Module: `_None_`

## Description
南都号的 UID 可通过 `m.mp.oeeee.com` 下的文章页面获取。点击文章上方的南都号头像，进入该南都号的个人主页，即可从 url 中获取。

## Parameters
- `id`: 南都号 ID


## Features
- `requireConfig`: false
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
    "traditional-media"
  ],
  "description": "南都号的 UID 可通过 `m.mp.oeeee.com` 下的文章页面获取。点击文章上方的南都号头像，进入该南都号的个人主页，即可从 url 中获取。",
  "example": "/oeeee/app/channel/50",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "app/channel.ts",
  "maintainers": [
    "TimWu007"
  ],
  "name": "南都客户端（按南都号 ID）",
  "parameters": {
    "id": "南都号 ID"
  },
  "path": "/app/channel/:id",
  "topFeeds": [
    {
      "description": "南方都市报客户端 - 南都广州 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87329418896513044",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.mp.oeeee.com/u/50.html",
      "title": "南方都市报客户端 - 南都广州",
      "type": "feed",
      "url": "rsshub://oeeee/app/channel/50"
    }
  ]
}
```
