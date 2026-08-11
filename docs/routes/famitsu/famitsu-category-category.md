# ファミ通 - Category

## Coverage
`index-only`

## Route
- Namespace: `famitsu`
- Namespace Name: `ファミ通`
- Route Path: `/famitsu/category/:category?`
- Route Name: `Category`
- Example: `/famitsu/category/new-article`
- URL: `famitsu.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `category.tsx`
- Source Module: `_None_`

## Description
| 新着        | Switch | PS5 | PS4 | PC ゲーム | ニュース | 動画   | 特集・企画記事  | インタビュー | 取材・リポート | レビュー | インディーゲーム |
| ----------- | ------ | --- | --- | --------- | -------- | ------ | --------------- | ------------ | -------------- | -------- | ---------------- |
| new-article | switch | ps5 | ps4 | pc-game   | news     | videos | special-article | interview    | event-report   | review   | indie-game       |

## Parameters
- `category`: Category, see table below, `new-article` by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.famitsu.com/category/:category/page/1`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新着        | Switch | PS5 | PS4 | PC ゲーム | ニュース | 動画   | 特集・企画記事  | インタビュー | 取材・リポート | レビュー | インディーゲーム |\n| ----------- | ------ | --- | --- | --------- | -------- | ------ | --------------- | ------------ | -------------- | -------- | ---------------- |\n| new-article | switch | ps5 | ps4 | pc-game   | news     | videos | special-article | interview    | event-report   | review   | indie-game       |",
  "example": "/famitsu/category/new-article",
  "heat": 42,
  "location": "category.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, see table below, `new-article` by default"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "www.famitsu.com/category/:category/page/1"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "新着の最新記事 | ゲーム・エンタメ最新情報のファミ通.com - Powered by RSSHub",
      "errorAt": "2026-03-26T04:42:27.495Z",
      "errorMessage": "Unhandle type: ARTICLE_AD\n",
      "id": "73943720962894848",
      "image": "https://www.famitsu.com/img/1812/favicons/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.famitsu.com/category/new-article/page/1",
      "title": "新着の最新記事 | ゲーム・エンタメ最新情報のファミ通.com",
      "type": "feed",
      "url": "rsshub://famitsu/category/new-article"
    },
    {
      "description": "新着の最新記事 | ゲーム・エンタメ最新情報のファミ通.com - Powered by RSSHub",
      "errorAt": "2026-03-26T05:02:18.083Z",
      "errorMessage": "Unhandle type: ARTICLE_AD\n",
      "id": "172851805999353856",
      "image": "https://www.famitsu.com/img/1812/favicons/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.famitsu.com/category/new-article/page/1",
      "title": "新着の最新記事 | ゲーム・エンタメ最新情報のファミ通.com",
      "type": "feed",
      "url": "rsshub://famitsu/category"
    }
  ]
}
```
