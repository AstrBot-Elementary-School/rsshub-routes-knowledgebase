# 云谦的博客 - 文章

## Coverage
`index-only`

## Route
- Namespace: `sorrycc`
- Namespace Name: `云谦的博客`
- Route Path: `/sorrycc/`
- Route Name: `文章`
- Example: `/sorrycc`
- URL: `blog.sorrycc.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `KarasuShin`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
云谦的博客。受限文章仅包含网站公开提供的预览内容。

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `sorrycc.com`
- `target`: `/`
### Rule 2
- `source`:
  - `blog.sorrycc.com/`
  - `blog.sorrycc.com/*path`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "云谦的博客。受限文章仅包含网站公开提供的预览内容。",
  "example": "/sorrycc",
  "features": {
    "supportRadar": true
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "文章",
  "path": "/",
  "radar": [
    {
      "source": [
        "sorrycc.com"
      ],
      "target": "/"
    },
    {
      "source": [
        "blog.sorrycc.com/",
        "blog.sorrycc.com/*path"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 0
}
```
