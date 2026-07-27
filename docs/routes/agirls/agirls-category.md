# 电獭少女 - 分类

## Coverage
`index-only`

## Route
- Namespace: `agirls`
- Namespace Name: `电獭少女`
- Route Path: `/agirls/:category?`
- Route Name: `分类`
- Example: `/agirls/app`
- URL: `agirls.aotter.net`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `z-index.ts`
- Source Module: `_None_`

## Description
| App 评测 | 手机开箱 | 笔电开箱 | 3C 周边     | 教学小技巧 | 科技情报 |
| -------- | -------- | -------- | ----------- | ---------- | -------- |
| app      | phone    | computer | accessories | tutorial   | techlife |

## Parameters
- `category`: 分类，默认为最新文章，可在对应主题页的 URL 中找到，下表仅列出部分


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
  - `agirls.aotter.net/posts/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| App 评测 | 手机开箱 | 笔电开箱 | 3C 周边     | 教学小技巧 | 科技情报 |\n| -------- | -------- | -------- | ----------- | ---------- | -------- |\n| app      | phone    | computer | accessories | tutorial   | techlife |",
  "example": "/agirls/app",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 168,
  "location": "z-index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，默认为最新文章，可在对应主题页的 URL 中找到，下表仅列出部分"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "agirls.aotter.net/posts/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "電獺少女是一群女生組成的團隊，主要分享敗家心得、App軟體介紹、科技快訊及一些新3C酷品、周邊商品的介紹和測試、iPhone手機、Android手機教學，當然還有女孩的生活吃喝玩樂紀錄，歡迎洽談合作或產品測試！聰明網址：aottergirls.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74062803265350656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agirls.aotter.net/posts",
      "title": "最新文章- 電獺少女：女孩的科技日常-App、科技酷品、生活與美食",
      "type": "feed",
      "url": "rsshub://agirls"
    },
    {
      "description": "電獺少女是一群女生組成的團隊，主要分享敗家心得、App軟體介紹、科技快訊及一些新3C酷品、周邊商品的介紹和測試、iPhone手機、Android手機教學，當然還有女孩的生活吃喝玩樂紀錄，歡迎洽談合作或產品測試！聰明網址：aottergirls.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65288670568498176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://agirls.aotter.net/posts/app",
      "title": "分類 App 應用 最新文章- 電獺少女：女孩的科技日常-App、科技酷品、生活與美食",
      "type": "feed",
      "url": "rsshub://agirls/app"
    }
  ]
}
```
