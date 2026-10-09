# INSPIRE - Collection Search

## Coverage
`index-only`

## Route
- Namespace: `inspirehep`
- Namespace Name: `INSPIRE`
- Route Path: `/inspirehep/:collection{jobs|seminars|conferences|institutions|experiments|journals}/:q?`
- Route Name: `Collection Search`
- Example: `/inspirehep/jobs`
- URL: `inspirehep.net`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `DIYgod`
- Source Location: `collections.tsx`
- Source Module: `_None_`

## Description
Jobs use the most recent creation date, conferences and seminars use the most recent event date, and other collections use the publisher's search ordering. Journals and institutions feeds contain directory records; use Literature Search to subscribe to their publications.

## Parameters
- `collection`: {"description": "Collection to subscribe to", "options": [{"label": "Jobs", "value": "jobs"}, {"label": "Seminars", "value": "seminars"}, {"label": "Conferences", "value": "conferences"}, {"label": "Institutions", "value": "institutions"}, {"label": "Experiments", "value": "experiments"}, {"label": "Journals", "value": "journals"}]}
- `q`: Optional search query, using the same syntax as the INSPIRE website


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `inspirehep.net/jobs`
- `target`: `/jobs`
### Rule 2
- `source`:
  - `inspirehep.net/seminars`
- `target`: `/seminars`
### Rule 3
- `source`:
  - `inspirehep.net/conferences`
- `target`: `/conferences`
### Rule 4
- `source`:
  - `inspirehep.net/institutions`
- `target`: `/institutions`
### Rule 5
- `source`:
  - `inspirehep.net/experiments`
- `target`: `/experiments`
### Rule 6
- `source`:
  - `inspirehep.net/journals`
- `target`: `/journals`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Jobs use the most recent creation date, conferences and seminars use the most recent event date, and other collections use the publisher's search ordering. Journals and institutions feeds contain directory records; use Literature Search to subscribe to their publications.",
  "example": "/inspirehep/jobs",
  "heat": 0,
  "location": "collections.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Collection Search",
  "parameters": {
    "collection": {
      "description": "Collection to subscribe to",
      "options": [
        {
          "label": "Jobs",
          "value": "jobs"
        },
        {
          "label": "Seminars",
          "value": "seminars"
        },
        {
          "label": "Conferences",
          "value": "conferences"
        },
        {
          "label": "Institutions",
          "value": "institutions"
        },
        {
          "label": "Experiments",
          "value": "experiments"
        },
        {
          "label": "Journals",
          "value": "journals"
        }
      ]
    },
    "q": "Optional search query, using the same syntax as the INSPIRE website"
  },
  "path": "/:collection{jobs|seminars|conferences|institutions|experiments|journals}/:q?",
  "radar": [
    {
      "source": [
        "inspirehep.net/jobs"
      ],
      "target": "/jobs"
    },
    {
      "source": [
        "inspirehep.net/seminars"
      ],
      "target": "/seminars"
    },
    {
      "source": [
        "inspirehep.net/conferences"
      ],
      "target": "/conferences"
    },
    {
      "source": [
        "inspirehep.net/institutions"
      ],
      "target": "/institutions"
    },
    {
      "source": [
        "inspirehep.net/experiments"
      ],
      "target": "/experiments"
    },
    {
      "source": [
        "inspirehep.net/journals"
      ],
      "target": "/journals"
    }
  ],
  "topFeeds": []
}
```
