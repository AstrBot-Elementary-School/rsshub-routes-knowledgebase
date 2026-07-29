# 巨量算数 - 算数指数 - 头条指数波峰

## Coverage
`index-only`

## Route
- Namespace: `oceanengine`
- Namespace Name: `巨量算数 - 算数指数`
- Route Path: `/oceanengine/index/:keyword/toutiao`
- Route Name: `头条指数波峰`
- Example: `/oceanengine/index/教材/toutiao`
- URL: `trendinsight.oceanengine.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Jkker`
- Source Location: `arithmetic-index-toutiao.ts`
- Source Module: `_None_`

## Description
爬取巨量算数近 6 个月的头条指数，解密后提取指数波峰当日的热门搜索关键词，生成为 RSS。可用于追踪新闻热点事件。

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
  "description": "爬取巨量算数近 6 个月的头条指数，解密后提取指数波峰当日的热门搜索关键词，生成为 RSS。可用于追踪新闻热点事件。",
  "example": "/oceanengine/index/教材/toutiao",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "arithmetic-index-toutiao.ts",
  "maintainers": [
    "Jkker"
  ],
  "name": "头条指数波峰",
  "parameters": {
    "keyword": "热点关键词"
  },
  "path": "/index/:keyword/toutiao",
  "topFeeds": []
}
```
