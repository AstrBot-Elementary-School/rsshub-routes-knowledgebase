# dbaplus社群 - 活动

## Coverage
`index-only`

## Route
- Namespace: `dbaplus`
- Namespace Name: `dbaplus社群`
- Route Path: `/dbaplus/activity/:type?`
- Route Name: `活动`
- Example: `/dbaplus/activity`
- URL: `dbaplus.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `activity.ts`
- Source Module: `_None_`

## Description
| 线上分享 | 线下峰会 |
| -------- | -------- |
| online   | offline  |

## Parameters
- `type`: 分类，见下表，默认为线上分享


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 线上分享 | 线下峰会 |\n| -------- | -------- |\n| online   | offline  |",
  "example": "/dbaplus/activity",
  "heat": 0,
  "location": "activity.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "活动",
  "parameters": {
    "type": "分类，见下表，默认为线上分享"
  },
  "path": "/activity/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
