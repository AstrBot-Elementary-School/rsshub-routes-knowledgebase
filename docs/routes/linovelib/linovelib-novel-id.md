# 哔哩轻小说 - 小说更新

## Coverage
`index-only`

## Route
- Namespace: `linovelib`
- Namespace Name: `哔哩轻小说`
- Route Path: `/linovelib/novel/:id`
- Route Name: `小说更新`
- Example: `/linovelib/novel/2547`
- URL: `linovelib.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `misakicoca`
- Source Location: `novel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id，对应书架开始阅读 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/linovelib/novel/2547",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "novel.ts",
  "maintainers": [
    "misakicoca"
  ],
  "name": "小说更新",
  "parameters": {
    "id": "小说 id，对应书架开始阅读 URL 中找到"
  },
  "path": "/novel/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "欢迎来到实力至上主义的教室 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "171191130615603200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linovelib.com/novel/8/catalog",
      "title": "哩哔轻小说 - 欢迎来到实力至上主义的教室",
      "type": "feed",
      "url": "rsshub://linovelib/novel/8"
    },
    {
      "description": "败北女角太多了！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57803547274585088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.linovelib.com/novel/3095/catalog",
      "title": "哩哔轻小说 - 败北女角太多了！",
      "type": "feed",
      "url": "rsshub://linovelib/novel/3095"
    }
  ]
}
```
