# 小黑盒 - 喜加一

## Coverage
`index-only`

## Route
- Namespace: `xiaoheihe`
- Namespace Name: `小黑盒`
- Route Path: `/xiaoheihe/add2cart/:platform`
- Route Name: `喜加一`
- Example: `/xiaoheihe/add2cart/epic`
- URL: `xiaoheihe.cn`
- Language: `_None_`
- Categories: `game`
- Maintainers: `ladeng07`
- Source Location: `add2cart.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `platform`: 平台名：epic、steam或gog


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/xiaoheihe/add2cart/epic",
  "heat": 443,
  "location": "add2cart.ts",
  "maintainers": [
    "ladeng07"
  ],
  "name": "喜加一",
  "parameters": {
    "platform": "平台名：epic、steam或gog"
  },
  "path": "/add2cart/:platform",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "小黑盒 EPIC 喜加一 - Powered by RSSHub",
      "errorAt": "2024-12-24T07:42:30.812Z",
      "errorMessage": "Failed to fetch\nInvalid RSSHub JSON Feed from 98292582055262208\nAuthentication failed. Access denied.\n/xiaoheihe/add2cart/epic\nCannot read properties of undefined (reading 'map')\n",
      "id": "58426420603331584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "小黑盒 EPIC 喜加一",
      "type": "feed",
      "url": "rsshub://xiaoheihe/add2cart/epic"
    },
    {
      "description": "小黑盒 STEAM 喜加一 - Powered by RSSHub",
      "errorAt": "2024-12-24T07:15:54.224Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "65390865249901568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xiaoheihe.cn/",
      "title": "小黑盒 STEAM 喜加一",
      "type": "feed",
      "url": "rsshub://xiaoheihe/add2cart/steam"
    }
  ]
}
```
