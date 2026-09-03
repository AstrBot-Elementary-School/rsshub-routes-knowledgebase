# Readhub - 分类

## Coverage
`index-only`

## Route
- Namespace: `readhub`
- Namespace Name: `Readhub`
- Route Path: `/readhub/:category?`
- Route Name: `分类`
- Example: `/readhub`
- URL: `readhub.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `WhiteWorld, nczitzk, Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 热门话题 | 科技动态 | 医疗产业 | 财经快讯           |
| -------- | -------- | -------- | ------------------ |
|          | news     | medical  | financial\_express |

## Parameters
- `category`: 分类，见下表，默认为热门话题


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 热门话题 | 科技动态 | 医疗产业 | 财经快讯           |\n| -------- | -------- | -------- | ------------------ |\n|          | news     | medical  | financial\\_express |",
  "example": "/readhub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 540,
  "location": "index.ts",
  "maintainers": [
    "WhiteWorld",
    "nczitzk",
    "Fatpandac"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为热门话题"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "每天三分钟的科技资讯聚合阅读 - Powered by RSSHub",
      "errorAt": "2026-09-02T08:08:27.572Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 55939235463397379",
      "id": "55939235463397379",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://readhub.cn/",
      "title": "Readhub - AI 与科技资讯热点追踪 - 无码科技 - 热门话题",
      "type": "feed",
      "url": "rsshub://readhub"
    },
    {
      "description": "24 小时热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77974917410779136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://readhub.cn/hot",
      "title": "Readhub 24 小时热榜 - 排行榜",
      "type": "feed",
      "url": "rsshub://readhub/hot"
    }
  ]
}
```
