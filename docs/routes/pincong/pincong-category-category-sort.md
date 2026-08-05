# 品葱 - 发现

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/pincong/category/:category?/:sort?`
- Route Name: `发现`
- Example: `/pincong/category/1/new`
- URL: `pincong.rocks`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新 | 推荐      | 热门 |
| ---- | --------- | ---- |
| new  | recommend | hot  |

## Parameters
- `category`: 分类，与官网分类 URL `category-` 后的数字对应，默认为全部
- `sort`: 排序方式，参数可见下表，默认为推荐


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 最新 | 推荐      | 热门 |\n| ---- | --------- | ---- |\n| new  | recommend | hot  |",
  "example": "/pincong/category/1/new",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "发现",
  "parameters": {
    "category": "分类，与官网分类 URL `category-` 后的数字对应，默认为全部",
    "sort": "排序方式，参数可见下表，默认为推荐"
  },
  "path": "/category/:category?/:sort?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "品葱 - 发现 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53908061985105939",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pincong.rocks/sort_type-new__category-1",
      "title": "品葱 - 发现",
      "type": "feed",
      "url": "rsshub://pincong/category/1/new"
    },
    {
      "description": "品葱 - 发现 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1183231996273229824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pincong.rocks/recommend-1__category-1/hot",
      "title": "品葱 - 发现",
      "type": "feed",
      "url": "rsshub://pincong/category/1%2Fhot"
    }
  ]
}
```
