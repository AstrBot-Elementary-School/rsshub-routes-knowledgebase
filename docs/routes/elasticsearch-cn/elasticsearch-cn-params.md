# Elastic 中文社区 - 发现

## Coverage
`index-only`

## Route
- Namespace: `elasticsearch-cn`
- Namespace Name: `Elastic 中文社区`
- Route Path: `/elasticsearch-cn/:params?`
- Route Name: `发现`
- Example: `/elasticsearch-cn`
- URL: `elasticsearch.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
如 [Elasticsearch 最新](https://elasticsearch.cn/category-2) 的 URL 为 `https://elasticsearch.cn/category-2`，则分类参数处填写 `category-2`，最后得到路由地址 [`/elasticsearch-cn/category-2`](https://rsshub.app/elasticsearch-cn/category-2)。

又如 [求职招聘 30 天热门](https://elasticsearch.cn/sort_type-hot____category-12__day-30) 的 URL 为 `https://elasticsearch.cn/sort_type-hot____category-12__day-30`，则分类参数处填写 `sort_type-hot____category-12__day-30`，最后得到路由地址 [`/elasticsearch-cn/sort_type-hot____category-12__day-30`](https://rsshub.app/elasticsearch-cn/sort_type-hot____category-12__day-30)。

## Parameters
- `params`: 分类，可在对应分类页 URL 中找到


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
  - `elasticsearch.cn/:params`
  - `elasticsearch.cn/`
- `target`: `/:params`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "如 [Elasticsearch 最新](https://elasticsearch.cn/category-2) 的 URL 为 `https://elasticsearch.cn/category-2`，则分类参数处填写 `category-2`，最后得到路由地址 [`/elasticsearch-cn/category-2`](https://rsshub.app/elasticsearch-cn/category-2)。\n\n又如 [求职招聘 30 天热门](https://elasticsearch.cn/sort_type-hot____category-12__day-30) 的 URL 为 `https://elasticsearch.cn/sort_type-hot____category-12__day-30`，则分类参数处填写 `sort_type-hot____category-12__day-30`，最后得到路由地址 [`/elasticsearch-cn/sort_type-hot____category-12__day-30`](https://rsshub.app/elasticsearch-cn/sort_type-hot____category-12__day-30)。",
  "example": "/elasticsearch-cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 60,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "发现",
  "parameters": {
    "params": "分类，可在对应分类页 URL 中找到"
  },
  "path": "/:params?",
  "radar": [
    {
      "source": [
        "elasticsearch.cn/:params",
        "elasticsearch.cn/"
      ],
      "target": "/:params"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "搜索客，搜索人自己的社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64113341498592256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://elasticsearch.cn/",
      "title": "搜索客，搜索人自己的社区",
      "type": "feed",
      "url": "rsshub://elasticsearch-cn"
    },
    {
      "description": "Elasticsearch - 搜索客，搜索人自己的社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75540489377172480",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://elasticsearch.cn/category-2",
      "title": "Elasticsearch - 搜索客，搜索人自己的社区",
      "type": "feed",
      "url": "rsshub://elasticsearch-cn/category-2"
    }
  ]
}
```
