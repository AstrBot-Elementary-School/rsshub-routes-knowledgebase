# Air-Level - 空气质量

## Coverage
`index-only`

## Route
- Namespace: `air-level`
- Namespace Name: `Air-Level`
- Route Path: `/air-level/air/:area`
- Route Name: `空气质量`
- Example: `/air-level/air/xian`
- URL: `air-level.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `lifetraveler`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `area`: 地区


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.air-level.com/air/:area/`
- `target`: `/air/:area`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/air-level/air/xian",
  "heat": 25,
  "location": "index.ts",
  "maintainers": [
    "lifetraveler"
  ],
  "name": "空气质量",
  "parameters": {
    "area": "地区"
  },
  "path": "/air/:area",
  "radar": [
    {
      "source": [
        "m.air-level.com/air/:area/"
      ],
      "target": "/air/:area"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:69:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "订阅每个城市的天气质量 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81563872281993216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.air-level.com/air/shanghai",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://air-level/air/shanghai"
    },
    {
      "description": "订阅每个城市的天气质量 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "146122544518077440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.air-level.com/air/suzhou",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://air-level/air/suzhou"
    }
  ]
}
```
