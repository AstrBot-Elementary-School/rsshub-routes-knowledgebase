# Inoreader - HTML Clip

## Coverage
`index-only`

## Route
- Namespace: `inoreader`
- Namespace Name: `Inoreader`
- Route Path: `/inoreader/html_clip/:user/:tag`
- Route Name: `HTML Clip`
- Example: `/inoreader/html_clip/1005137674/user-favorites`
- URL: `inoreader.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `IvanWng97`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: User id, can be found in the HTML clip URL
- `tag`: Tag name, can be found in the HTML clip URL


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/inoreader/html_clip/1005137674/user-favorites",
  "heat": 9,
  "location": "index.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "HTML Clip",
  "parameters": {
    "tag": "Tag name, can be found in the HTML clip URL",
    "user": "User id, can be found in the HTML clip URL"
  },
  "path": "/html_clip/:user/:tag",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Yifan's favorite articles on Inoreader - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73156704664542208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.inoreader.com/stream/user/1005137674/tag/user-favorites/view/html?n=20",
      "title": "Yifan's favorite articles on Inoreader",
      "type": "feed",
      "url": "rsshub://inoreader/html_clip/1005137674/user-favorites"
    },
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "120745013178740736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.inoreader.com/stream/user/:user/tag/:tag/view/html?n=20",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://inoreader/html_clip/:user/:tag"
    }
  ],
  "view": 0
}
```
