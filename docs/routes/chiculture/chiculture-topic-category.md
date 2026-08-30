# 通識・現代中國 - 議題熱話

## Coverage
`index-only`

## Route
- Namespace: `chiculture`
- Namespace Name: `通識・現代中國`
- Route Path: `/chiculture/topic/:category?`
- Route Name: `議題熱話`
- Example: `/chiculture/topic`
- URL: `chiculture.org.hk`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
| 全部 | 現代中國 | 今日香港 | 全球化 | 一周時事通識 |
| ---- | -------- | -------- | ------ | ------------ |
|      | 76       | 479      | 480    | 379          |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  "description": "| 全部 | 現代中國 | 今日香港 | 全球化 | 一周時事通識 |\n| ---- | -------- | -------- | ------ | ------------ |\n|      | 76       | 479      | 480    | 379          |",
  "example": "/chiculture/topic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "議題熱話",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/topic/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "議題熱話 | 通識·現代中國 - Powered by RSSHub",
      "errorAt": "2026-05-04T04:46:56.217Z",
      "errorMessage": "[GET] \"https://ls.chiculture.org.hk/api/general-listing?lang=zh-hant&type=ssrh&category=&page=1\": 403 Forbidden\n",
      "id": "55135298544042029",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ls.chiculture.org.hk/tc/hot-topics",
      "title": "議題熱話 | 通識·現代中國",
      "type": "feed",
      "url": "rsshub://chiculture/topic"
    }
  ]
}
```
