# 雪球 - 动态详情

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/status/:uid/:id`
- Route Name: `动态详情`
- Example: `/xueqiu/status/8152922548/409443228`
- URL: `xueqiu.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `ruesin`
- Source Location: `status.ts`
- Source Module: `_None_`

## Description
获取单条动态或专栏文章的完整内容（列表类路由的 description 只有截断预览，需要全文时用本路由按动态页 URL 逐条获取）。

## Parameters
- `uid`: 用户 id，可在动态页 URL 中找到
- `id`: 动态 id，可在动态页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/:uid/:id`
- `target`: `/status/:uid/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "获取单条动态或专栏文章的完整内容（列表类路由的 description 只有截断预览，需要全文时用本路由按动态页 URL 逐条获取）。",
  "example": "/xueqiu/status/8152922548/409443228",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "status.ts",
  "maintainers": [
    "ruesin"
  ],
  "name": "动态详情",
  "parameters": {
    "id": "动态 id，可在动态页 URL 中找到",
    "uid": "用户 id，可在动态页 URL 中找到"
  },
  "path": "/status/:uid/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/:uid/:id"
      ],
      "target": "/status/:uid/:id"
    }
  ],
  "topFeeds": [],
  "url": "xueqiu.com"
}
```
