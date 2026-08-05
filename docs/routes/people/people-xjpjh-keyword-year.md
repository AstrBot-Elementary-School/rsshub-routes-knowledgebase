# 人民网 - 习近平系列重要讲话

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/people/xjpjh/:keyword?/:year?`
- Route Name: `习近平系列重要讲话`
- Example: `/people/xjpjh`
- URL: `jhsjk.people.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `LogicJake`
- Source Location: `xjpjh.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，默认不填
- `year`: 年份，默认 all


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
  - `jhsjk.people.cn/`
- `target`: `/xjpjh`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/people/xjpjh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "xjpjh.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "习近平系列重要讲话",
  "parameters": {
    "keyword": "关键词，默认不填",
    "year": "年份，默认 all"
  },
  "path": "/xjpjh/:keyword?/:year?",
  "radar": [
    {
      "source": [
        "jhsjk.people.cn/"
      ],
      "target": "/xjpjh"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "习近平系列重要讲话-all-all - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "159914682433828881",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://jhsjk.people.cn/result?keywords=&year=0",
      "title": "习近平系列重要讲话-all-all",
      "type": "feed",
      "url": "rsshub://people/xjpjh"
    }
  ],
  "url": "jhsjk.people.cn"
}
```
