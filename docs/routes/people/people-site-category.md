# 人民网 - 首页头条

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/people/:site?/:category{.+}?`
- Route Name: `首页头条`
- Example: `/people`
- URL: `people.com.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/people",
  "heat": 352,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "首页头条",
  "path": "/:site?/:category{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(2) ] to not include 'http://society.people.com.cn/n1/2026/…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人民日报重要言论库--观点--人民网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73227336896093184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://opinion.people.com.cn/GB/8213/49160",
      "title": "人民日报重要言论库--观点--人民网",
      "type": "feed",
      "url": "rsshub://people/opinion/8213/49160"
    },
    {
      "description": "首页头条--人民网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59474368564173825",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.people.com.cn/GB/59476",
      "title": "首页头条--人民网",
      "type": "feed",
      "url": "rsshub://people"
    }
  ]
}
```
