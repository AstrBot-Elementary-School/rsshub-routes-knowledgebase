# 环球法律评论 - 期刊

## Coverage
`index-only`

## Route
- Namespace: `globallawreview`
- Namespace Name: `环球法律评论`
- Route Path: `/globallawreview/`
- Route Name: `期刊`
- Example: `/globallawreview`
- URL: `globallawreview.org/Magazine/GetIssueContentList`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `globallawreview.org/Magazine/GetIssueContentList`
  - `globallawreview.org/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/globallawreview",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "期刊",
  "path": "/",
  "radar": [
    {
      "source": [
        "globallawreview.org/Magazine/GetIssueContentList",
        "globallawreview.org/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "globallawreview.org/Magazine/GetIssueContentList"
}
```
