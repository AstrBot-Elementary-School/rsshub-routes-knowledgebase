# 一亩三分地 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/1point3acres/thread/:type?/:order?`
- Route Name: `帖子`
- Example: `/1point3acres/thread/hot`
- URL: `instant.1point3acres.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `IvanWng97, DIYgod, nczitzk`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
分类

| 热门帖子 | 最新帖子 |
| -------- | -------- |
| hot      | new      |

排序方式

| 最新回复 | 最新发布 |
| -------- | -------- |
|          | post     |

## Parameters
- `type`: 帖子分类, 见下表，默认为 hot，即热门帖子
- `order`: 排序方式，见下表，默认为空，即最新回复


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "分类\n\n| 热门帖子 | 最新帖子 |\n| -------- | -------- |\n| hot      | new      |\n\n排序方式\n\n| 最新回复 | 最新发布 |\n| -------- | -------- |\n|          | post     |",
  "example": "/1point3acres/thread/hot",
  "heat": 168,
  "location": "thread.ts",
  "maintainers": [
    "IvanWng97",
    "DIYgod",
    "nczitzk"
  ],
  "name": "帖子",
  "parameters": {
    "order": "排序方式，见下表，默认为空，即最新回复",
    "type": "帖子分类, 见下表，默认为 hot，即热门帖子"
  },
  "path": "/thread/:type?/:order?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "一亩三分地 - 热门帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55133630460506172",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instant.1point3acres.com/",
      "title": "一亩三分地 - 热门帖子",
      "type": "feed",
      "url": "rsshub://1point3acres/thread/hot"
    },
    {
      "description": "一亩三分地 - 热门帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150085572058846208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instant.1point3acres.com/",
      "title": "一亩三分地 - 热门帖子",
      "type": "feed",
      "url": "rsshub://1point3acres/thread"
    }
  ],
  "url": "instant.1point3acres.com/"
}
```
