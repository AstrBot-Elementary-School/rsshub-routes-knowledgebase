# Literotica - Category

## Coverage
`index-only`

## Route
- Namespace: `literotica`
- Namespace Name: `Literotica`
- Route Path: `/literotica/category/:category`
- Route Name: `Category`
- Example: `/literotica/category/anal-sex-stories`
- URL: `literotica.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category, can be found in URL


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `literotica.com/c/:category`
  - `literotica.com/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/literotica/category/anal-sex-stories",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "category": "Category, can be found in URL"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "literotica.com/c/:category",
        "literotica.com/"
      ]
    }
  ],
  "topFeeds": []
}
```
