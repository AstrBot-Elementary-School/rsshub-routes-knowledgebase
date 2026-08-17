# 中国科学院 - 电工研究所 科研动态

## Coverage
`index-only`

## Route
- Namespace: `cas`
- Namespace Name: `中国科学院`
- Route Path: `/cas/iee/kydt`
- Route Name: `电工研究所 科研动态`
- Example: `/cas/iee/kydt`
- URL: `www.iee.cas.cn/xwzx/kydt`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `iee/kydt.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.iee.cas.cn/xwzx/kydt`
  - `www.iee.cas.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cas/iee/kydt",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "iee/kydt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "电工研究所 科研动态",
  "parameters": {},
  "path": "/iee/kydt",
  "radar": [
    {
      "source": [
        "www.iee.cas.cn/xwzx/kydt",
        "www.iee.cas.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "科研成果 - 中国科学院电工研究所 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75524738969015296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.iee.cas.cn/xwzx/kydt/",
      "title": "科研成果 - 中国科学院电工研究所",
      "type": "feed",
      "url": "rsshub://cas/iee/kydt"
    }
  ],
  "url": "www.iee.cas.cn/xwzx/kydt"
}
```
