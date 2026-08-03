# 香港 01 - 专题

## Coverage
`index-only`

## Route
- Namespace: `hk01`
- Namespace Name: `香港 01`
- Route Path: `/hk01/issue/:id?`
- Route Name: `专题`
- Example: `/hk01/issue/649`
- URL: `hk01.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `hoilc, Fatpandac, nczitzk`
- Source Location: `issue.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专题 id, 可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hk01.com/issue/:id`
  - `hk01.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hk01/issue/649",
  "heat": 0,
  "location": "issue.ts",
  "maintainers": [
    "hoilc",
    "Fatpandac",
    "nczitzk"
  ],
  "name": "专题",
  "parameters": {
    "id": "专题 id, 可在 URL 中找到"
  },
  "path": "/issue/:id?",
  "radar": [
    {
      "source": [
        "hk01.com/issue/:id",
        "hk01.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
