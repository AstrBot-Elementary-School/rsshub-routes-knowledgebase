# 鸟哥笔记 - 今日事

## Coverage
`index-only`

## Route
- Namespace: `niaogebiji`
- Namespace Name: `鸟哥笔记`
- Route Path: `/niaogebiji/today`
- Route Name: `今日事`
- Example: `/niaogebiji/today`
- URL: `niaogebiji.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `KotoriK`
- Source Location: `today.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `niaogebiji.com/`
  - `niaogebiji.com/bulletin`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/niaogebiji/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "today.ts",
  "maintainers": [
    "KotoriK"
  ],
  "name": "今日事",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "niaogebiji.com/",
        "niaogebiji.com/bulletin"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "鸟哥笔记-今日事 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63474398493291526",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.niaogebiji.com/bulletin",
      "title": "鸟哥笔记-今日事",
      "type": "feed",
      "url": "rsshub://niaogebiji/today"
    }
  ],
  "url": "niaogebiji.com/"
}
```
