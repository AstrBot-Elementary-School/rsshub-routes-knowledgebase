# 千篇网 - 知识库／资讯

## Coverage
`index-only`

## Route
- Namespace: `qianp`
- Namespace Name: `千篇网`
- Route Path: `/qianp/news/:path{.+}?`
- Route Name: `知识库／资讯`
- Example: `/qianp/news`
- URL: `qianp.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: 路径，可在URL中找到，默认为 `news/recommend`


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
  "example": "/qianp/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "知识库／资讯",
  "parameters": {
    "path": "路径，可在URL中找到，默认为 `news/recommend`"
  },
  "path": "/news/:path{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
