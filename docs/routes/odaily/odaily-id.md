# Odaily 星球日报 - 文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/:id?`
- Route Name: `文章`
- Example: `/odaily`
- URL: `0daily.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
| 最新 | 新品 | DeFi | NFT | 存储 | 波卡 | 行情 | 活动 |
| ---- | ---- | ---- | --- | ---- | ---- | ---- | ---- |
| 280  | 333  | 331  | 334 | 332  | 330  | 297  | 296  |

## Parameters
- `id`: id，见下表，默认为最新


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
  - `0daily.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新 | 新品 | DeFi | NFT | 存储 | 波卡 | 行情 | 活动 |\n| ---- | ---- | ---- | --- | ---- | ---- | ---- | ---- |\n| 280  | 333  | 331  | 334 | 332  | 330  | 297  | 296  |",
  "example": "/odaily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 112,
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "文章",
  "parameters": {
    "id": "id，见下表，默认为最新"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "0daily.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T19:29:20.919Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://www.odaily.news/api/pp/api/app-front/feed-stream?feed_id=280&b_id=&per_page=25\": 404 Not Found\n",
      "id": "56204588915011597",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily"
    },
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T20:18:06.864Z",
      "errorMessage": "[GET] \"https://www.odaily.news/api/pp/api/app-front/feed-stream?feed_id=280&b_id=&per_page=25\": 404 Not Found\n",
      "id": "85203770103696384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/280"
    }
  ],
  "url": "0daily.com/"
}
```
