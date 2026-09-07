# 大河财立方 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `dahecube`
- Namespace Name: `大河财立方`
- Route Path: `/dahecube/:type?`
- Route Name: `新闻`
- Example: `/dahecube`
- URL: `dahecube.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `linbuxiao`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |
| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |
| recommend | history | stock | business | education | finance | science | invest | column |

## Parameters
- `type`: 板块，见下表，默认为推荐


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
  "description": "| 推荐      | 党史    | 豫股  | 财经     | 投教      | 金融    | 科创    | 投融   | 专栏   |\n| --------- | ------- | ----- | -------- | --------- | ------- | ------- | ------ | ------ |\n| recommend | history | stock | business | education | finance | science | invest | column |",
  "example": "/dahecube",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "index.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "name": "新闻",
  "parameters": {
    "type": "板块，见下表，默认为推荐"
  },
  "path": "/:type?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "大河财立方 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73611588824278016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dahecube.com/index.html?recid=1",
      "title": "大河财立方",
      "type": "feed",
      "url": "rsshub://dahecube"
    },
    {
      "description": "大河财立方 推荐 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79864002134590464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dahecube.com/index.html?recid=1",
      "title": "大河财立方",
      "type": "feed",
      "url": "rsshub://dahecube/recommend"
    }
  ]
}
```
