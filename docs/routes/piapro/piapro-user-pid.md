# piapro - User latest works

## Coverage
`index-only`

## Route
- Namespace: `piapro`
- Namespace Name: `piapro`
- Route Path: `/piapro/user/:pid`
- Route Name: `User latest works`
- Example: `/piapro/user/shine_longer`
- URL: `piapro.jp`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pid`: User ID, can be found in url


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/piapro/user/shine_longer",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "User latest works",
  "parameters": {
    "pid": "User ID, can be found in url"
  },
  "path": "/user/:pid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 386307662236 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
