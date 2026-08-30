# 镁客网 - 频道

## Coverage
`index-only`

## Route
- Namespace: `im2maker`
- Namespace Name: `镁客网`
- Route Path: `/im2maker/:channel?`
- Route Name: `频道`
- Example: `/im2maker`
- URL: `www.im2maker.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `jin1218scu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新文章 | 行业快讯 | 行业观察 | 镁客请讲 | 硬科技 100 人 | 投融界   | 万象       |
| -------- | -------- | -------- | -------- | ------------- | -------- | ---------- |
|          | fresh    | industry | talk     | intech        | investor | everything |

## Parameters
- `channel`: 默认不填为 最新文章 ，频道如下


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新文章 | 行业快讯 | 行业观察 | 镁客请讲 | 硬科技 100 人 | 投融界   | 万象       |\n| -------- | -------- | -------- | -------- | ------------- | -------- | ---------- |\n|          | fresh    | industry | talk     | intech        | investor | everything |",
  "example": "/im2maker",
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "jin1218scu"
  ],
  "name": "频道",
  "parameters": {
    "channel": "默认不填为 最新文章 ，频道如下"
  },
  "path": "/:channel?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-26T04:23:55.144Z",
      "errorMessage": "[GET] \"https://www.im2maker.com/wp-json/wp/v2/posts?_embed\": <no response> fetch failed (unable to verify the first certificate; if the root CA is installed locally, try running Node.js with --use-system-ca)\n",
      "id": "149642094386478113",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://im2maker/"
    }
  ]
}
```
