# 豆瓣 - 浏览发现分栏目

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/explore/column/:id`
- Route Name: `浏览发现分栏目`
- Example: `/douban/explore/column/2`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `other/explore-column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分栏目id


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/explore/column/2",
  "heat": 3,
  "location": "other/explore-column.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "浏览发现分栏目",
  "parameters": {
    "id": "分栏目id"
  },
  "path": "/explore/column/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "旅行-豆瓣发现 - Powered by RSSHub",
      "errorAt": "2024-11-05T09:41:38.827Z",
      "errorMessage": "[GET] \"https://www.douban.com/explore/column/2\": 403 Forbidden\n",
      "id": "68923387494636578",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/explore/column/2",
      "title": "旅行-豆瓣发现",
      "type": "feed",
      "url": "rsshub://douban/explore/column/2"
    }
  ]
}
```
