# 鹰角网络 - 明日方舟：终末地 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/endfield/news/:group?`
- Route Name: `明日方舟：终末地 - 游戏公告与新闻`
- Example: `/hypergryph/endfield/news`
- URL: `endfield.hypergryph.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `E-larex`
- Source Location: `endfield/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 公告    | 活动   | 新闻 |
| ---- | ------- | ------ | ---- |
| ALL  | notices | events | news |

## Parameters
- `group`: 分组，默认为 `ALL`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `endfield.hypergryph.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 公告    | 活动   | 新闻 |\n| ---- | ------- | ------ | ---- |\n| ALL  | notices | events | news |",
  "example": "/hypergryph/endfield/news",
  "heat": 2,
  "location": "endfield/news.ts",
  "maintainers": [
    "E-larex"
  ],
  "name": "明日方舟：终末地 - 游戏公告与新闻",
  "parameters": {
    "group": "分组，默认为 `ALL`"
  },
  "path": "/endfield/news/:group?",
  "radar": [
    {
      "source": [
        "endfield.hypergryph.com/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "《明日方舟：终末地》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1161356855100702720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://endfield.hypergryph.com/news",
      "title": "《明日方舟：终末地》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/endfield/news"
    }
  ],
  "url": "endfield.hypergryph.com/news"
}
```
