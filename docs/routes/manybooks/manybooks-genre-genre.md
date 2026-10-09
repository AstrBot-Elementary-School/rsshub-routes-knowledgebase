# ManyBooks - Books by genre

## Coverage
`index-only`

## Route
- Namespace: `manybooks`
- Namespace Name: `ManyBooks`
- Route Path: `/manybooks/genre/:genre`
- Route Name: `Books by genre`
- Example: `/manybooks/genre/romance`
- URL: `manybooks.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `DIYgod`
- Source Location: `genre.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `genre`: Genre slug from a ManyBooks /genres/ page, such as romance or science-fiction.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `manybooks.net/genres/:genre`
- `target`: `/genre/:genre`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/manybooks/genre/romance",
  "heat": 0,
  "location": "genre.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Books by genre",
  "parameters": {
    "genre": "Genre slug from a ManyBooks /genres/ page, such as romance or science-fiction."
  },
  "path": "/genre/:genre",
  "radar": [
    {
      "source": [
        "manybooks.net/genres/:genre"
      ],
      "target": "/genre/:genre"
    }
  ],
  "topFeeds": []
}
```
