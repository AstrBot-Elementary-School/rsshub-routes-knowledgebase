# 轻之国度 - 文章更新阅读

## Coverage
`index-only`

## Route
- Namespace: `lightnovel`
- Namespace Name: `轻之国度`
- Route Path: `/lightnovel/:keywords/:security_key?`
- Route Name: `文章更新阅读`
- Example: `/lightnovel/歡迎來到實力至上主義的教室/3cfc2dc63f3575ee42e12823188ad1b5:1709125:0`
- URL: `lightNovel.us/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nightmare-mio`
- Source Location: `light-novel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keywords`: 关键字，可以模糊匹配，但最好精确匹配
- `security_key`: cookie,由于文章有防爬，所以必须携带cookie请求。route中的cookie优先级高于环境变量cookie，取token中的security_key值


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lightNovel.us/`
- `target`: `/:keywords/:security_key`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/lightnovel/歡迎來到實力至上主義的教室/3cfc2dc63f3575ee42e12823188ad1b5:1709125:0",
  "heat": 0,
  "location": "light-novel.ts",
  "maintainers": [
    "nightmare-mio"
  ],
  "name": "文章更新阅读",
  "parameters": {
    "keywords": "关键字，可以模糊匹配，但最好精确匹配",
    "security_key": "cookie,由于文章有防爬，所以必须携带cookie请求。route中的cookie优先级高于环境变量cookie，取token中的security_key值"
  },
  "path": "/:keywords/:security_key?",
  "radar": [
    {
      "source": [
        "lightNovel.us/"
      ],
      "target": "/:keywords/:security_key"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "lightNovel.us/"
}
```
