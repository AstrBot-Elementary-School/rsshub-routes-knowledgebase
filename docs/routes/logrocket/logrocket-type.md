# logrocket blog - Blog

## Coverage
`index-only`

## Route
- Namespace: `logrocket`
- Namespace Name: `logrocket blog`
- Route Path: `/logrocket/:type`
- Route Name: `Blog`
- Example: `/logrocket/dev`
- URL: `blog.logrocket.com/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `findwei`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: dev | product-management | ux-design


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `blog.logrocket.com`
- `target`: `/dev`
### Rule 2
- `source`:
  - `blog.logrocket.com/dev`
- `target`: `/dev`
### Rule 3
- `source`:
  - `blog.logrocket.com/product-management`
- `target`: `/product-management`
### Rule 4
- `source`:
  - `blog.logrocket.com/ux-design`
- `target`: `/ux-design`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/logrocket/dev",
  "heat": 8,
  "location": "index.ts",
  "maintainers": [
    "findwei"
  ],
  "name": "Blog",
  "parameters": {
    "type": "dev | product-management | ux-design"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "blog.logrocket.com"
      ],
      "target": "/dev"
    },
    {
      "source": [
        "blog.logrocket.com/dev"
      ],
      "target": "/dev"
    },
    {
      "source": [
        "blog.logrocket.com/product-management"
      ],
      "target": "/product-management"
    },
    {
      "source": [
        "blog.logrocket.com/ux-design"
      ],
      "target": "/ux-design"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:64:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:90:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:109:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "logrocket-Dev - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80088309178667008",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.logrocket.com/",
      "title": "logrocket-Dev",
      "type": "feed",
      "url": "rsshub://logrocket/dev"
    }
  ],
  "url": "blog.logrocket.com/"
}
```
