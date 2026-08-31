# 巨量算数 - 算数指数 - 抖音指数波峰

## Coverage
`index-only`

## Route
- Namespace: `oceanengine`
- Namespace Name: `巨量算数 - 算数指数`
- Route Path: `/oceanengine/index/:keyword`
- Route Name: `抖音指数波峰`
- Example: `/oceanengine/index/教材`
- URL: `trendinsight.oceanengine.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Jkker`
- Source Location: `arithmetic-index.tsx`
- Source Module: `_None_`

## Description
爬取巨量算数近 6 个月的抖音指数，解密后提取指数波峰当日的热门搜索关键词，生成为 RSS。可用于追踪新闻热点事件。

## Parameters
- `keyword`: 热点关键词


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "爬取巨量算数近 6 个月的抖音指数，解密后提取指数波峰当日的热门搜索关键词，生成为 RSS。可用于追踪新闻热点事件。",
  "example": "/oceanengine/index/教材",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 2,
  "location": "arithmetic-index.tsx",
  "maintainers": [
    "Jkker"
  ],
  "name": "抖音指数波峰",
  "parameters": {
    "keyword": "热点关键词"
  },
  "path": "/index/:keyword",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
