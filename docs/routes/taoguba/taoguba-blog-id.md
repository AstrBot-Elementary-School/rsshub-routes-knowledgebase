# 淘股吧 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `taoguba`
- Namespace Name: `淘股吧`
- Route Path: `/taoguba/blog/:id`
- Route Name: `用户博客`
- Example: `/taoguba/blog/252069`
- URL: `tgb.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 博客 id，可在对应博客页中找到


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
  - `tgb.cn/blog/:id`
  - `tgb.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/taoguba/blog/252069",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 712,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户博客",
  "parameters": {
    "id": "博客 id，可在对应博客页中找到"
  },
  "path": "/blog/:id",
  "radar": [
    {
      "source": [
        "tgb.cn/blog/:id",
        "tgb.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "淘股吧幽兰行天下的博客,幽兰行天下为所有投资者提供股票、证券、金融、港股、行情、基金、实盘、期货等极具价值的实用参考信息。欢迎访问幽兰行天下淘股吧博客! - Powered by RSSHub",
      "errorAt": "2026-06-24T17:27:22.482Z",
      "errorMessage": "[GET] \"https://www.tgb.cn//a/2tKyjN7bOIE\": 404 Not Found\n[GET] \"https://www.tgb.cn//a/2tyTI2mqwFl\": 404 Not Found\n",
      "id": "69384991748864007",
      "image": "https://image.tgb.cn/img/user_icon_60.png_80wh.png",
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/blog/523494",
      "title": "淘股吧 - 幽兰行天下",
      "type": "feed",
      "url": "rsshub://taoguba/blog/523494"
    },
    {
      "description": "淘股吧湖南人的博客,湖南人为所有投资者提供股票、证券、金融、港股、行情、基金、实盘、期货等极具价值的实用参考信息。欢迎访问湖南人淘股吧博客! - Powered by RSSHub",
      "errorAt": "2026-06-24T19:17:56.818Z",
      "errorMessage": "[GET] \"https://www.tgb.cn//a/2tR2UnZgD9B\": 404 Not Found\n[GET] \"https://www.tgb.cn//a/2tR2UnZgD9B\": 404 Not Found\n",
      "id": "69384991748864006",
      "image": "https://image.tgb.cn/img/2016/02/02/bfi12304d7t6.jpg_80wh.png",
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/blog/444409",
      "title": "淘股吧 - 湖南人",
      "type": "feed",
      "url": "rsshub://taoguba/blog/444409"
    }
  ]
}
```
