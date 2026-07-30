# 起点 - 作品章节

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/qidian/chapter/:id`
- Route Name: `作品章节`
- Example: `/qidian/chapter/1010400217`
- URL: `qidian.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `fuzy112, pseudoyu`
- Source Location: `chapter.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `book.qidian.com/info/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/chapter/1010400217",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 197,
  "location": "chapter.ts",
  "maintainers": [
    "fuzy112",
    "pseudoyu"
  ],
  "name": "作品章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "book.qidian.com/info/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "起点 宿命之环 - Powered by RSSHub",
      "errorAt": "2026-07-27T22:46:21.459Z",
      "errorMessage": "Failed to fetch\n",
      "id": "57278498453365760",
      "image": "https:https://imgservices-1252317822.image.myqcloud.com/coco/s06272023/b412ecf2.e7k0cq.png",
      "ownerUserId": null,
      "siteUrl": "https://book.qidian.com/info/1036370336",
      "title": "起点 宿命之环",
      "type": "feed",
      "url": "rsshub://qidian/chapter/1036370336"
    },
    {
      "description": "起点 剑来 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59200495544733696",
      "image": "https:https://imgservices-1252317822.image.myqcloud.com/coco/s06272023/b412ecf2.e7k0cq.png",
      "ownerUserId": null,
      "siteUrl": "https://book.qidian.com/info/1012261200",
      "title": "起点 剑来",
      "type": "feed",
      "url": "rsshub://qidian/chapter/1012261200"
    }
  ],
  "view": 5
}
```
