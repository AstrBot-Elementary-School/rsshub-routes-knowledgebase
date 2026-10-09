# ACEA - Publications

## Coverage
`index-only`

## Route
- Namespace: `acea`
- Namespace Name: `ACEA`
- Route Path: `/acea/publications/:type?`
- Route Name: `Publications`
- Example: `/acea/publications/press-releases`
- URL: `www.acea.auto`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `DIYgod`
- Source Location: `publications.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Native content type, e.g. press-releases, facts, figures or publications. Defaults to press-releases.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.acea.auto/nav/`
- `target`: `/publications`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/acea/publications/press-releases",
  "heat": 0,
  "location": "publications.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Publications",
  "parameters": {
    "type": "Native content type, e.g. press-releases, facts, figures or publications. Defaults to press-releases."
  },
  "path": "/publications/:type?",
  "radar": [
    {
      "source": [
        "www.acea.auto/nav/"
      ],
      "target": "/publications"
    }
  ],
  "topFeeds": []
}
```
