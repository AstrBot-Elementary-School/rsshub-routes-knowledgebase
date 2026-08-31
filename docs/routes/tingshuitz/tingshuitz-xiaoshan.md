# 停水通知 - 萧山区

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/xiaoshan`
- Route Name: `萧山区`
- Example: `/tingshuitz/xiaoshan`
- URL: `www.xswater.com/gongshui/channels/227.html`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `znhocn`
- Source Location: `xiaoshan.ts`
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
  - `www.xswater.com/gongshui/channels/227.html`
  - `www.xswater.com/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/tingshuitz/xiaoshan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xiaoshan.ts",
  "maintainers": [
    "znhocn"
  ],
  "name": "萧山区",
  "parameters": {},
  "path": "/xiaoshan",
  "radar": [
    {
      "source": [
        "www.xswater.com/gongshui/channels/227.html",
        "www.xswater.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.xswater.com/gongshui/channels/227.html"
}
```
