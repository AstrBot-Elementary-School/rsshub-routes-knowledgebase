# IEEE Xplore - IEEE Journal Articles

## Coverage
`index-only`

## Route
- Namespace: `ieee`
- Namespace Name: `IEEE Xplore`
- Route Path: `/ieee/journal/:punumber/:earlyAccess?`
- Route Name: `IEEE Journal Articles`
- Example: `/ieee/journal/6287639/preprint`
- URL: `www.ieee.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `HenryQW`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `punumber`: Publication Number, look for `punumber` in the URL
- `earlyAccess`: Optional, set any value to get early access articles


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ieee/journal/6287639/preprint",
  "heat": 262,
  "location": "journal.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "IEEE Journal Articles",
  "parameters": {
    "earlyAccess": "Optional, set any value to get early access articles",
    "punumber": "Publication Number, look for `punumber` in the URL"
  },
  "path": "/journal/:punumber/:earlyAccess?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "IEEE Access - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66654457230659584",
      "image": "https://ieeexplore.ieee.orgundefined",
      "ownerUserId": null,
      "siteUrl": "https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=6514899",
      "title": "IEEE Access",
      "type": "feed",
      "url": "rsshub://ieee/journal/6287639/preprint"
    },
    {
      "description": "IEEE Transactions on Geoscience and Remote Sensing - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61591456839305216",
      "image": "https://ieeexplore.ieee.orgundefined",
      "ownerUserId": null,
      "siteUrl": "https://ieeexplore.ieee.org/xpl/tocresult.jsp?isnumber=4358825",
      "title": "IEEE Transactions on Geoscience and Remote Sensing",
      "type": "feed",
      "url": "rsshub://ieee/journal/36/preprint"
    }
  ]
}
```
