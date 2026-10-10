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
- `type`: {"default": "press-releases", "description": "Native content type", "options": [{"label": "Press releases", "value": "press-releases"}, {"label": "News", "value": "news"}, {"label": "Facts", "value": "facts"}, {"label": "Figures", "value": "figures"}, {"label": "Publications", "value": "publications"}]}


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
    "type": {
      "default": "press-releases",
      "description": "Native content type",
      "options": [
        {
          "label": "Press releases",
          "value": "press-releases"
        },
        {
          "label": "News",
          "value": "news"
        },
        {
          "label": "Facts",
          "value": "facts"
        },
        {
          "label": "Figures",
          "value": "figures"
        },
        {
          "label": "Publications",
          "value": "publications"
        }
      ]
    }
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
