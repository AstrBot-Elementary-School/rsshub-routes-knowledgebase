# WBV-GPA - Angebote

## Coverage
`index-only`

## Route
- Namespace: `wbv-gpa`
- Namespace Name: `WBV-GPA`
- Route Path: `/wbv-gpa/:category?/:state?`
- Route Name: `Angebote`
- Example: `/wbv-gpa/wohnungen/wien`
- URL: `wbv-gpa.at`
- Language: `_None_`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Search housing by WBV-GPA, see "Angebote" menu item in <https://www.wbv-gpa.at>.
Filtering by state is done client-side.

## Parameters
- `category`: Anything behind `/angebote/` in the URL. Default: `wohnungen`
- `state`: Optionally filter by Austrian state (`wien`, `steiermark`, ...)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wbv-gpa.at/wohnungen/`
- `target`: `/wohnungen`
### Rule 2
- `source`:
  - `www.wbv-gpa.at/angebote/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Search housing by WBV-GPA, see \"Angebote\" menu item in <https://www.wbv-gpa.at>.\nFiltering by state is done client-side.",
  "example": "/wbv-gpa/wohnungen/wien",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "name": "Angebote",
  "parameters": {
    "category": "Anything behind `/angebote/` in the URL. Default: `wohnungen`",
    "state": "Optionally filter by Austrian state (`wien`, `steiermark`, ...)"
  },
  "path": "/:category?/:state?",
  "radar": [
    {
      "source": [
        "www.wbv-gpa.at/wohnungen/"
      ],
      "target": "/wohnungen"
    },
    {
      "source": [
        "www.wbv-gpa.at/angebote/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
