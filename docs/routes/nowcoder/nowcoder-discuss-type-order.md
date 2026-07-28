# 牛客网 - 讨论区

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/nowcoder/discuss/:type/:order`
- Route Name: `讨论区`
- Example: `/nowcoder/discuss/2/4`
- URL: `nowcoder.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `LogicJake`
- Source Location: `discuss.ts`
- Source Module: `_None_`

## Description
| 最新回复 | 最新发表 | 最新 | 精华 |
| -------- | -------- | ---- | ---- |
| 0        | 3        | 1    | 4    |

## Parameters
- `type`: 讨论区分区id 在 URL 中可以找到
- `order`: 排序方式


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
    "bbs"
  ],
  "description": "| 最新回复 | 最新发表 | 最新 | 精华 |\n| -------- | -------- | ---- | ---- |\n| 0        | 3        | 1    | 4    |",
  "example": "/nowcoder/discuss/2/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "discuss.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "讨论区",
  "parameters": {
    "order": "排序方式",
    "type": "讨论区分区id 在 URL 中可以找到"
  },
  "path": "/discuss/:type/:order",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-26T04:23:58.101Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "149642094386478112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://nowcoder/discuss/2/4"
    },
    {
      "description": null,
      "errorAt": "2025-06-01T04:10:13.443Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "151850021267056692",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://nowcoder/discuss/9/4"
    }
  ]
}
```
