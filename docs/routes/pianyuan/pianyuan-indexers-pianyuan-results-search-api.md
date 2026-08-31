# 片源网 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `pianyuan`
- Namespace Name: `片源网`
- Route Path: `/pianyuan/indexers/pianyuan/results/search/api`
- Route Name: `搜索`
- Example: `/pianyuan/indexers/pianyuan/results/search/api?t=test&q=长津湖`
- URL: `pianyuan.org/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `jerry1119`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
搜索路由模仿 jackett 的搜索 api, 以提供给 nastools 使用，填写在 nastools 配置 indexer 中

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `pianyuan.org/`
- `target`: `/index`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "搜索路由模仿 jackett 的搜索 api, 以提供给 nastools 使用，填写在 nastools 配置 indexer 中",
  "example": "/pianyuan/indexers/pianyuan/results/search/api?t=test&q=长津湖",
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "jerry1119"
  ],
  "name": "搜索",
  "path": "/indexers/pianyuan/results/search/api",
  "radar": [
    {
      "source": [
        "pianyuan.org/"
      ],
      "target": "/index"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "pianyuan.org/"
}
```
