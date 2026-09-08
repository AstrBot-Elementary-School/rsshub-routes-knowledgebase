# PSN 中文站 - 节点

## Coverage
`index-only`

## Route
- Namespace: `psnine`
- Namespace Name: `PSN 中文站`
- Route Path: `/psnine/node/:id?/:order?`
- Route Name: `节点`
- Example: `/psnine/node/news`
- URL: `psnine.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `betta-cyber, nczitzk`
- Source Location: `node.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 节点 id，见下表，默认为 news
- `order`: 排序，`date` 即最新，默认为 `obdate` 即综合排序


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `psnine.com/node/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/psnine/node/news",
  "heat": 4,
  "location": "node.ts",
  "maintainers": [
    "betta-cyber",
    "nczitzk"
  ],
  "name": "节点",
  "parameters": {
    "id": "节点 id，见下表，默认为 news",
    "order": "排序，`date` 即最新，默认为 `obdate` 即综合排序"
  },
  "path": "/node/:id?/:order?",
  "radar": [
    {
      "source": [
        "psnine.com/node/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "「会免」最新讨论 - PSN中文站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "125916510049597440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.psnine.com/node/plus?ob=obdate",
      "title": "「会免」最新讨论 - PSN中文站",
      "type": "feed",
      "url": "rsshub://psnine/node/plus"
    },
    {
      "description": "「新闻」最新讨论 - PSN中文站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130453375930870784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.psnine.com/node/news?ob=obdate",
      "title": "「新闻」最新讨论 - PSN中文站",
      "type": "feed",
      "url": "rsshub://psnine/node/news"
    }
  ]
}
```
