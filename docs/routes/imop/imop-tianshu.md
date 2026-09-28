# imop - 全部消息

## Coverage
`index-only`

## Route
- Namespace: `imop`
- Namespace Name: `imop`
- Route Path: `/imop/tianshu`
- Route Name: `全部消息`
- Example: `/imop/tianshu`
- URL: `imop.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `zhkgo`
- Source Location: `tianshu.ts`
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
  - `t.imop.com`
- `target`: `/tianshu`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/imop/tianshu",
  "heat": 1,
  "location": "tianshu.ts",
  "maintainers": [
    "zhkgo"
  ],
  "name": "全部消息",
  "path": "/tianshu",
  "radar": [
    {
      "source": [
        "t.imop.com"
      ],
      "target": "/tianshu"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "天书最新消息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74073602902251520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://t.imop.com/list/0-1.htm",
      "title": "天书最新消息",
      "type": "feed",
      "url": "rsshub://imop/tianshu"
    }
  ]
}
```
