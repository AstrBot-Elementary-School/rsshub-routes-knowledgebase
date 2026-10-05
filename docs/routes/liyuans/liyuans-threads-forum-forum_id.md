# 梨园 - 主题帖（板块）

## Coverage
`index-only`

## Route
- Namespace: `liyuans`
- Namespace Name: `梨园`
- Route Path: `/liyuans/threads/forum/:forum_id`
- Route Name: `主题帖（板块）`
- Example: `/liyuans/threads/forum/1`
- URL: `forums.liyuans.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `WooMai`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `forum_id`: 板块 ID, 支持多个, 使用英文逗号分隔


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/liyuans/threads/forum/1",
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "WooMai"
  ],
  "name": "主题帖（板块）",
  "parameters": {
    "forum_id": "板块 ID, 支持多个, 使用英文逗号分隔"
  },
  "path": "/threads/forum/:forum_id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
