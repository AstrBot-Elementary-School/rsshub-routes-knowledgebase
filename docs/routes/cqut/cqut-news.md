# 重庆理工大学 - 学校通知

## Coverage
`index-only`

## Route
- Namespace: `cqut`
- Namespace Name: `重庆理工大学`
- Route Path: `/cqut/news`
- Route Name: `学校通知`
- Example: `/cqut/news`
- URL: `www.cqut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Colin-XKL`
- Source Location: `cqut-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.cqut.edu.cn/tzgg/xxtz1.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cqut/news",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "cqut-news.ts",
  "maintainers": [
    "Colin-XKL"
  ],
  "name": "学校通知",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.cqut.edu.cn/tzgg/xxtz1.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
