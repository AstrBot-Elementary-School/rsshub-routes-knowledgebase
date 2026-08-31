# 扇贝 - 用户打卡

## Coverage
`index-only`

## Route
- Namespace: `shanbay`
- Namespace Name: `扇贝`
- Route Path: `/shanbay/checkin/:id`
- Route Name: `用户打卡`
- Example: `/shanbay/checkin/ddwej`
- URL: `www.shanbay.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `DIYgod`
- Source Location: `checkin.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/shanbay/checkin/ddwej",
  "heat": 0,
  "location": "checkin.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "用户打卡",
  "parameters": {
    "id": "用户 id"
  },
  "path": "/checkin/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
