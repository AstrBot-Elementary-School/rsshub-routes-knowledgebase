# 風傳媒 - 分类

## Coverage
`index-only`

## Route
- Namespace: `storm`
- Namespace Name: `風傳媒`
- Route Path: `/storm/:category?/:id?`
- Route Name: `分类`
- Example: `/storm`
- URL: `storm.mg`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 新聞總覽 | 地方新聞      | 歷史頻道 | 評論總覽    |
| -------- | ------------- | -------- | ----------- |
| articles | localarticles | history  | all-comment |

::: tip
支持形如 `https://www.storm.mg/category/118` 的路由，即 [`/storm/category/118`](https://rsshub.app/storm/category/118)

支持形如 `https://www.storm.mg/localarticle-category/s149845` 的路由，即 [`/storm/localarticle-category/s149845`](https://rsshub.app/storm/localarticle-category/s149845)
:::

## Parameters
- `category`: 分类，见下表，默认为新聞總覽
- `id`: 子分类 ID，可在 URL 中找到


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
  - `storm.mg/:category/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新聞總覽 | 地方新聞      | 歷史頻道 | 評論總覽    |\n| -------- | ------------- | -------- | ----------- |\n| articles | localarticles | history  | all-comment |\n\n::: tip\n支持形如 `https://www.storm.mg/category/118` 的路由，即 [`/storm/category/118`](https://rsshub.app/storm/category/118)\n\n支持形如 `https://www.storm.mg/localarticle-category/s149845` 的路由，即 [`/storm/localarticle-category/s149845`](https://rsshub.app/storm/localarticle-category/s149845)\n:::",
  "example": "/storm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 40,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为新聞總覽",
    "id": "子分类 ID，可在 URL 中找到"
  },
  "path": "/:category?/:id?",
  "radar": [
    {
      "source": [
        "storm.mg/:category/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "新聞總覽｜風傳媒 - Powered by RSSHub",
      "errorAt": "2025-05-13T21:15:14.517Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "67077327876919319",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.storm.mg/articles",
      "title": "新聞總覽｜風傳媒",
      "type": "feed",
      "url": "rsshub://storm"
    }
  ]
}
```
