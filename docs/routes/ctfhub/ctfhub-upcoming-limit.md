# CTFHub - 查询近期赛事

## Coverage
`index-only`

## Route
- Namespace: `ctfhub`
- Namespace Name: `CTFHub`
- Route Path: `/ctfhub/upcoming/:limit?`
- Route Name: `查询近期赛事`
- Example: `/ctfhub/upcoming`
- URL: `www.ctfhub.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `frankli0324`
- Source Location: `upcoming.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `limit`: 一个整数，筛选最近的 limit 场比赛，默认为 5


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
  "example": "/ctfhub/upcoming",
  "heat": 0,
  "location": "upcoming.ts",
  "maintainers": [
    "frankli0324"
  ],
  "name": "查询近期赛事",
  "parameters": {
    "limit": "一个整数，筛选最近的 limit 场比赛，默认为 5"
  },
  "path": "/upcoming/:limit?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected -567232420 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
