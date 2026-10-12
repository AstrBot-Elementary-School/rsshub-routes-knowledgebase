# 萌番组 - Latest

## Coverage
`index-only`

## Route
- Namespace: `bangumi.moe`
- Namespace Name: `萌番组`
- Route Path: `/bangumi.moe/:tags{.+}?`
- Route Name: `Latest`
- Example: `/bangumi.moe`
- URL: `bangumi.moe/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tags`: Tags, empty by default, multiple tags separated by `/`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bangumi.moe/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.moe",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Latest",
  "parameters": {
    "tags": "Tags, empty by default, multiple tags separated by `/`"
  },
  "path": "/:tags{.+}?",
  "radar": [
    {
      "source": [
        "bangumi.moe/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "bangumi.moe/"
}
```
