# 南京大学 - 资产管理处

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/zcc`
- Route Name: `资产管理处`
- Example: `/nju/zcc`
- URL: `zcc.nju.edu.cn/tzgg/gyfytdglk/index.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `zcc.ts`
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
  - `zcc.nju.edu.cn/tzgg/gyfytdglk/index.html`
  - `zcc.nju.edu.cn/tzgg/index.html`
  - `zcc.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/zcc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "zcc.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "资产管理处",
  "parameters": {},
  "path": "/zcc",
  "radar": [
    {
      "source": [
        "zcc.nju.edu.cn/tzgg/gyfytdglk/index.html",
        "zcc.nju.edu.cn/tzgg/index.html",
        "zcc.nju.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "资产管理处-公告通知 - Powered by RSSHub",
      "errorAt": "2025-12-03T06:46:20.246Z",
      "errorMessage": "[GET] \"https://zcc.nju.edu.cn/sy/tzzhxx/index.html\": <no response> fetch failed\n",
      "id": "62660981128166400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zcc.nju.edu.cn/sy/tzzhxx/index.html",
      "title": "资产管理处-公告通知",
      "type": "feed",
      "url": "rsshub://nju/zcc"
    }
  ],
  "url": "zcc.nju.edu.cn/tzgg/gyfytdglk/index.html"
}
```
