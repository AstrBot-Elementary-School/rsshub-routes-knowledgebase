# AIAA Aerospace Research Central - ASR Articles

## Coverage
`index-only`

## Route
- Namespace: `aiaa`
- Namespace Name: `AIAA Aerospace Research Central`
- Route Path: `/aiaa/journal/:journalID`
- Route Name: `ASR Articles`
- Example: `/aiaa/journal/aiaaj`
- URL: `arc.aiaa.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `HappyZhu99`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journalID`: journal ID, can be found in the URL


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
  "example": "/aiaa/journal/aiaaj",
  "heat": 0,
  "location": "journal.ts",
  "maintainers": [
    "HappyZhu99"
  ],
  "name": "ASR Articles",
  "parameters": {
    "journalID": "journal ID, can be found in the URL"
  },
  "path": "/journal/:journalID",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
