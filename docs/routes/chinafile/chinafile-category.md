# ChinaFile - Reporting & Opinion

## Coverage
`index-only`

## Route
- Namespace: `chinafile`
- Namespace Name: `ChinaFile`
- Route Path: `/chinafile/:category?`
- Route Name: `Reporting & Opinion`
- Example: `/chinafile/all`
- URL: `www.chinafile.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `oppilate`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Generates full-text feeds that the official feed doesn't provide.

| All | The China NGO Project |
| --- | --------------------- |
| all | ngo                   |

## Parameters
- `category`: Category, by default `all`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Generates full-text feeds that the official feed doesn't provide.\n\n| All | The China NGO Project |\n| --- | --------------------- |\n| all | ngo                   |",
  "example": "/chinafile/all",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "oppilate"
  ],
  "name": "Reporting & Opinion",
  "parameters": {
    "category": "Category, by default `all`"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "China News, Analysis, Culture, Environment, Media - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "176986240301127681",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chinafile.com/",
      "title": "ChinaFile",
      "type": "feed",
      "url": "rsshub://chinafile/all"
    }
  ]
}
```
