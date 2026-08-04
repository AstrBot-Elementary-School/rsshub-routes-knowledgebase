# 印记中文 - 周刊 - JavaScript

## Coverage
`index-only`

## Route
- Namespace: `docschina`
- Namespace Name: `印记中文`
- Route Path: `/docschina/weekly/:category?`
- Route Name: `周刊 - JavaScript`
- Example: `/docschina/weekly`
- URL: `docschina.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `daijinru, hestudy`
- Source Location: `weekly.ts`
- Source Module: `_None_`

## Description
| javascript | node | react |
| ---------- | ---- | ----- |
| js         | node | react |

## Parameters
- `category`: 周刊分类，见下表，默认为js


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `docschina.org/news/weekly/js/*`
  - `docschina.org/news/weekly/js`
  - `docschina.org/`
- `target`: `/jsweekly`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| javascript | node | react |\n| ---------- | ---- | ----- |\n| js         | node | react |",
  "example": "/docschina/weekly",
  "heat": 269,
  "location": "weekly.ts",
  "maintainers": [
    "daijinru",
    "hestudy"
  ],
  "name": "周刊 - JavaScript",
  "parameters": {
    "category": "周刊分类，见下表，默认为js"
  },
  "path": "/weekly/:category?",
  "radar": [
    {
      "source": [
        "docschina.org/news/weekly/js/*",
        "docschina.org/news/weekly/js",
        "docschina.org/"
      ],
      "target": "/jsweekly"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "印记中文 - 深入挖掘国外前端新领域，为国内 Web 前端开发人员提供优质文档！ - Powered by RSSHub",
      "errorAt": "2026-06-20T14:54:51.771Z",
      "errorMessage": "[GET] \"https://docschina.org/news/weekly/js\": <no response> fetch failed (certificate has expired)\n[GET] \"https://docschina.org/news/weekly/js\": <no response> fetch failed (Connect Timeout Error (attempted address: docschina.org:443, timeout: 10000ms))\n",
      "id": "42759639011832832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docschina.org/news/weekly/js",
      "title": "印记中文 - 深入挖掘国外前端新领域，为国内 Web 前端开发人员提供优质文档！",
      "type": "feed",
      "url": "rsshub://docschina/weekly"
    },
    {
      "description": "印记中文 - 深入挖掘国外前端新领域，为国内 Web 前端开发人员提供优质文档！ - Powered by RSSHub",
      "errorAt": "2026-07-05T11:50:31.390Z",
      "errorMessage": "[GET] \"https://docschina.org/news/weekly/node\": <no response> fetch failed (certificate has expired)\n",
      "id": "70318276834867203",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docschina.org/news/weekly/node",
      "title": "印记中文 - 深入挖掘国外前端新领域，为国内 Web 前端开发人员提供优质文档！",
      "type": "feed",
      "url": "rsshub://docschina/weekly/node"
    }
  ]
}
```
