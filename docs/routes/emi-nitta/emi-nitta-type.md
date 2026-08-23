# Emi Nitta - Recent update / News

## Coverage
`index-only`

## Route
- Namespace: `emi-nitta`
- Namespace Name: `Emi Nitta`
- Route Path: `/emi-nitta/:type`
- Route Name: `Recent update / News`
- Example: `/emi-nitta/updates`
- URL: `emi-nitta.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `luyuhuang`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Type, `updates` or `news`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `emi-nitta.net/updates`
- `target`: `/updates`
### Rule 2
- `source`:
  - `emi-nitta.net/contents/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/emi-nitta/updates",
  "heat": 0,
  "location": "home.ts",
  "maintainers": [
    "luyuhuang"
  ],
  "name": "Recent update / News",
  "parameters": {
    "type": "Type, `updates` or `news`"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "emi-nitta.net/updates"
      ],
      "target": "/updates"
    },
    {
      "source": [
        "emi-nitta.net/contents/news"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": []
}
```
