# 南京大学 - 本科迎新

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/admission`
- Route Name: `本科迎新`
- Example: `/nju/admission`
- URL: `admission.nju.edu.cn/tzgg/index.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `admission.ts`
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
  - `admission.nju.edu.cn/tzgg/index.html`
  - `admission.nju.edu.cn/tzgg`
  - `admission.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/admission",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "admission.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "本科迎新",
  "parameters": {},
  "path": "/admission",
  "radar": [
    {
      "source": [
        "admission.nju.edu.cn/tzgg/index.html",
        "admission.nju.edu.cn/tzgg",
        "admission.nju.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "本科迎新-通知公告 - Powered by RSSHub",
      "errorAt": "2025-12-03T06:46:04.791Z",
      "errorMessage": "[GET] \"https://admission.nju.edu.cn/tzgg\": <no response> fetch failed\n",
      "id": "62659893230566400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://admission.nju.edu.cn/tzgg",
      "title": "本科迎新-通知公告",
      "type": "feed",
      "url": "rsshub://nju/admission"
    }
  ],
  "url": "admission.nju.edu.cn/tzgg/index.html"
}
```
