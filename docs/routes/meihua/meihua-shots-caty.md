# 梅花网 - 作品

## Coverage
`index-only`

## Route
- Namespace: `meihua`
- Namespace Name: `梅花网`
- Route Path: `/meihua/shots/:caty`
- Route Name: `作品`
- Example: `/meihua/shots/latest`
- URL: `www.meihua.info`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `shots.ts`
- Source Module: `_None_`

## Description
| 最新   | 热门 | 推荐      |
| ------ | ---- | --------- |
| latest | hot  | recommend |

## Parameters
- `caty`: 分类，见下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新   | 热门 | 推荐      |\n| ------ | ---- | --------- |\n| latest | hot  | recommend |",
  "example": "/meihua/shots/latest",
  "heat": 0,
  "location": "shots.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "作品",
  "parameters": {
    "caty": "分类，见下表"
  },
  "path": "/shots/:caty",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
