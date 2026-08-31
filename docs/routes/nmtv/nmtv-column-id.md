# 内蒙古广播电视台 - 点播

## Coverage
`index-only`

## Route
- Namespace: `nmtv`
- Namespace Name: `内蒙古广播电视台`
- Route Path: `/nmtv/column/:id?`
- Route Name: `点播`
- Example: `/nmtv/column/877`
- URL: `nmtv.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `column.tsx`
- Source Module: `_None_`

## Description
::: tip
如 [蒙古语卫视新闻联播](http://www.nmtv.cn/folder292/folder663/folder301/folder830/folder877) 的 URL 为 `http://www.nmtv.cn/folder292/folder663/folder301/folder830/folder877`，其栏目 id 为末尾数字编号，即 `877`。可以得到其对应路由为 [`/nmtv/column/877`](https://rsshub.app/nmtv/column/877)
:::

## Parameters
- `id`: 栏目 id，可在对应栏目 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n如 [蒙古语卫视新闻联播](http://www.nmtv.cn/folder292/folder663/folder301/folder830/folder877) 的 URL 为 `http://www.nmtv.cn/folder292/folder663/folder301/folder830/folder877`，其栏目 id 为末尾数字编号，即 `877`。可以得到其对应路由为 [`/nmtv/column/877`](https://rsshub.app/nmtv/column/877)\n:::",
  "example": "/nmtv/column/877",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "column.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "点播",
  "parameters": {
    "id": "栏目 id，可在对应栏目 URL 中找到"
  },
  "path": "/column/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
