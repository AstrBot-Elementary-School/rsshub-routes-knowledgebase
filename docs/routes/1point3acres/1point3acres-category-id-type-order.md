# 一亩三分地 - 标签

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/1point3acres/category/:id?/:type?/:order?`
- Route Name: `标签`
- Example: `/1point3acres/category/h1b`
- URL: `blog.1point3acres.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
::: tip
更多标签可以在 [标签列表](https://instant.1point3acres.com/tags) 中找到。
:::

分类

| 热门帖子 | 最新帖子 |
| -------- | -------- |
| hot      | new      |

排序方式

| 最新回复 | 最新发布 |
| -------- | -------- |
|          | post     |

## Parameters
- `id`: 标签 id，默认为全部
- `type`: 帖子分类, 见下表，默认为 hot，即热门帖子
- `order`: 排序方式，见下表，默认为空，即最新回复


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
  - `instant.1point3acres.com/section/:id`
  - `instant.1point3acres.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n更多标签可以在 [标签列表](https://instant.1point3acres.com/tags) 中找到。\n:::\n\n分类\n\n| 热门帖子 | 最新帖子 |\n| -------- | -------- |\n| hot      | new      |\n\n排序方式\n\n| 最新回复 | 最新发布 |\n| -------- | -------- |\n|          | post     |",
  "example": "/1point3acres/category/h1b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 46,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": "标签 id，默认为全部",
    "order": "排序方式，见下表，默认为空，即最新回复",
    "type": "帖子分类, 见下表，默认为 hot，即热门帖子"
  },
  "path": "/category/:id?/:type?/:order?",
  "radar": [
    {
      "source": [
        "instant.1point3acres.com/section/:id",
        "instant.1point3acres.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "一亩三分地 - 创业热门帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "119723709260963840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instant.1point3acres.com/category/%E5%88%9B%E4%B8%9A",
      "title": "一亩三分地 - 创业热门帖子",
      "type": "feed",
      "url": "rsshub://1point3acres/category/%E5%88%9B%E4%B8%9A"
    },
    {
      "description": "一亩三分地 - h1b热门帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55159696591377408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://instant.1point3acres.com/category/h1b",
      "title": "一亩三分地 - h1b热门帖子",
      "type": "feed",
      "url": "rsshub://1point3acres/category/h1b"
    }
  ]
}
```
