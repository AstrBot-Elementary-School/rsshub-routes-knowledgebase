# DCFever - 二手市集 - 物品搜尋

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/dcfever/trading/search/:keyword/:mainCat?`
- Route Name: `二手市集 - 物品搜尋`
- Example: `/dcfever/trading/search/Sony`
- URL: `dcfever.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `trading-search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: 關鍵字
- `mainCat`: 主要分類 ID，見上表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dcfever/trading/search/Sony",
  "heat": 0,
  "location": "trading-search.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "二手市集 - 物品搜尋",
  "parameters": {
    "keyword": "關鍵字",
    "mainCat": "主要分類 ID，見上表"
  },
  "path": "/trading/search/:keyword/:mainCat?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
