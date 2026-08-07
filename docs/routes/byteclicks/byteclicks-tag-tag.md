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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人工智能 - 字节点击 - Powered by RSSHub",
      "errorAt": "2026-08-05T22:06:05.517Z",
      "errorMessage": "[GET] \"https://byteclicks.com/wp-json/wp/v2/tags?search=%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD&per_page=100\": 403 Forbidden\n[GET] \"https://byteclicks.com/tag/人工智能\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 103.57.13.235:443, 103.57.13.234:443, 103.57.13.233:443, 103.57.13.237:443, 103.57.13.232:443, 103.57.13.231:443, 103.57.13.229:443, 103.57.13.230:443, timeout: 10000ms))\n",
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
