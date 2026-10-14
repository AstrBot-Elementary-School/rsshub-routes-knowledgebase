# 豆瓣 - 读书论坛

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/:id/discussion`
- Route Name: `读书论坛`
- Example: `/douban/36328704/discussion`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `nightmare-mio`
- Source Location: `other/discussion.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 书本id;默认论坛文章使用"按回应时间排序",仅第一页文章


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
  - `book.douban.com/subject/:id/discussion`
- `target`: `/:id/discussion`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/36328704/discussion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "other/discussion.ts",
  "maintainers": [
    "nightmare-mio"
  ],
  "name": "读书论坛",
  "parameters": {
    "id": "书本id;默认论坛文章使用\"按回应时间排序\",仅第一页文章"
  },
  "path": "/:id/discussion",
  "radar": [
    {
      "source": [
        "book.douban.com/subject/:id/discussion"
      ],
      "target": "/:id/discussion"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "太白金星有点烦的论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73622068229947392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://book.douban.com/subject/36328704/discussion",
      "title": "太白金星有点烦的论坛",
      "type": "feed",
      "url": "rsshub://douban/36328704/discussion"
    }
  ]
}
```
