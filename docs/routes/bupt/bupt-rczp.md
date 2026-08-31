# 北京邮电大学 - 人才招聘

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/rczp`
- Route Name: `人才招聘`
- Example: `/bupt/rczp`
- URL: `bupt.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `rczp.ts`
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
  - `bupt.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bupt/rczp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "rczp.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "人才招聘",
  "parameters": {},
  "path": "/rczp",
  "radar": [
    {
      "source": [
        "bupt.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人才招聘-北京邮电大学 - Powered by RSSHub",
      "errorAt": "2025-06-17T10:30:31.122Z",
      "errorMessage": "[GET] \"https://www.bupt.edu.cn/rczp.htm\": 412 Precondition Failed\n",
      "id": "66343158256695296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bupt.edu.cn/rczp.htm",
      "title": "人才招聘-北京邮电大学",
      "type": "feed",
      "url": "rsshub://bupt/rczp"
    }
  ],
  "url": "bupt.edu.cn/"
}
```
