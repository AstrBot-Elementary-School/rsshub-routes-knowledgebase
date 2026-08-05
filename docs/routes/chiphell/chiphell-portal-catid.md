# Chiphell - 分类

## Coverage
`index-only`

## Route
- Namespace: `chiphell`
- Namespace Name: `Chiphell`
- Route Path: `/chiphell/portal/:catId?`
- Route Name: `分类`
- Example: `/chiphell/portal/1`
- URL: `www.chiphell.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `tylinux`
- Source Location: `portal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `catId`: 分类 ID，可在 URL 中找到，默认为 1


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
  "example": "/chiphell/portal/1",
  "heat": 89,
  "location": "portal.ts",
  "maintainers": [
    "tylinux"
  ],
  "name": "分类",
  "parameters": {
    "catId": "分类 ID，可在 URL 中找到，默认为 1"
  },
  "path": "/portal/:catId?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "评测 ,Chiphell - 分享与交流用户体验 - Powered by RSSHub",
      "errorAt": "2025-11-25T01:04:36.524Z",
      "errorMessage": "[GET] \"https://www.chiphell.com/portal.php?mod=list&catid=1\": 567 Unknown Status\n",
      "id": "155314423251107840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chiphell.com/portal.php?mod=list&catid=1",
      "title": "评测 - Chiphell - 分享与交流用户体验",
      "type": "feed",
      "url": "rsshub://chiphell/portal"
    },
    {
      "description": "评测 ,Chiphell - 分享与交流用户体验 - Powered by RSSHub",
      "errorAt": "2025-11-25T00:07:35.552Z",
      "errorMessage": "[GET] \"https://www.chiphell.com/portal.php?mod=list&catid=1\": 567 Unknown Status\n[GET] \"https://www.chiphell.com/portal.php?mod=list&catid=1\": 567 Unknown Status\n[GET] \"https://www.chiphell.com/portal.php?mod=list&catid=1\": 567 Unknown Status\n",
      "id": "154175981513858048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chiphell.com/portal.php?mod=list&catid=1",
      "title": "评测 - Chiphell - 分享与交流用户体验",
      "type": "feed",
      "url": "rsshub://chiphell/portal/1"
    }
  ]
}
```
