# 逛丢 - 九块九

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/guangdiu/cheaps/:query?`
- Route Name: `九块九`
- Example: `/guangdiu/cheaps/k=clothes`
- URL: `guangdiu.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `fatpandac`
- Source Location: `cheaps.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `query`: 链接参数，对应网址问号后的内容


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
    "shopping"
  ],
  "example": "/guangdiu/cheaps/k=clothes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 229,
  "location": "cheaps.ts",
  "maintainers": [
    "fatpandac"
  ],
  "name": "九块九",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/cheaps/:query?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "逛丢 - 九块九 - Powered by RSSHub",
      "errorAt": "2026-01-14T18:34:19.387Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "65670452855599112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/cheaps.php?k=clothes",
      "title": "逛丢 - 九块九",
      "type": "feed",
      "url": "rsshub://guangdiu/cheaps/k=clothes"
    },
    {
      "description": "逛丢 - 九块九 - Powered by RSSHub",
      "errorAt": "2026-01-14T23:56:22.109Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "157995760019765248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://guangdiu.com/cheaps.php",
      "title": "逛丢 - 九块九",
      "type": "feed",
      "url": "rsshub://guangdiu/cheaps"
    }
  ]
}
```
