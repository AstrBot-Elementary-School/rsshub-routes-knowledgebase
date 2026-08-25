# 吉林工商学院 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `jlbtc`
- Namespace Name: `吉林工商学院`
- Route Path: `/jlbtc/jwc/:category{.+}?`
- Route Name: `教务处`
- Example: `/jlbtc/jwc`
- URL: `www.jlbtc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 教务新闻   | 通知公告   | 教务管理  | 教师发展 | 学籍考务工作 | 教学建设 |
| ---------- | ---------- | --------- | -------- | ------------ | -------- |
| index/tpxw | index/tzgg | szdw/jwgl | jjj      | xjkwgz       | zyjs     |

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
  "description": "| 教务新闻   | 通知公告   | 教务管理  | 教师发展 | 学籍考务工作 | 教学建设 |\n| ---------- | ---------- | --------- | -------- | ------------ | -------- |\n| index/tpxw | index/tzgg | szdw/jwgl | jjj      | xjkwgz       | zyjs     |",
  "example": "/jlbtc/jwc",
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "教务处",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/jwc/:category{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
