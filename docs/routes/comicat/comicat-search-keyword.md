# Comicat - 搜索关键词

## Coverage
`index-only`

## Route
- Namespace: `comicat`
- Namespace Name: `Comicat`
- Route Path: `/comicat/search/:keyword`
- Route Name: `搜索关键词`
- Example: `/comicat/search/喵萌奶茶屋+跃动青春+720P+简日`
- URL: `comicat.org`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `Cyang39`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 关键词，请用`+`号连接


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comicat/search/喵萌奶茶屋+跃动青春+720P+简日",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "search.ts",
  "maintainers": [
    "Cyang39"
  ],
  "name": "搜索关键词",
  "parameters": {
    "keyword": "关键词，请用`+`号连接"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Comicat - 无职转生 - Powered by RSSHub",
      "errorAt": "2026-09-06T02:57:23.821Z",
      "errorMessage": "Failed to fetch\n",
      "id": "191615269219045376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://comicat.org/search.php?keyword=%E6%97%A0%E8%81%8C%E8%BD%AC%E7%94%9F",
      "title": "Comicat - 无职转生",
      "type": "feed",
      "url": "rsshub://comicat/search/%E6%97%A0%E8%81%8C%E8%BD%AC%E7%94%9F"
    }
  ]
}
```
