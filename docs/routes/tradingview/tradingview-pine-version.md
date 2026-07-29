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
  "topFeeds": []
}
```
