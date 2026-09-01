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
      "errorAt": "2025-05-20T20:52:20.637Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "69965125338796043",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20Mohammad.Mehdi.Sheikh.Jabbari.1",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/a%20Mohammad.Mehdi.Sheikh.Jabbari.1"
    },
    {
      "description": "Literature Search - INSPIRE - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69965125338796041",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=a%20L.Susskind.1",
      "title": "Literature Search - INSPIRE",
      "type": "feed",
      "url": "rsshub://inspirehep/literature/a%20L.Susskind.1"
    }
  ]
}
```
