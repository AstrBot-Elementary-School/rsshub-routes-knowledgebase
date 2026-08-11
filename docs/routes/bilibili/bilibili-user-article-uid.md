# 哔哩哔哩 bilibili - UP 主图文

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/article/:uid`
- Route Name: `UP 主图文`
- Example: `/bilibili/user/article/334958638`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lengthmin, Qixingchen, hyoban`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到


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
  - `space.bilibili.com/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/article/334958638",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 886,
  "location": "article.ts",
  "maintainers": [
    "lengthmin",
    "Qixingchen",
    "hyoban"
  ],
  "name": "UP 主图文",
  "parameters": {
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/article/:uid",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "技术爬爬虾 的 bilibili 图文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78446399642487808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842/article",
      "title": "技术爬爬虾 的 bilibili 图文",
      "type": "feed",
      "url": "rsshub://bilibili/user/article/316183842"
    },
    {
      "description": "undefined 的 bilibili 图文 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55126637717323776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/57276677/article",
      "title": "undefined 的 bilibili 图文",
      "type": "feed",
      "url": "rsshub://bilibili/user/article/57276677"
    }
  ]
}
```
