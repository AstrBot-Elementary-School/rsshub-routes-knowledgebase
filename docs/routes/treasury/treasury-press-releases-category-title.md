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
  "heat": 1,
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
  "topFeeds": [
    {
      "description": "Press Releases | U.S. Department of the TreasuryLock - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1270142923911856128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://home.treasury.gov/news/press-releases",
      "title": "Press Releases | U.S. Department of the TreasuryLock",
      "type": "feed",
      "url": "rsshub://treasury/press-releases"
    }
  ]
}
```
