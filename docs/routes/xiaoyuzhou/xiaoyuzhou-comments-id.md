# 小宇宙 - 单集热门评论

## Coverage
`index-only`

## Route
- Namespace: `xiaoyuzhou`
- Namespace Name: `小宇宙`
- Route Path: `/xiaoyuzhou/comments/:id`
- Route Name: `单集热门评论`
- Example: `/xiaoyuzhou/comments/5f573de183c34e85ddce9c8b`
- URL: `xiaoyuzhoufm.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `comments.tsx`
- Source Module: `_None_`

## Description
订阅单集公开网页展示的热门评论。网页只展示部分热门评论，无法保证包含全部评论或每条最新评论。

## Parameters
- `id`: 单集 id，可在单集页面 URL 中找到


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
  - `xiaoyuzhoufm.com/episode/:id`
- `target`: `/comments/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "订阅单集公开网页展示的热门评论。网页只展示部分热门评论，无法保证包含全部评论或每条最新评论。",
  "example": "/xiaoyuzhou/comments/5f573de183c34e85ddce9c8b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "comments.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "单集热门评论",
  "parameters": {
    "id": "单集 id，可在单集页面 URL 中找到"
  },
  "path": "/comments/:id",
  "radar": [
    {
      "source": [
        "xiaoyuzhoufm.com/episode/:id"
      ],
      "target": "/comments/:id"
    }
  ],
  "topFeeds": []
}
```
