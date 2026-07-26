# Anthropic - Frontier Red Team

## Coverage
`index-only`

## Route
- Namespace: `anthropic`
- Namespace Name: `Anthropic`
- Route Path: `/anthropic/red`
- Route Name: `Frontier Red Team`
- Example: `/anthropic/red`
- URL: `red.anthropic.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `shoeper`
- Source Location: `red.ts`
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
  - `red.anthropic.com`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/anthropic/red",
  "heat": 10,
  "location": "red.ts",
  "maintainers": [
    "shoeper"
  ],
  "name": "Frontier Red Team",
  "path": "/red",
  "radar": [
    {
      "source": [
        "red.anthropic.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Anthropic Frontier Red Team - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "230531103133701120",
      "image": "https://red.anthropic.com/anthropic-serve/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://red.anthropic.com/red",
      "title": "Anthropic Frontier Red Team",
      "type": "feed",
      "url": "rsshub://anthropic/red"
    }
  ],
  "url": "red.anthropic.com"
}
```
