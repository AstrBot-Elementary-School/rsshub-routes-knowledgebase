# 广告门 - 案例库

## Coverage
`index-only`

## Route
- Namespace: `adquan`
- Namespace Name: `广告门`
- Route Path: `/adquan/case_library`
- Route Name: `案例库`
- Example: `/adquan/case_library`
- URL: `www.adquan.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `case-library.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.adquan.com/case_library/index`
- `target`: `/case_library`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/adquan/case_library",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 22,
  "location": "case-library.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "案例库",
  "path": "/case_library",
  "radar": [
    {
      "source": [
        "www.adquan.com/case_library/index"
      ],
      "target": "/case_library"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -231372773640265 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广告门案例库专注于展示广告营销领域和泛营销行业的优秀案例，和行业奖项如：金瞳奖、戛纳等的获奖案例。案例多配有解读和分析，帮您更好的理解市场动态 - Powered by RSSHub",
      "errorAt": "2026-08-06T06:30:57.890Z",
      "errorMessage": "[GET] \"https://www.adquan.com/case_library/index\": <no response> fetch failed\n[GET] \"https://www.adquan.com/case_library/index\": 405 Not Allowed\n",
      "id": "136638184266081280",
      "image": "https://oss.adquan.com/img_pc/navigation/hongbai.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.adquan.com/case_library/index",
      "title": "广告门案例库 - 广告营销行业案例库",
      "type": "feed",
      "url": "rsshub://adquan/case_library"
    }
  ],
  "url": "www.adquan.com",
  "view": 0
}
```
