# 中国研究生招生信息网 - 考研动态

## Coverage
`index-only`

## Route
- Namespace: `chsi`
- Namespace Name: `中国研究生招生信息网`
- Route Path: `/chsi/kydt`
- Route Name: `考研动态`
- Example: `/chsi/kydt`
- URL: `yz.chsi.com.cn/kyzx/kydt`
- Language: `_None_`
- Categories: `study`
- Maintainers: `SunBK201`
- Source Location: `kydt.ts`
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
  - `yz.chsi.com.cn/kyzx/kydt`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/chsi/kydt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 90,
  "location": "kydt.ts",
  "maintainers": [
    "SunBK201"
  ],
  "name": "考研动态",
  "parameters": {},
  "path": "/kydt",
  "radar": [
    {
      "source": [
        "yz.chsi.com.cn/kyzx/kydt"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国研究生招生信息网 - 考研动态 - Powered by RSSHub",
      "errorAt": "2026-08-15T09:33:47.704Z",
      "errorMessage": "200 ",
      "id": "64923928042092545",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yz.chsi.com.cn/kyzx/kydt/",
      "title": "中国研究生招生信息网 - 考研动态",
      "type": "feed",
      "url": "rsshub://chsi/kydt"
    }
  ],
  "url": "yz.chsi.com.cn/kyzx/kydt"
}
```
