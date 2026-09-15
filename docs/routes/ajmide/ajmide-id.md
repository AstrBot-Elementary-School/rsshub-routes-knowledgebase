# 阿基米德 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `ajmide`
- Namespace Name: `阿基米德 FM`
- Route Path: `/ajmide/:id`
- Route Name: `播客`
- Example: `/ajmide/10603594`
- URL: `m.ajmide.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 播客 id，可以从播客页面 URL 中找到


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
    "multimedia"
  ],
  "example": "/ajmide/10603594",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 77,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "播客",
  "parameters": {
    "id": "播客 id，可以从播客页面 URL 中找到"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "全球华语音乐排行榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75392155030438912",
      "image": "https://img-ossimg-qn.ajmide.com/program/1IMu3m.png",
      "ownerUserId": null,
      "siteUrl": "https://m.ajmide.com/m/brand?id=10602753",
      "title": "全球华语音乐排行榜",
      "type": "feed",
      "url": "rsshub://ajmide/10602753"
    },
    {
      "description": "一些事一些情 - Powered by RSSHub",
      "errorAt": "2026-04-10T07:47:26.522Z",
      "errorMessage": "Cannot read properties of undefined (reading '0')\nCannot read properties of undefined (reading '0')\n",
      "id": "58782515556028416",
      "image": "https://img-ossimg-qn.ajmide.com/c_up/571ef0d2839d34522c55d628306bb971.jpg@150w_150h_1e_1c",
      "ownerUserId": null,
      "siteUrl": "https://m.ajmide.com/m/brand?id=10603594",
      "title": "一些事一些情",
      "type": "feed",
      "url": "rsshub://ajmide/10603594"
    }
  ],
  "view": 4
}
```
