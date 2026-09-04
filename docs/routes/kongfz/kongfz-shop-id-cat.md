# 孔夫子旧书网 - 店铺上架

## Coverage
`index-only`

## Route
- Namespace: `kongfz`
- Namespace Name: `孔夫子旧书网`
- Route Path: `/kongfz/shop/:id/:cat?`
- Route Name: `店铺上架`
- Example: `/kongfz/shop/10067/1`
- URL: `kongfz.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `shop.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 店铺 id, 可在对应店铺页 URL 中找到
- `cat`: 分类 id，可在对应分类页 URL 中找到，默认为店铺最新上架


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/kongfz/shop/10067/1",
  "heat": 0,
  "location": "shop.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "店铺上架",
  "parameters": {
    "cat": "分类 id，可在对应分类页 URL 中找到，默认为店铺最新上架",
    "id": "店铺 id, 可在对应店铺页 URL 中找到"
  },
  "path": "/shop/:id/:cat?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
