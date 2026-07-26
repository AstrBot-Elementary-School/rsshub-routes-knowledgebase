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
      "id": "69965125338796038",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20V.E.Hubeny.1",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/a%20V.E.Hubeny.1"
    },
    {
      "description": "Literature Search - INSPIRE - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69965125338796039",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20G.Compere.1",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/a%20G.Compere.1"
    }
  ]
}
```
