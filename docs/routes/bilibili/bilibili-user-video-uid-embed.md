# 哔哩哔哩 bilibili - UP 主投稿

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/video/:uid/:embed?`
- Route Name: `UP 主投稿`
- Example: `/bilibili/user/video/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, Konano, pseudoyu`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
- `target`: `/user/video/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/bilibili/user/video/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 179419,
  "location": "video.ts",
  "maintainers": [
    "DIYgod",
    "Konano",
    "pseudoyu"
  ],
  "name": "UP 主投稿",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/video/:uid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "影视飓风 的 bilibili 空间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55653085540614144",
      "image": "https://i0.hdslb.com/bfs/face/c1733474892caa45952b2c09a89323157df7129a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/946974",
      "title": "影视飓风 的 bilibili 空间",
      "type": "feed",
      "url": "rsshub://bilibili/user/video/946974"
    },
    {
      "description": "技术爬爬虾 的 bilibili 空间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58463916731079680",
      "image": "https://i0.hdslb.com/bfs/face/333b1b477f1ac1b40091b70afcfd4444e646a7d3.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842",
      "title": "技术爬爬虾 的 bilibili 空间",
      "type": "feed",
      "url": "rsshub://bilibili/user/video/316183842"
    }
  ],
  "view": 3
}
```
