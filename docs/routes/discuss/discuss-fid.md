# 香港討論區 - 版塊

## Coverage
`index-only`

## Route
- Namespace: `discuss`
- Namespace Name: `香港討論區`
- Route Path: `/discuss/:fid`
- Route Name: `版塊`
- Example: `/discuss/62`
- URL: `www.discuss.com.hk`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `fid`: fid，可在对应板块页的 URL 中找到


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/discuss/62",
  "features": {
    "antiCrawler": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "版塊",
  "parameters": {
    "fid": "fid，可在对应板块页的 URL 中找到"
  },
  "path": "/:fid",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
