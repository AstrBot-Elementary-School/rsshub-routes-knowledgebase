# U.S. Department of the Treasury - Press Releases

## Coverage
`index-only`

## Route
- Namespace: `treasury`
- Namespace Name: `U.S. Department of the Treasury`
- Route Path: `/treasury/press-releases/:category?/:title?`
- Route Name: `Press Releases`
- Example: `/treasury/press-releases`
- URL: `home.treasury.gov`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `press-releases.ts`
- Source Module: `_None_`

## Description
Category

| Press Releases | Statements & Remarks | Readouts | Testimonies |
| -------------- | -------------------- | -------- | ----------- |
| all            | statements-remarks   | readouts | testimonies |

## Parameters
- `category`: Category, see below, all by default
- `title`: Title keywords, empty by default


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Category\n\n| Press Releases | Statements & Remarks | Readouts | Testimonies |\n| -------------- | -------------------- | -------- | ----------- |\n| all            | statements-remarks   | readouts | testimonies |",
  "example": "/treasury/press-releases",
  "heat": 0,
  "location": "press-releases.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Press Releases",
  "parameters": {
    "category": "Category, see below, all by default",
    "title": "Title keywords, empty by default"
  },
  "path": "/press-releases/:category?/:title?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
