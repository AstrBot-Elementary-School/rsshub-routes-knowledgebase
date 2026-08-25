# Deepin - BBS Home Page

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/deepin/homepage/:user_id`
- Route Name: `BBS Home Page`
- Example: `/deepin/homepage/78326`
- URL: `bbs.deepin.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `tensor-tech`
- Source Location: `homepage.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: user id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org/user/:user_id`
- `target`: `/homepage/:user_id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/homepage/78326",
  "heat": 2,
  "location": "homepage.ts",
  "maintainers": [
    "tensor-tech"
  ],
  "name": "BBS Home Page",
  "parameters": {
    "user_id": "user id"
  },
  "path": "/homepage/:user_id",
  "radar": [
    {
      "source": [
        "bbs.deepin.org/user/:user_id"
      ],
      "target": "/homepage/:user_id"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "广雅居士/deepin论坛主页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63580812692062208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/user/78326",
      "title": "广雅居士/deepin论坛主页",
      "type": "feed",
      "url": "rsshub://deepin/homepage/78326"
    }
  ]
}
```
