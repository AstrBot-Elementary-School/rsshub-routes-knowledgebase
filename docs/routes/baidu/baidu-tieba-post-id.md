# 百度 - 帖子动态

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/post/:id`
- Route Name: `帖子动态`
- Example: `/baidu/tieba/post/686961453`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `u3u, FlanChanXwO`
- Source Location: `tieba/post.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 帖子 ID


## Features
- `requireConfig`: [{"description": "百度 cookie 值，用于需要登录的贴吧页面", "name": "BAIDU_COOKIE", "optional": false}]
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tieba.baidu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/baidu/tieba/post/686961453",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "百度 cookie 值，用于需要登录的贴吧页面",
        "name": "BAIDU_COOKIE",
        "optional": false
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "tieba/post.tsx",
  "maintainers": [
    "u3u",
    "FlanChanXwO"
  ],
  "name": "帖子动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": [
    "/tieba/post/:id",
    "/tieba/post/lz/:id"
  ],
  "radar": [
    {
      "source": [
        "tieba.baidu.com/p/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "回复：【推书】推书＋记录我看过的无男主的最新回复 - Powered by RSSHub",
      "errorAt": "2025-11-02T01:15:28.587Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/8993611867?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "116742777462552576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/8993611867?see_lz=0",
      "title": "回复：【推书】推书＋记录我看过的无男主",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/8993611867"
    },
    {
      "description": "回复：注册求踢帖的最新回复 - Powered by RSSHub",
      "errorAt": "2026-06-08T16:51:35.220Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/p/9270867907?see_lz=0&pn=7000000&ajax=1\": 403 Forbidden\n",
      "id": "115346513587038208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/p/9270867907?see_lz=0",
      "title": "回复：注册求踢帖",
      "type": "feed",
      "url": "rsshub://baidu/tieba/post/9270867907"
    }
  ]
}
```
