# 龙空 - 分区

## Coverage
`index-only`

## Route
- Namespace: `lkong`
- Namespace Name: `龙空`
- Route Path: `/lkong/forum/:id?/:digest?`
- Route Name: `分区`
- Example: `/lkong/forum/60`
- URL: `lkong.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `nczitzk, ma6254`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 分区 id, 可在分区的URL里找到
- `digest`: 默认获取全部主题，任意值则只获取精华主题


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lkong.com/forum/:id`
  - `lkong.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/lkong/forum/60",
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "nczitzk",
    "ma6254"
  ],
  "name": "分区",
  "parameters": {
    "digest": "默认获取全部主题，任意值则只获取精华主题",
    "id": "分区 id, 可在分区的URL里找到"
  },
  "path": "/forum/:id?/:digest?",
  "radar": [
    {
      "source": [
        "lkong.com/forum/:id",
        "lkong.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": []
}
```
