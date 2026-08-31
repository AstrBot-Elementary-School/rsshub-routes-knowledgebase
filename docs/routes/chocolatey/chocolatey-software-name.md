# Chocolatey - Software Update

## Coverage
`index-only`

## Route
- Namespace: `chocolatey`
- Namespace Name: `Chocolatey`
- Route Path: `/chocolatey/software/:name?`
- Route Name: `Software Update`
- Example: `/chocolatey/software/GoogleChrome`
- URL: `chocolatey.org`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `woodgear`
- Source Location: `software.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Software name


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
  "example": "/chocolatey/software/GoogleChrome",
  "heat": 0,
  "location": "software.ts",
  "maintainers": [
    "woodgear"
  ],
  "name": "Software Update",
  "parameters": {
    "name": "Software name"
  },
  "path": "/software/:name?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 311131152784 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
