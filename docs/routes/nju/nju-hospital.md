# 南京大学 - 校医院

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/hospital`
- Route Name: `校医院`
- Example: `/nju/hospital`
- URL: `hospital.nju.edu.cn/ggtz/index.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `hosptial.ts`
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
  - `hospital.nju.edu.cn/ggtz/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/hospital",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "hosptial.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "校医院",
  "parameters": {},
  "path": "/hospital",
  "radar": [
    {
      "source": [
        "hospital.nju.edu.cn/ggtz/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "校医院-公告通知 - Powered by RSSHub",
      "errorAt": "2025-12-03T06:46:02.470Z",
      "errorMessage": "[GET] \"https://hospital.nju.edu.cn/ggtz/index.html\": <no response> fetch failed\n",
      "id": "62660875676972032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hospital.nju.edu.cn/ggtz/index.html",
      "title": "校医院-公告通知",
      "type": "feed",
      "url": "rsshub://nju/hospital"
    }
  ],
  "url": "hospital.nju.edu.cn/ggtz/index.html"
}
```
