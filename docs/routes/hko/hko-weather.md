# Hong Kong Observatory - Current Weather Report

## Coverage
`index-only`

## Route
- Namespace: `hko`
- Namespace Name: `Hong Kong Observatory`
- Route Path: `/hko/weather`
- Route Name: `Current Weather Report`
- Example: `/hko/weather`
- URL: `www.weather.gov.hk/en/wxinfo/currwx/current.htm`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `calpa`
- Source Location: `weather.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.weather.gov.hk/en/wxinfo/currwx/current.htm`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/hko/weather",
  "heat": 5,
  "location": "weather.ts",
  "maintainers": [
    "calpa"
  ],
  "name": "Current Weather Report",
  "path": "/weather",
  "radar": [
    {
      "source": [
        "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(28) ] to not include '\\n      http://rss.weather.gov.hk/rss…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "provided by the Hong Kong Observatory: Thu, 06 Aug 2026 19:02:00 GMT - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69176555091531776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.weather.gov.hk/en/wxinfo/currwx/current.htm",
      "title": "Current Weather Report",
      "type": "feed",
      "url": "rsshub://hko/weather"
    }
  ],
  "url": "www.weather.gov.hk/en/wxinfo/currwx/current.htm"
}
```
