# 电动邦 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `diandong`
- Namespace Name: `电动邦`
- Route Path: `/diandong/news/:cate?`
- Route Name: `资讯`
- Example: `/diandong/news`
- URL: `diandong.com/news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
分类

| 推荐 | 新车 | 导购 | 试驾 | 用车 | 技术 | 政策 | 行业 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 0    | 29   | 61   | 30   | 75   | 22   | 24   | 23   |

## Parameters
- `cate`: 分类，见下表，默认为推荐


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
  - `diandong.com/news`
- `target`: `/news/:cate`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "分类\n\n| 推荐 | 新车 | 导购 | 试驾 | 用车 | 技术 | 政策 | 行业 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 0    | 29   | 61   | 30   | 75   | 22   | 24   | 23   |",
  "example": "/diandong/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 183,
  "location": "news.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "资讯",
  "parameters": {
    "cate": "分类，见下表，默认为推荐"
  },
  "path": "/news/:cate?",
  "radar": [
    {
      "source": [
        "diandong.com/news"
      ],
      "target": "/news/:cate"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "电动邦 - 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55806647143790592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.diandong.com/news",
      "title": "电动邦 - 推荐",
      "type": "feed",
      "url": "rsshub://diandong/news"
    },
    {
      "description": "电动邦 - 新车 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74064527242090496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.diandong.com/news",
      "title": "电动邦 - 新车",
      "type": "feed",
      "url": "rsshub://diandong/news/29"
    }
  ],
  "url": "diandong.com/news"
}
```
