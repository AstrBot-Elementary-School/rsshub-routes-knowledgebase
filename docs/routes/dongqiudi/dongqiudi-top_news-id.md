# 懂球帝 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/top_news/:id?`
- Route Name: `新闻`
- Example: `/dongqiudi/top_news/1`
- URL: `m.dongqiudi.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HendricksZheng`
- Source Location: `top-news.ts`
- Source Module: `_None_`

## Description
| 头条 | 深度 | 闲情 | D 站 | 中超 | 国际 | 英超 | 西甲 | 意甲 | 德甲 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1    | 55   | 37   | 219  | 56   | 120  | 3    | 5    | 4    | 6    |

## Parameters
- `id`: 类别 id，不填默认头条新闻


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
  - `m.dongqiudi.com/home/:id`
- `target`: `/top_news/:id`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "description": "| 头条 | 深度 | 闲情 | D 站 | 中超 | 国际 | 英超 | 西甲 | 意甲 | 德甲 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 1    | 55   | 37   | 219  | 56   | 120  | 3    | 5    | 4    | 6    |",
  "example": "/dongqiudi/top_news/1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 376,
  "location": "top-news.ts",
  "maintainers": [
    "HendricksZheng"
  ],
  "name": "新闻",
  "parameters": {
    "id": "类别 id，不填默认头条新闻"
  },
  "path": "/top_news/:id?",
  "radar": [
    {
      "source": [
        "m.dongqiudi.com/home/:id"
      ],
      "target": "/top_news/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "懂球帝 - 头条 - Powered by RSSHub",
      "errorAt": "2026-09-02T07:44:53.408Z",
      "errorMessage": "Failed to fetch\n",
      "id": "73989204856510464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/articlesList/1",
      "title": "懂球帝 - 头条",
      "type": "feed",
      "url": "rsshub://dongqiudi/top_news"
    },
    {
      "description": "懂球帝 - 深度 - Powered by RSSHub",
      "errorAt": "2026-09-02T07:39:04.868Z",
      "errorMessage": "Failed to fetch\n",
      "id": "67550300258611200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dongqiudi.com/articlesList/55",
      "title": "懂球帝 - 深度",
      "type": "feed",
      "url": "rsshub://dongqiudi/top_news/55"
    }
  ]
}
```
