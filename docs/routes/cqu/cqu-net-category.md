# 重庆大学 - 信息化办公室

## Coverage
`index-only`

## Route
- Namespace: `cqu`
- Namespace Name: `重庆大学`
- Route Path: `/cqu/net/:category`
- Route Name: `信息化办公室`
- Example: `/cqu/net/tzgg`
- URL: `cqu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Hagb`
- Source Location: `net.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 单位动态 | 语言文字 |
| -------- | -------- | -------- |
| tzgg     | dwdt     | yywz     |

## Parameters
- `category`: 分类名


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 单位动态 | 语言文字 |\n| -------- | -------- | -------- |\n| tzgg     | dwdt     | yywz     |",
  "example": "/cqu/net/tzgg",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "net.ts",
  "maintainers": [
    "Hagb"
  ],
  "name": "信息化办公室",
  "parameters": {
    "category": "分类名"
  },
  "path": "/net/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
