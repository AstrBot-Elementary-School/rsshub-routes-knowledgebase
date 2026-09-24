# 雪球 - 用户收藏动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/favorite/:id`
- Route Name: `用户收藏动态`
- Example: `/xueqiu/favorite/8152922548`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `imlonghao`
- Source Location: `favorite.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


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
  - `xueqiu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/favorite/8152922548",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 62,
  "location": "favorite.ts",
  "maintainers": [
    "imlonghao"
  ],
  "name": "用户收藏动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/favorite/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "大道无形我有型 的雪球收藏动态 - Powered by RSSHub",
      "errorAt": "2026-05-22T17:41:26.911Z",
      "errorMessage": "[GET] \"https://xueqiu.com/favorites.json?userid=1247347556\": 400 Bad Request\n",
      "id": "59965365270185984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/1247347556",
      "title": "大道无形我有型 的雪球收藏动态",
      "type": "feed",
      "url": "rsshub://xueqiu/favorite/1247347556"
    },
    {
      "description": "陈达美股投资 的雪球收藏动态 - Powered by RSSHub",
      "errorAt": "2024-12-03T09:58:41.916Z",
      "errorMessage": "Remote Playwright WebSocket upgrade failed with HTTP 428\n",
      "id": "86391133411299328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/9598793634",
      "title": "陈达美股投资 的雪球收藏动态",
      "type": "feed",
      "url": "rsshub://xueqiu/favorite/9598793634"
    }
  ]
}
```
