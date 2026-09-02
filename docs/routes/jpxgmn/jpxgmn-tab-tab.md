# 极品性感美女 - 分类

## Coverage
`index-only`

## Route
- Namespace: `jpxgmn`
- Namespace Name: `极品性感美女`
- Route Path: `/jpxgmn/tab/:tab?`
- Route Name: `分类`
- Example: `/jpxgmn/tab`
- URL: `www.jpxgmn.com`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `Urabartin`
- Source Location: `tab.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tab`: 分类，默认为`top`，包括`top`、`new`、`hot`，以及[源网站](http://www.jpxgmn.com/)所包含的其他相对路径，比如`Xiuren`、`XiaoYu`等


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mei5.vip/:tab`
- `target`: `/:tab`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/jpxgmn/tab",
  "features": {
    "nsfw": true
  },
  "heat": 1703,
  "location": "tab.ts",
  "maintainers": [
    "Urabartin"
  ],
  "name": "分类",
  "parameters": {
    "tab": "分类，默认为`top`，包括`top`、`new`、`hot`，以及[源网站](http://www.jpxgmn.com/)所包含的其他相对路径，比如`Xiuren`、`XiaoYu`等"
  },
  "path": "/tab/:tab?",
  "radar": [
    {
      "source": [
        "mei5.vip/:tab"
      ],
      "target": "/:tab"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "极品性感美女 - 推荐美女 - Powered by RSSHub",
      "errorAt": "2026-01-22T07:31:26.090Z",
      "errorMessage": "Failed to fetch\nInvalid RSSHub JSON Feed from 98292582055262208\n[GET] \"http:///top.html\": <no response> fetch failed (getaddrinfo ENOTFOUND top.html)\n[GET] \"http:///top.html\": <no response> fetch failed (getaddrinfo ENOTFOUND top.html)\n[GET] \"http:///top.html\": <no response> fetch failed\nAuthentication failed. Access denied.\n/jpxgmn/tab\n[GET] \"http:///top.html\": <no response> fetch failed\n530 \n[GET] \"http:///top.html\": <no response> fetch failed (getaddrinfo ENOTFOUND top.html)\n[GET] \"http:///top.html\": <no response> fetch failed (getaddrinfo ENOTFOUND top.html)\n[GET] \"http:///top.html\": <no response> fetch failed (getaddrinfo ENOTFOUND top.html)\n",
      "id": "57074574176806961",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://a1.876512.xyz/top.html",
      "title": "极品性感美女 - 推荐美女",
      "type": "feed",
      "url": "rsshub://jpxgmn/tab"
    },
    {
      "description": "极品性感美女 - 热门美女 - Powered by RSSHub",
      "errorAt": "2025-10-09T03:44:04.191Z",
      "errorMessage": "Failed to fetch\n530 \n[GET] \"http:///hot.html\": <no response> fetch failed\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n[GET] \"http:///hot.html\": <no response> fetch failed (getaddrinfo ENOTFOUND hot.html)\n",
      "id": "57074574176806959",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://a.876519.xyz/hot.html",
      "title": "极品性感美女 - 热门美女",
      "type": "feed",
      "url": "rsshub://jpxgmn/tab/hot"
    }
  ]
}
```
