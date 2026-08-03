# TradingView - Pine Script™ Release notes

## Coverage
`index-only`

## Route
- Namespace: `tradingview`
- Namespace Name: `TradingView`
- Route Path: `/tradingview/pine/:version?`
- Route Name: `Pine Script™ Release notes`
- Example: `/tradingview/pine`
- URL: `tradingview.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `pine.ts`
- Source Module: `_None_`

## Description
| v5 | v4 |
| -- | -- |

## Parameters
- `version`: Version, see below, `v5` by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `tradingview.com/pine-script-docs/en/:version/Release_notes.html`
- `target`: `/pine/:version`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| v5 | v4 |\n| -- | -- |",
  "example": "/tradingview/pine",
  "heat": 0,
  "location": "pine.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Pine Script™ Release notes",
  "parameters": {
    "version": "Version, see below, `v5` by default"
  },
  "path": "/pine/:version?",
  "radar": [
    {
      "source": [
        "tradingview.com/pine-script-docs/en/:version/Release_notes.html"
      ],
      "target": "/pine/:version"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
