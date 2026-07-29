# Deepin - 首页主题列表

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/deepin/threads/:type?`
- Route Name: `首页主题列表`
- Example: `/deepin/threads/latest`
- URL: `bbs.deepin.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `myml`
- Source Location: `thread.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org`
- `target`: `/threads/latest`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/threads/latest",
  "heat": 20,
  "location": "thread.ts",
  "maintainers": [
    "myml"
  ],
  "name": "首页主题列表",
  "parameters": {
    "type": {
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/threads/:type?",
  "radar": [
    {
      "source": [
        "bbs.deepin.org"
      ],
      "target": "/threads/latest"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "deepin论坛主页 - 最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62087080975204352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/",
      "title": "deepin论坛主页 - 最新主题",
      "type": "feed",
      "url": "rsshub://deepin/threads/latest"
    },
    {
      "description": "deepin论坛主页 - 最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155304200635561984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/",
      "title": "deepin论坛主页 - 最新主题",
      "type": "feed",
      "url": "rsshub://deepin/threads"
    }
  ]
}
```
