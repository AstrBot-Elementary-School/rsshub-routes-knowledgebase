# Shanghai Museum - Special Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `shanghaimuseum`
- Namespace Name: `Shanghai Museum`
- Route Path: `/shanghaimuseum/display/offline-exhibit/:type?`
- Route Name: `Special Exhibitions`
- Example: `/shanghaimuseum/display/offline-exhibit/PRESENT`
- URL: `www.shanghaimuseum.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `offline-exhibit.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: PRESENT (当期展览) | PAST (往期展览). Default: All exhibitions (both PRESENT and PAST).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shanghaimuseum.cn/mu/frontend/pg/display/offline-exhibit`
- `target`: `/display/offline-exhibit`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/shanghaimuseum/display/offline-exhibit/PRESENT",
  "heat": 0,
  "location": "offline-exhibit.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Special Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: PRESENT (当期展览) | PAST (往期展览). Default: All exhibitions (both PRESENT and PAST)."
  },
  "path": "/display/offline-exhibit/:type?",
  "radar": [
    {
      "source": [
        "www.shanghaimuseum.cn/mu/frontend/pg/display/offline-exhibit"
      ],
      "target": "/display/offline-exhibit"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
