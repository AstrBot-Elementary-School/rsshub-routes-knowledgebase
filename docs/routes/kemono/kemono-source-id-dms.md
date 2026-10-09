# Kemono - Creator direct messages

## Coverage
`index-only`

## Route
- Namespace: `kemono`
- Namespace Name: `Kemono`
- Route Path: `/kemono/:source/:id/dms`
- Route Name: `Creator direct messages`
- Example: `/kemono/patreon/123870346/dms`
- URL: `kemono.cr`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `DIYgod`
- Source Location: `dms.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `source`: Source from the website URL, such as patreon.
- `id`: Creator ID from the website URL.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `kemono.cr/:source/user/:id/dms`
- `target`: `/:source/:id/dms`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/kemono/patreon/123870346/dms",
  "features": {
    "nsfw": true
  },
  "heat": 0,
  "location": "dms.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Creator direct messages",
  "parameters": {
    "id": "Creator ID from the website URL.",
    "source": "Source from the website URL, such as patreon."
  },
  "path": "/:source/:id/dms",
  "radar": [
    {
      "source": [
        "kemono.cr/:source/user/:id/dms"
      ],
      "target": "/:source/:id/dms"
    }
  ],
  "topFeeds": []
}
```
