# Air-Level - 空气质量排行

## Coverage
`index-only`

## Route
- Namespace: `air-level`
- Namespace Name: `Air-Level`
- Route Path: `/air-level/rank/:status?`
- Route Name: `空气质量排行`
- Example: `/air-level/rank/best,/air-level/rank`
- URL: `air-level.com`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `lifetraveler`
- Source Location: `levelrank.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `status`: 地区


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.air-level.com/rank/:status`
  - `m.air-level.com/rank`
- `target`: `/rank/:status`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/air-level/rank/best,/air-level/rank",
  "heat": 3,
  "location": "levelrank.ts",
  "maintainers": [
    "lifetraveler"
  ],
  "name": "空气质量排行",
  "parameters": {
    "status": "地区"
  },
  "path": "/rank/:status?",
  "radar": [
    {
      "source": [
        "m.air-level.com/rank/:status",
        "m.air-level.com/rank"
      ],
      "target": "/rank/:status"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 404 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "空气质量排行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84881942044598272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.air-level.com/rank",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://air-level/rank/best"
    }
  ]
}
```
