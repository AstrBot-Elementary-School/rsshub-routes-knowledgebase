# 深圳证券交易所 - 上市公告 - 可转换债券

## Coverage
`index-only`

## Route
- Namespace: `szse`
- Namespace Name: `深圳证券交易所`
- Route Path: `/szse/notice`
- Route Name: `上市公告 - 可转换债券`
- Example: `/szse/notice`
- URL: `szse.cn/disclosure/notice/company/index.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`
- Source Location: `notice.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `szse.cn/disclosure/notice/company/index.html`
  - `szse.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/szse/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "notice.ts",
  "maintainers": [
    "Jeason0228",
    "nczitzk"
  ],
  "name": "上市公告 - 可转换债券",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "szse.cn/disclosure/notice/company/index.html",
        "szse.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "深圳证券交易所——上市公告-可转换债券 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68289343779232768",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.szse.cn/disclosure/notice/company/index.html",
      "title": "深圳证券交易所——上市公告-可转换债券",
      "type": "feed",
      "url": "rsshub://szse/notice"
    }
  ],
  "url": "szse.cn/disclosure/notice/company/index.html"
}
```
