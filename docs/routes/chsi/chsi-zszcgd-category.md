# 中国研究生招生信息网 - 教育部阳光高考信息公开平台招生政策规定

## Coverage
`index-only`

## Route
- Namespace: `chsi`
- Namespace Name: `中国研究生招生信息网`
- Route Path: `/chsi/zszcgd/:category?`
- Route Name: `教育部阳光高考信息公开平台招生政策规定`
- Example: `/chsi/zszcgd`
- URL: `yz.chsi.com.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `zszcgd.ts`
- Source Module: `_None_`

## Description
| 招生政策 | 深化考试招生制度改革 | 教育法律法规 |
| -------- | -------------------- | ------------ |
| dnzszc   | zdgg                 | jyflfg       |

## Parameters
- `category`: 分类，默认为招生政策


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
  "description": "| 招生政策 | 深化考试招生制度改革 | 教育法律法规 |\n| -------- | -------------------- | ------------ |\n| dnzszc   | zdgg                 | jyflfg       |",
  "example": "/chsi/zszcgd",
  "heat": 0,
  "location": "zszcgd.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "教育部阳光高考信息公开平台招生政策规定",
  "parameters": {
    "category": "分类，默认为招生政策"
  },
  "path": "/zszcgd/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
