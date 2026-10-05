# imop - 全部消息

## Coverage
`index-only`

## Route
- Namespace: `imop`
- Namespace Name: `imop`
- Route Path: `/imop/tianshu`
- Route Name: `全部消息`
- Example: `/imop/tianshu`
- URL: `imop.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `zhkgo`
- Source Location: `tianshu.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `t.imop.com`
- `target`: `/tianshu`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/imop/tianshu",
  "heat": 1,
  "location": "tianshu.ts",
  "maintainers": [
    "zhkgo"
  ],
  "name": "全部消息",
  "path": "/tianshu",
  "radar": [
    {
      "source": [
        "t.imop.com"
      ],
      "target": "/tianshu"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "天书最新消息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74073602902251520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://t.imop.com/list/0-1.htm",
      "title": "天书最新消息",
      "type": "feed",
      "url": "rsshub://imop/tianshu"
    }
  ]
}
```
