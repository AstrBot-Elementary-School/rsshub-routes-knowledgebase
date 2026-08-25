# 吉林工商学院 - 科研处

## Coverage
`index-only`

## Route
- Namespace: `jlbtc`
- Namespace Name: `吉林工商学院`
- Route Path: `/jlbtc/kyc/:category?`
- Route Name: `科研处`
- Example: `/jlbtc/kyc`
- URL: `www.jlbtc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `kyc.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻动态 |
| -------- | -------- |
| tzgg     | xwdt     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 |\n| -------- | -------- |\n| tzgg     | xwdt     |",
  "example": "/jlbtc/kyc",
  "heat": 0,
  "location": "kyc.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "科研处",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/kyc/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
