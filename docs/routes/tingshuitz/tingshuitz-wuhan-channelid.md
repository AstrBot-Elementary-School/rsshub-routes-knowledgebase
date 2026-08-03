# 停水通知 - 武汉市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/tingshuitz/wuhan/:channelId?`
- Route Name: `武汉市`
- Example: `/tingshuitz/wuhan`
- URL: `whwater.com/IWater.shtml`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `MoonBegonia`
- Source Location: `wuhan.ts`
- Source Module: `_None_`

## Description
| channelId | 分类       |
| --------- | ---------- |
| 68        | 计划性停水 |
| 69        | 突发性停水 |

## Parameters
- `channelId`: 分类，见下表，默认为 68


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `whwater.com/IWater.shtml`
  - `whwater.com/`
- `target`: `/wuhan`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| channelId | 分类       |\n| --------- | ---------- |\n| 68        | 计划性停水 |\n| 69        | 突发性停水 |",
  "example": "/tingshuitz/wuhan",
  "heat": 0,
  "location": "wuhan.ts",
  "maintainers": [
    "MoonBegonia"
  ],
  "name": "武汉市",
  "parameters": {
    "channelId": "分类，见下表，默认为 68"
  },
  "path": "/wuhan/:channelId?",
  "radar": [
    {
      "source": [
        "whwater.com/IWater.shtml",
        "whwater.com/"
      ],
      "target": "/wuhan"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "whwater.com/IWater.shtml"
}
```
