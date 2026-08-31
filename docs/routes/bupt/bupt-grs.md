# 北京邮电大学 - 研究生院通知

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/grs`
- Route Name: `研究生院通知`
- Example: `/bupt/grs`
- URL: `grs.bupt.edu.cn/tzgg.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jiaming-shi`
- Source Location: `grs.ts`
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
  - `grs.bupt.edu.cn/tzgg.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bupt/grs",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "grs.ts",
  "maintainers": [
    "jiaming-shi"
  ],
  "name": "研究生院通知",
  "path": "/grs",
  "radar": [
    {
      "source": [
        "grs.bupt.edu.cn/tzgg.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "grs.bupt.edu.cn/tzgg.htm"
}
```
