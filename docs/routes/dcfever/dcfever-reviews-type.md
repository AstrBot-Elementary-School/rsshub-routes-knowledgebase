# DCFever - 測試報告

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/dcfever/reviews/:type?`
- Route Name: `測試報告`
- Example: `/dcfever/reviews/cameras`
- URL: `dcfever.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `reviews.ts`
- Source Module: `_None_`

## Description
| 相機及鏡頭 | 手機平板 | 試車報告 |
| ---------- | -------- | -------- |
| cameras    | phones   | cars     |

## Parameters
- `type`: 分類，預設為 `cameras`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dcfever.com/:type/reviews.php`
- `target`: `/reviews/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 相機及鏡頭 | 手機平板 | 試車報告 |\n| ---------- | -------- | -------- |\n| cameras    | phones   | cars     |",
  "example": "/dcfever/reviews/cameras",
  "heat": 30,
  "location": "reviews.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "測試報告",
  "parameters": {
    "type": "分類，預設為 `cameras`"
  },
  "path": "/reviews/:type?",
  "radar": [
    {
      "source": [
        "dcfever.com/:type/reviews.php"
      ],
      "target": "/reviews/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(3) ] to not include 'https://www.dcfever.com/news/readnews…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "相機及鏡頭測試報告 Camera and Lens Reviews - DCFever.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84292992343678976",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/cameras/reviews.php",
      "title": "相機及鏡頭測試報告 Camera and Lens Reviews - DCFever.com",
      "type": "feed",
      "url": "rsshub://dcfever/reviews"
    },
    {
      "description": "手機平板電腦測試報告 - DCFever.com - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63944676322037760",
      "image": "https://cdn10.dcfever.com/images/android_192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.dcfever.com/phones/reviews.php",
      "title": "手機平板電腦測試報告 - DCFever.com",
      "type": "feed",
      "url": "rsshub://dcfever/reviews/phones"
    }
  ]
}
```
