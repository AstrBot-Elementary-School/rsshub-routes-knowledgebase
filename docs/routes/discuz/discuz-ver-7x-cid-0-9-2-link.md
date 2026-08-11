# Discuz - 通用子版块

## Coverage
`index-only`

## Route
- Namespace: `discuz`
- Namespace Name: `Discuz`
- Route Path: `/discuz/:ver{[7x]}/:cid{[0-9]{2}}/:link{.+}`
- Route Name: `通用子版块`
- Example: `/discuz/x/https%3a%2f%2fwww.52pojie.cn%2fforum-16-1.html`
- URL: `https://www.discuz.vip/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `junfengP, pseudoyu`
- Source Location: `discuz.ts`
- Source Module: `_None_`

## Description
| Discuz X Series | Discuz 7.x Series |
| --------------- | ----------------- |
| x               | 7                 |

## Parameters
- `ver`: discuz version，see below table
- `cid`: Cookie id，require self hosted and set environment parameters, see Deploy - Configuration pages for detail
- `link`: link of subforum, require url encoded


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| Discuz X Series | Discuz 7.x Series |\n| --------------- | ----------------- |\n| x               | 7                 |",
  "example": "/discuz/x/https%3a%2f%2fwww.52pojie.cn%2fforum-16-1.html",
  "heat": 0,
  "location": "discuz.ts",
  "maintainers": [
    "junfengP",
    "pseudoyu"
  ],
  "name": "通用子版块",
  "parameters": {
    "cid": "Cookie id，require self hosted and set environment parameters, see Deploy - Configuration pages for detail",
    "link": "link of subforum, require url encoded",
    "ver": "discuz version，see below table"
  },
  "path": [
    "/:ver{[7x]}/:cid{[0-9]{2}}/:link{.+}",
    "/:ver{[7x]}/:link{.+}",
    "/:link{.+}"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
