# 停水通知 - 深圳市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/shenzhen`
- Route Name: `深圳市`
- Example: `/tingshuitz/shenzhen`
- URL: `sz-water.com.cn/*`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `lilPiper`
- Source Location: `shenzhen.tsx`
- Source Module: `_None_`

## Description
可能仅限中国大陆服务器访问，以实际情况为准。

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
  - `sz-water.com.cn/*`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "可能仅限中国大陆服务器访问，以实际情况为准。",
  "example": "/tingshuitz/shenzhen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "shenzhen.tsx",
  "maintainers": [
    "lilPiper"
  ],
  "name": "深圳市",
  "parameters": {},
  "path": "/shenzhen",
  "radar": [
    {
      "source": [
        "sz-water.com.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(24) ] to not include '宝安区燕罗街道松福麒麟山天桥2026-08-16 15:18:00'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "sz-water.com.cn/*"
}
```
