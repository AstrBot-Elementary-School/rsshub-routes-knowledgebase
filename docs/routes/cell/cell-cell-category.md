# Cell - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `cell`
- Namespace Name: `Cell`
- Route Path: `/cell/cell/:category`
- Route Name: `Current Issue`
- Example: `/cell/cell/current`
- URL: `www.cell.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c`
- Source Location: `cell.ts`
- Source Module: `_None_`

## Description
| `:category` |        Query Type       |
| :---------: | :---------------------: |
|   current   | Current Issue (default) |
|   inpress   |    Articles in press    |

## Parameters
- `category`: Query type, see the table below


## Features
- `supportScihub`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| `:category` |        Query Type       |\n| :---------: | :---------------------: |\n|   current   | Current Issue (default) |\n|   inpress   |    Articles in press    |",
  "example": "/cell/cell/current",
  "features": {
    "supportScihub": true
  },
  "heat": 0,
  "location": "cell.ts",
  "maintainers": [
    "y9c"
  ],
  "name": "Current Issue",
  "parameters": {
    "category": "Query type, see the table below"
  },
  "path": "/cell/:category",
  "topFeeds": []
}
```
