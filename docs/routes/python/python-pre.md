# Python - 版本发布

## Coverage
`index-only`

## Route
- Namespace: `python`
- Namespace Name: `Python`
- Route Path: `/python/:pre?`
- Route Name: `版本发布`
- Example: `/python`
- URL: `python.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `trim21`
- Source Location: `downloads.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pre`: 填入 `pre` 以包含预发布版本，默认只含正式版本


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/python",
  "heat": 0,
  "location": "downloads.ts",
  "maintainers": [
    "trim21"
  ],
  "name": "版本发布",
  "parameters": {
    "pre": "填入 `pre` 以包含预发布版本，默认只含正式版本"
  },
  "path": "/:pre?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 321069197391 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
