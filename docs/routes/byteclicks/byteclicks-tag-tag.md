# 字节点击 - 标签

## Coverage
`index-only`

## Route
- Namespace: `byteclicks`
- Namespace Name: `字节点击`
- Route Path: `/byteclicks/tag/:tag`
- Route Name: `标签`
- Example: `/byteclicks/tag/人工智能`
- URL: `byteclicks.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: 标签，可在URL中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `byteclicks.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/byteclicks/tag/人工智能",
  "heat": 5,
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签，可在URL中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "byteclicks.com/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "人工智能 - 字节点击 - Powered by RSSHub",
      "errorAt": "2026-08-31T21:50:09.857Z",
      "errorMessage": "a.find is not a function\n[GET] \"https://byteclicks.com/tag/人工智能\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 58.30.207.163:443, 58.30.207.160:443, timeout: 10000ms))\n",
      "id": "63118600077338624",
      "image": "https://byteclicks.com/img/byte01.ico",
      "ownerUserId": null,
      "siteUrl": "https://byteclicks.com/tag/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD",
      "title": "人工智能 - 字节点击",
      "type": "feed",
      "url": "rsshub://byteclicks/tag/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD"
    }
  ],
  "url": "byteclicks.com/"
}
```
