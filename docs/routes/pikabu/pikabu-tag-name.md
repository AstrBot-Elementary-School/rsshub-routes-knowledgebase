# Pikabu - Tag

## Coverage
`index-only`

## Route
- Namespace: `pikabu`
- Namespace Name: `Pikabu`
- Route Path: `/pikabu/tag/:name`
- Route Name: `Tag`
- Example: `/pikabu/tag/Metallica`
- URL: `pikabu.ru`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: Tag name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `pikabu.ru/tag/:name`
- `target`: `/tag/:name`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pikabu/tag/Metallica",
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Tag",
  "parameters": {
    "name": "Tag name"
  },
  "path": "/tag/:name",
  "radar": [
    {
      "source": [
        "pikabu.ru/tag/:name"
      ],
      "target": "/tag/:name"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
