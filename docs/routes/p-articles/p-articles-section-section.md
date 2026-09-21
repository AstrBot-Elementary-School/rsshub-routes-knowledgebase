# 虚词 - 版块

## Coverage
`index-only`

## Route
- Namespace: `p-articles`
- Namespace Name: `虚词`
- Route Path: `/p-articles/section/:section`
- Route Name: `版块`
- Example: `/p-articles/section/critics`
- URL: `p-articles.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `Insomnia1437`
- Source Location: `section.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `section`: 版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `p-articles.com/:section/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/p-articles/section/critics",
  "heat": 38,
  "location": "section.ts",
  "maintainers": [
    "Insomnia1437"
  ],
  "name": "版块",
  "parameters": {
    "section": "版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接"
  },
  "path": "/section/:section",
  "radar": [
    {
      "source": [
        "p-articles.com/:section/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "虚词 p-articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53733146806773766",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://p-articles.com/works/",
      "title": "虚词 p-articles",
      "type": "feed",
      "url": "rsshub://p-articles/section/works"
    },
    {
      "description": "虚词 p-articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98011535417850904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://p-articles.com/critics/",
      "title": "虚词 p-articles",
      "type": "feed",
      "url": "rsshub://p-articles/section/critics"
    }
  ]
}
```
