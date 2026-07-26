# Hong Kong Observatory - 全球地震資訊網

## Coverage
`index-only`

## Route
- Namespace: `hko`
- Namespace Name: `Hong Kong Observatory`
- Route Path: `/hko/earthquake`
- Route Name: `全球地震資訊網`
- Example: `/hko/earthquake`
- URL: `www.hko.gov.hk`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `after9`
- Source Location: `earthquake.ts`
- Source Module: `_None_`

## Description
来自香港天文台的全球 5 级以上地震记录

## Parameters
_None_


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "来自香港天文台的全球 5 级以上地震记录",
  "example": "/hko/earthquake",
  "heat": 10,
  "location": "earthquake.ts",
  "maintainers": [
    "after9"
  ],
  "name": "全球地震資訊網",
  "path": "/earthquake",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ '[震級:5.9] [地點:里奧加耶戈斯, 阿根廷]', …(21) ] to not include '[震級:5] [地點:達沃, 菲律賓]'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "提供經天文台分析的全球5.0級或以上及本地有感的地震資訊。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69201588937562112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hko.gov.hk/tc/gts/equake/quake-info.htm",
      "title": "来自香港天文台的全球5级以上地震记录",
      "type": "feed",
      "url": "rsshub://hko/earthquake"
    }
  ]
}
```
