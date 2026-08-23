# Nobel Prize - List

## Coverage
`index-only`

## Route
- Namespace: `nobelprize`
- Namespace Name: `Nobel Prize`
- Route Path: `/nobelprize/:caty?`
- Route Name: `List`
- Example: `/nobelprize`
- URL: `www.nobelprize.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Physics | Chemistry | Physiology or Medicine | Literature | Peace | Economic Science  |
| ------- | --------- | ---------------------- | ---------- | ----- | ----------------- |
| physics | chemistry | physiology-or-medicine | literature | peace | economic-sciences |

## Parameters
- `caty`: Category, see below, all by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| Physics | Chemistry | Physiology or Medicine | Literature | Peace | Economic Science  |\n| ------- | --------- | ---------------------- | ---------- | ----- | ----------------- |\n| physics | chemistry | physiology-or-medicine | literature | peace | economic-sciences |",
  "example": "/nobelprize",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "List",
  "parameters": {
    "caty": "Category, see below, all by default"
  },
  "path": "/:caty?",
  "topFeeds": []
}
```
