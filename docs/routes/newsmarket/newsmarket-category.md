# 上下游 News&Market - 分類

## Coverage
`index-only`

## Route
- Namespace: `newsmarket`
- Namespace Name: `上下游 News&Market`
- Route Path: `/newsmarket/:category?`
- Route Name: `分類`
- Example: `/newsmarket`
- URL: `newsmarket.com.tw`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 時事。政策  | 食安        | 新知      | 愛地方       | 種好田       | 好吃。好玩    |
| ----------- | ----------- | --------- | ------------ | ------------ | ------------- |
| news-policy | food-safety | knowledge | country-life | good-farming | good-food-fun |

| 食農教育       | 人物               | 漁業。畜牧           | 綠生活。國際        | 評論    |
| -------------- | ------------------ | -------------------- | ------------------- | ------- |
| food-education | people-and-history | raising-and-breeding | living-green-travel | opinion |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `newsmarket.com.tw/blog/category/:category`
  - `newsmarket.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 時事。政策  | 食安        | 新知      | 愛地方       | 種好田       | 好吃。好玩    |\n| ----------- | ----------- | --------- | ------------ | ------------ | ------------- |\n| news-policy | food-safety | knowledge | country-life | good-farming | good-food-fun |\n\n| 食農教育       | 人物               | 漁業。畜牧           | 綠生活。國際        | 評論    |\n| -------------- | ------------------ | -------------------- | ------------------- | ------- |\n| food-education | people-and-history | raising-and-breeding | living-green-travel | opinion |",
  "example": "/newsmarket",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分類",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "newsmarket.com.tw/blog/category/:category",
        "newsmarket.com.tw/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上下游新聞 | 專注於台灣農業、食物、環境等公共議題的獨立媒體 - Powered by RSSHub",
      "errorAt": "2026-07-19T13:53:07.195Z",
      "errorMessage": "[GET] \"https://www.newsmarket.com.tw\": 403 Forbidden\n",
      "id": "69287393138986001",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.newsmarket.com.tw/",
      "title": "上下游新聞 | 專注於台灣農業、食物、環境等公共議題的獨立媒體",
      "type": "feed",
      "url": "rsshub://newsmarket"
    },
    {
      "description": "新知 | 上下游新聞 - Powered by RSSHub",
      "errorAt": "2026-07-19T11:12:09.134Z",
      "errorMessage": "[GET] \"https://www.newsmarket.com.tw/blog/category/:knowledge\": 403 Forbidden\n",
      "id": "111389962417871873",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.newsmarket.com.tw/blog/category/:knowledge",
      "title": "新知 | 上下游新聞",
      "type": "feed",
      "url": "rsshub://newsmarket/:knowledge"
    }
  ]
}
```
