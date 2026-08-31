# hashnode - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `hashnode`
- Namespace Name: `hashnode`
- Route Path: `/hashnode/blog/:username`
- Route Name: `用户博客`
- Example: `/hashnode/blog/inklings`
- URL: `hashnode.dev/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `hnrainll`
- Source Location: `blog.tsx`
- Source Module: `_None_`

## Description
::: tip
username 为博主用户名，而非`xxx.hashnode.dev`中`xxx`所代表的 blog 地址。
:::

## Parameters
- `username`: 博主名称，用户头像 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hashnode.dev/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "::: tip\nusername 为博主用户名，而非`xxx.hashnode.dev`中`xxx`所代表的 blog 地址。\n:::",
  "example": "/hashnode/blog/inklings",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "blog.tsx",
  "maintainers": [
    "hnrainll"
  ],
  "name": "用户博客",
  "parameters": {
    "username": "博主名称，用户头像 URL 中找到"
  },
  "path": "/blog/:username",
  "radar": [
    {
      "source": [
        "hashnode.dev/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "hashnode.dev/"
}
```
