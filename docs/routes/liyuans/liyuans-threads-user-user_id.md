# 梨园 - 主题帖（用户）

## Coverage
`index-only`

## Route
- Namespace: `liyuans`
- Namespace Name: `梨园`
- Route Path: `/liyuans/threads/user/:user_id`
- Route Name: `主题帖（用户）`
- Example: `/liyuans/threads/user/1`
- URL: `forums.liyuans.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `WooMai`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: 用户 ID (仅支持数字 ID), 支持多个, 使用英文逗号分隔


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
  "example": "/liyuans/threads/user/1",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "WooMai"
  ],
  "name": "主题帖（用户）",
  "parameters": {
    "user_id": "用户 ID (仅支持数字 ID), 支持多个, 使用英文逗号分隔"
  },
  "path": "/threads/user/:user_id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
