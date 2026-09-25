# INSPIRE - Literature Search

## Coverage
`index-only`

## Route
- Namespace: `inspirehep`
- Namespace Name: `INSPIRE`
- Route Path: `/inspirehep/literature/:q`
- Route Name: `Literature Search`
- Example: `/inspirehep/literature/Physics`
- URL: `inspirehep.net`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `literature.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `q`: Search keyword


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `inspirehep.net/literature`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/inspirehep/literature/Physics",
  "heat": 26,
  "location": "literature.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Literature Search",
  "parameters": {
    "q": "Search keyword"
  },
  "path": "/literature/:q",
  "radar": [
    {
      "source": [
        "inspirehep.net/literature"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Literature Search - INSPIRE - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67195512624501760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=Physics",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/Physics"
    },
    {
      "description": "Literature Search - INSPIRE - Powered by RSSHub",
      "errorAt": "2025-03-05T15:13:11.683Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "69965125338796055",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20E.Witten.1",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/a%20E.Witten.1"
    }
  ]
}
```
