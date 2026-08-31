# 无讼案例 - 案例

## Coverage
`index-only`

## Route
- Namespace: `itslaw`
- Namespace Name: `无讼案例`
- Route Path: `/itslaw/judgements/:conditions`
- Route Name: `案例`
- Example: `/itslaw/judgements/regulation+1121495748+13+中华人民共和国公司法（2018）第二十一条`
- URL: `www.itslaw.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `harveyqiu`
- Source Location: `judgements.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `conditions`: 筛选条件，见示例


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/itslaw/judgements/regulation+1121495748+13+中华人民共和国公司法（2018）第二十一条",
  "heat": 0,
  "location": "judgements.ts",
  "maintainers": [
    "harveyqiu"
  ],
  "name": "案例",
  "parameters": {
    "conditions": "筛选条件，见示例"
  },
  "path": "/judgements/:conditions",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
