# WebNovel - Novel rankings

## Coverage
`index-only`

## Route
- Namespace: `webnovel`
- Namespace Name: `WebNovel`
- Route Path: `/webnovel/ranking/:type?`
- Route Name: `Novel rankings`
- Example: `/webnovel/ranking`
- URL: `webnovel.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `DIYgod`
- Source Location: `ranking.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "power", "description": "Novel ranking type.", "options": [{"label": "power", "value": "power"}, {"label": "trending", "value": "trending"}, {"label": "collect", "value": "collect"}, {"label": "popular", "value": "popular"}, {"label": "update", "value": "update"}, {"label": "active", "value": "active"}, {"label": "fandom", "value": "fandom"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `webnovel.com/ranking`
- `target`: `/ranking`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/webnovel/ranking",
  "heat": 0,
  "location": "ranking.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Novel rankings",
  "parameters": {
    "type": {
      "default": "power",
      "description": "Novel ranking type.",
      "options": [
        {
          "label": "power",
          "value": "power"
        },
        {
          "label": "trending",
          "value": "trending"
        },
        {
          "label": "collect",
          "value": "collect"
        },
        {
          "label": "popular",
          "value": "popular"
        },
        {
          "label": "update",
          "value": "update"
        },
        {
          "label": "active",
          "value": "active"
        },
        {
          "label": "fandom",
          "value": "fandom"
        }
      ]
    }
  },
  "path": "/ranking/:type?",
  "radar": [
    {
      "source": [
        "webnovel.com/ranking"
      ],
      "target": "/ranking"
    }
  ],
  "topFeeds": []
}
```
