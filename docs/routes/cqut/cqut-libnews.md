# 重庆理工大学 - 图书馆通知

## Coverage
`index-only`

## Route
- Namespace: `cqut`
- Namespace Name: `重庆理工大学`
- Route Path: `/cqut/libnews`
- Route Name: `图书馆通知`
- Example: `/cqut/libnews`
- URL: `www.cqut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Colin-XKL`
- Source Location: `cqut-libnews.ts`
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
  - `lib.cqut.edu.cn/*`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cqut/libnews",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "cqut-libnews.ts",
  "maintainers": [
    "Colin-XKL"
  ],
  "name": "图书馆通知",
  "path": "/libnews",
  "radar": [
    {
      "source": [
        "lib.cqut.edu.cn/*"
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
