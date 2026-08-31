# 起点 - 讨论区

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/qidian/forum/:id`
- Route Name: `讨论区`
- Example: `/qidian/forum/1010400217`
- URL: `qidian.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `fuzy112, pseudoyu`
- Source Location: `forum.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `book.qidian.com/info/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/forum/1010400217",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "forum.ts",
  "maintainers": [
    "fuzy112",
    "pseudoyu"
  ],
  "name": "讨论区",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/forum/:id",
  "radar": [
    {
      "source": [
        "book.qidian.com/info/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://book.qidian.com/info/10104002…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
